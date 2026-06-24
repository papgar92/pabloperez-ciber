# Pablo SOC Card — landing de evento (React)

Tarjeta interactiva para el **Evolve Talent Day**. Tono SOC/terminal, secciones
animadas + consola opcional, bilingüe (ES/EN), PWA instalable y lista para Vercel.

Stack: **Vite + React + Tailwind + Framer Motion**.

---
<!--
## 1. Probarlo en local (opcional, recomendado)

Necesitas Node.js 18+ instalado.

```bash
cd pablo-soc
npm install
npm run dev
```

Abre la URL que aparece (normalmente `http://localhost:5173`). Verás la web tal cual.
Para parar: `Ctrl + C`.

---

## 2. Subirlo a GitHub (repo nuevo)

Desde la carpeta `pablo-soc`:

```bash
git init
git add .
git commit -m "Pablo SOC Card — landing evento"
gh repo create pablo-soc --public --source=. --remote=origin --push
```

Si no usas GitHub CLI (`gh`): crea el repo a mano en https://github.com/new
(nombre `pablo-soc`, **Public**, sin README), y luego:

```bash
git init
git add .
git commit -m "Pablo SOC Card — landing evento"
git branch -M main
git remote add origin https://github.com/papgar92/pablo-soc.git
git push -u origin main
```

> El `.gitignore` ya excluye `node_modules` y `dist`, así que no subes basura.

---

## 3. Conectarlo a Vercel (deploy automático)

1. Entra en https://vercel.com y haz **login con GitHub**.
2. **Add New… → Project**.
3. Selecciona el repo `pablo-soc` → **Import**.
4. Vercel detecta **Vite** automáticamente. No cambies nada:
   - Framework Preset: `Vite`
   - Build Command: `npm run build`
   - Output Directory: `dist`
5. Pulsa **Deploy**. En ~1 minuto tienes la URL (ej. `https://pablo-soc.vercel.app`).

Cada `git push` futuro se redespliega solo.

> **Dominio:** en Vercel → Settings → Domains puedes poner uno propio o cambiar el
> subdominio si `pablo-soc` está cogido (te dará `pablo-soc-xxxx.vercel.app`).

---

## 4. El QR

Una vez tengas la URL final de Vercel, genera el QR apuntando a ella. Opciones:
- Pídeme que te lo genere (te lo dejo en alta resolución, listo para imprimir).
- O usa cualquier generador (qr-code-generator.com, etc.) con la URL.

Imprímelo grande y nítido. Consejo: llévalo también en el móvil por si alguien
quiere escanearlo de tu pantalla.

---

## Editar contenido

Casi todo el texto (ES/EN) está en **`src/data/content.js`**. Ahí cambias:
- Datos de contacto (`CONTACT`)
- Proyectos, alertas, skills, certs, experiencia
- Textos de cada idioma (`T.es` / `T.en`)

Tras editar, `git add . && git commit -m "..." && git push` y Vercel redespliega.

---

## Quitar el badge del evento (tras el Talent Day)

En `src/data/content.js`, en `T.es` y `T.en`, borra o cambia la línea `event:`.
O elimina el bloque del badge al final de `src/App.jsx`.Ç
-->
