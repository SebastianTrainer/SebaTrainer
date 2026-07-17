# Seba Trainer — app instalable

App para que tus clientes vean sus rutinas y registren los pesos que levantan,
instalable como app real en el celular (PWA).

## 1. Requisitos

- Tener instalado [Node.js](https://nodejs.org) (versión 18 o más nueva).
- Una cuenta gratuita de [Firebase](https://console.firebase.google.com) (la
  usamos solo para que los datos se compartan entre tu celular y el de tus
  clientes — es gratis para el uso de una app chica como esta).
- Una cuenta gratuita de [Vercel](https://vercel.com) o [Netlify](https://netlify.com)
  para publicar la app con una URL propia.

## 2. Configurar el almacenamiento compartido (Firebase)

Ya hecho ✅ — las claves están en `src/firebaseConfig.js` y las reglas ya
fueron publicadas en Firestore.

## 3. Probar en tu computadora (opcional)

```bash
npm install
npm run dev
