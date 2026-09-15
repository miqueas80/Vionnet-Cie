# Vionnet & Cie — GitHub Pages

## Publicar directamente en GitHub

1. Creá o abrí un repositorio en GitHub.
2. Subí `index.html` y la carpeta `images`.
3. Entrá en **Settings → Pages**.
4. En **Build and deployment**, seleccioná:
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
5. Guardá y esperá a que GitHub publique la página.

## WhatsApp

Abrí `index.html` y cambiá:

```js
const WHATSAPP_NUMBER = "5493435353185";
```

Usá el número internacional sin `+`, espacios ni guiones.

## Nota

Esta versión es estática y funciona directamente en GitHub Pages: no necesita Node.js, Next.js ni servidor.
