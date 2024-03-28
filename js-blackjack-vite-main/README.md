# BlackJack Vite

Pasos para ejecutar proyecto:

1. Clonar repositorio
2. Ejecutar ```npm install``` para reconstruir los módulos de node
3. Correr el devServer ```npm run dev```

## Producción

1. Ejecutar ```npm run build```
2. Tomar la carpeta ```dist``` y desplegarla

Configuración package.json
{
  "name": "blackjack-vite",
  "private": true,
  "version": "0.0.0",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "devDependencies": {
    "vite": "^2.9.15"
  },
  "dependencies": {
    "underscore": "^1.13.6"
  }
}