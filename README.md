# 🏆 Mundo de Campeones — Links y Recursos

Marca deportiva familiar runner · Popayán, Colombia

---

## 🔗 Links principales

| Recurso | Link | Acceso |
|---|---|---|
| 🌐 Landing page pública | [ktalynagb.github.io/mundo-de-campeones](https://ktalynagb.github.io/mundo-de-campeones/) | Público |
| 🔒 Gestor operativo | [mc-gestor_.html](https://ktalynagb.github.io/mundo-de-campeones/mc-gestor_.html) | Privado (login) |
| 📊 Google Sheets catálogo | [Abrir Sheet](https://docs.google.com/spreadsheets/d/1CpV-uz_x5UQ2f3UUI7GNUUc_Alq0s8PSd1cXxgPoixk/edit?usp=sharing) | Equipo MC |

---

## 🔐 Acceso gestor operativo

- **Usuario:** `mundodecampeones`
- **Contraseña:** `MC123*`

---

## 📊 Google Sheets — Estructura del catálogo

| Columna | Campo | Valores válidos |
|---|---|---|
| A | nombre | Nombre del producto |
| B | categoria | `tenis` / `ropa` / `lifestyle` / `accesorios` / `kits` |
| C | descripcion | Texto libre |
| D | precio | Ej: `$180.000` o `Consultar` |
| E | foto | URL de Imgur (`https://imgur.com/XXXXXXX`) |
| F | tag | `Top ventas` / `Nuevo` / `Lifestyle` / (vacío) |
| G | disponible | `SI` / `NO` |

### Hoja `config` (video de la sección)
| clave | valor |
|---|---|
| video | URL de YouTube con embed habilitado |

---

## 📸 Fotos de productos — Imgur

- **Álbum:** [imgur.com/a/AVgtbpd](https://imgur.com/a/AVgtbpd)
- Subir foto → copiar link → pegar en columna `foto` del Sheet
- El sistema convierte automáticamente `imgur.com/XXX` → `i.imgur.com/XXX.jpeg`

---

## 🚀 Cómo actualizar la página

```powershell
cd D:\AA.MC\mundo-de-campeones
git add .
git commit -m "descripcion del cambio"
git push
```

La página se actualiza en ~2 minutos después del push.

---

## 📁 Archivos del repo

| Archivo | Descripción |
|---|---|
| `index.html` | Landing page pública |
| `mc-gestor_.html` | Gestor operativo privado |
| `logo_mc_transparente.png` | Logo oficial MC |
| `IMAGEN_FAMILIA_1_.jpeg` | Foto sección ¿Por qué MC? |
| `PROBADO_PISTA_.jpeg` | Foto probado en pista |
| `COMUNIDAD_NO_CLIENTES_.jpeg` | Foto comunidad |
| `FOTO_CARRERA_.jpeg` | Foto nosotros (wide) |
| `FAMILIA_MC_.jpeg` | Foto familia |
| `META_LOGRADA_.jpeg` | Foto meta lograda |
| `365_.jpeg` | Foto lifestyle 365 días |

---

## 📞 Contacto MC

- **WhatsApp:** [+57 313 520 8083](https://wa.me/573135208083)
- **Instagram:** [@mc_mundo.de.campeones](https://www.instagram.com/mc_mundo.de.campeones)
- **Ciudad:** Popayán, Colombia
