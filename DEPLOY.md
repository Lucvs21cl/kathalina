# 🚀 Instrucciones de Despliegue en GitHub

## Paso 1: Inicializar Git (si no lo has hecho)

```bash
cd /Users/lucasmorales/Desktop/Katha
git init
```

## Paso 2: Agregar archivos al repositorio

```bash
git add .
git commit -m "Primera versión de Kathalina - página web romántica"
```

## Paso 3: Conectar con GitHub

```bash
git remote add origin https://github.com/[TU-USUARIO]/kathalina.git
git branch -M main
git push -u origin main
```

## Paso 4: Activar GitHub Pages

1. Ve a tu repositorio en GitHub: `https://github.com/[TU-USUARIO]/kathalina`
2. Haz clic en **Settings** (Configuración)
3. Desplázate hacia abajo hasta **Pages**
4. En **Source**, selecciona **Deploy from a branch**
5. En **Branch**, selecciona **main**
6. En **Folder**, selecciona **/ (root)**
7. Haz clic en **Save**

## Paso 5: Acceder a tu página

Tu página estará disponible en:
- **URL:** `https://[TU-USUARIO].github.io/kathalina`
- **Ejemplo:** `https://lucasmorales.github.io/kathalina`

## 🔄 Actualizaciones futuras

Para actualizar tu página:

```bash
git add .
git commit -m "Descripción del cambio"
git push origin main
```

Los cambios se reflejarán automáticamente en GitHub Pages en unos minutos.

## 📱 Características de GitHub Pages

- ✅ **HTTPS automático** - Tu página será segura
- ✅ **Dominio personalizado** - Puedes usar tu propio dominio
- ✅ **CDN global** - Carga rápida desde cualquier lugar
- ✅ **Actualizaciones automáticas** - Cada push actualiza la página
- ✅ **Gratis** - Sin costo adicional

## 🎵 Notas importantes

- **Archivos de audio/video:** GitHub Pages soporta archivos multimedia
- **Tamaño máximo:** 1GB por repositorio
- **Ancho de banda:** 100GB por mes (más que suficiente)
- **Actualizaciones:** Pueden tardar 1-10 minutos en aparecer

## 🛠️ Solución de problemas

### Si la página no carga:
1. Verifica que GitHub Pages esté activado
2. Espera 5-10 minutos después del primer despliegue
3. Verifica que el archivo `index.html` esté en la raíz del repositorio

### Si la música no suena:
1. Verifica que el archivo `drake.mp3` esté en el repositorio
2. Algunos navegadores bloquean autoplay - el usuario debe hacer clic

### Si el video no se reproduce:
1. Verifica que `katha.mp4` esté en el repositorio
2. Asegúrate de que el formato sea compatible (MP4)

---

¡Tu página web romántica estará disponible en todo el mundo! 🌍💕
