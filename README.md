# 🍼 Leo Planning Familiar — Instrucciones de despliegue

## Lo que necesitáis (todo gratis)
- Cuenta Google (ya la tenéis)
- GitHub Desktop (ya lo tenéis)
- Cuenta Vercel (gratis, se crea en 2 min)

---

## PASO 1 — Crear proyecto Firebase (5 minutos)

1. Id a **console.firebase.google.com**
2. Click "Añadir proyecto" → nombre: `leo-planning`
3. Desactivad Google Analytics → "Crear proyecto"
4. En el menú izquierdo: **Realtime Database** → "Crear base de datos"
   - Elegid "Modo de prueba" → "Habilitar"
5. En el menú izquierdo: click el icono ⚙️ → "Configuración del proyecto"
6. Bajad hasta "Tus apps" → click `</>` (web)
7. Nombre: `leo-app` → "Registrar app"
8. **COPIAD el objeto firebaseConfig** que aparece — lo necesitáis en el paso 2

---

## PASO 2 — Pegar vuestra config Firebase

1. Abrid el archivo **index.html** con cualquier editor de texto (Notepad, TextEdit)
2. Buscad este bloque cerca del final:
```
const firebaseConfig = {
  apiKey: "VUESTRA_API_KEY",
  ...
```
3. Reemplazad TODO ese bloque con el que copiasteis de Firebase
4. Guardad el archivo

---

## PASO 3 — Subir a GitHub Desktop

1. Abrid GitHub Desktop
2. "File" → "New Repository" → nombre: `leo-planning` → "Create Repository"
3. "Show in Explorer/Finder" → copiad los archivos de esta carpeta ahí dentro
4. En GitHub Desktop: escribid "primera versión" en el mensaje → "Commit to main"
5. Click "Publish repository" (dejad en público o privado, da igual)

---

## PASO 4 — Desplegar en Vercel (3 minutos)

1. Id a **vercel.com** → "Sign up with GitHub"
2. "New Project" → seleccionad el repositorio `leo-planning`
3. Click "Deploy" — sin tocar nada más
4. En 1 minuto os da una URL tipo: `leo-planning.vercel.app`

---

## ¡Listo! Compartir con Mar y Emilia

- Enviadles la URL por WhatsApp
- Cualquiera que la abra ve y edita en tiempo real
- Se puede añadir al escritorio del móvil como app:
  - **iPhone**: Safari → compartir → "Añadir a pantalla de inicio"
  - **Android**: Chrome → menú → "Añadir a pantalla de inicio"

---

## Actualizar la app en el futuro

Si queréis cambiar algo:
1. Editad el index.html
2. En GitHub Desktop: "Commit" → "Push"
3. Vercel actualiza automáticamente en 30 segundos

