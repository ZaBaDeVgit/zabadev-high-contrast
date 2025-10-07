# 🟦 ZabaDev High Contrast – Windsurf Edition

**Autor:** Juan José Zabala Ríos
**Versión:** 1.0.0
**Licencia:** MIT

Un tema oscuro de **alto contraste** con fondo negro puro y colores vibrantes rojo, púrpura y verde.
Diseñado especialmente para **Windsurf IDE y Visual Studio Code**, ofreciendo máxima legibilidad, intensidad y estética moderna.

---

## 🎨 Paleta de colores
| Elemento | Color | Descripción |
|-----------|--------|-------------|
| Fondo principal | `#000000` | Negro absoluto |
| Texto | `#E6E6E6` | Gris claro de alto contraste |
| Palabras clave | `#FF006E` | Rosa neón intenso |
| Strings | `#BA00FF` | Púrpura brillante |
| Variables | `#00FF9F` | Verde neón |
| Funciones | `#00FFD1` | Cian brillante |
| Comentarios | `#777777` | Gris tenue |

---

## ⚙️ Instalación manual

1. Clona o descarga este repositorio.
2. Copia la carpeta en tu directorio de extensiones de VS Code:
   - **Windows:** `%USERPROFILE%\.vscode\extensions`
3. Reinicia VS Code o Windsurf IDE.
4. Selecciona el tema:
   `Ctrl + K + T → ZabaDev High Contrast – Windsurf Edition`

---

## 🛠️ Publicación

Para empaquetar y subir a VSX:

```bash
npm install -g @vscode/vsce
vsce package
vsce publish
