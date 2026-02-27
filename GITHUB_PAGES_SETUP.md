# Instrucciones para Publicar en GitHub Pages

## Paso 1: Crear el Repositorio

1. Ve a GitHub (https://github.com)
2. Haz clic en el botón "+" en la esquina superior derecha
3. Selecciona "New repository"
4. Nombre del repositorio: `TelefonosMapfre`
5. Descripción: "Guía de contactos TSR - MAPFRE"
6. Marca como "Public" o "Private" según tus necesidades
7. **NO** marques "Add a README file" (ya tenemos uno)
8. Haz clic en "Create repository"

## Paso 2: Subir los Archivos

### Opción A: Desde la Web de GitHub (Fácil)

1. En la página del repositorio recién creado, haz clic en "uploading an existing file"
2. Arrastra TODOS estos archivos:
   - index.html
   - manifest.json
   - sw.js
   - README.md
   - .gitignore
   - Todos los archivos icon-*.png (11 archivos)
3. Escribe un mensaje de commit: "Primera versión de TelefonosMapfre"
4. Haz clic en "Commit changes"

### Opción B: Desde la Terminal/Git (Avanzado)

```bash
git init
git add .
git commit -m "Primera versión de TelefonosMapfre"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TelefonosMapfre.git
git push -u origin main
```

## Paso 3: Activar GitHub Pages

1. Ve a la página de tu repositorio
2. Haz clic en "Settings" (⚙️)
3. En el menú lateral izquierdo, haz clic en "Pages"
4. En "Source", selecciona:
   - Branch: `main`
   - Folder: `/ (root)`
5. Haz clic en "Save"
6. Espera unos minutos (1-5 minutos)
7. Refresca la página
8. Verás un mensaje verde con la URL de tu aplicación:
   `Your site is published at https://TU-USUARIO.github.io/TelefonosMapfre/`

## Paso 4: Probar la Aplicación

1. Abre la URL en tu navegador
2. En móvil: Sigue las instrucciones del README.md para instalarla
3. En PC: Haz clic en el icono de instalación en la barra de direcciones

## Paso 5: Compartir la Aplicación

Comparte esta URL con tu equipo:
```
https://TU-USUARIO.github.io/TelefonosMapfre/
```

## Actualizar la Aplicación

Para hacer cambios:

1. Edita los archivos en tu repositorio
2. Haz commit de los cambios
3. GitHub Pages se actualizará automáticamente en 1-5 minutos

## ⚠️ Importante

- **Verifica que todos los 11 archivos de iconos estén subidos**
- **No cambies el nombre de `index.html`** (debe ser exactamente ese nombre)
- **Asegúrate de que el repositorio esté configurado como Public** si quieres compartirlo públicamente

## 🆘 Solución de Problemas

### "La aplicación no carga"
- Verifica que GitHub Pages esté activado en Settings > Pages
- Espera 5 minutos después de subir los archivos
- Limpia la caché del navegador (Ctrl+Shift+R o Cmd+Shift+R)

### "Los iconos no aparecen"
- Verifica que todos los archivos icon-*.png estén en la raíz del repositorio
- Revisa la consola del navegador (F12) para ver errores

### "No puedo instalar la aplicación"
- Asegúrate de que estás usando HTTPS (GitHub Pages lo hace automáticamente)
- En iOS, debes usar Safari (no Chrome)
- En Android, puedes usar Chrome o Edge

## 📞 Contacto

Para soporte adicional, contacta con el equipo de desarrollo.
