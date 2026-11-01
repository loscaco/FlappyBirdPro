# Flappy Bird Pro

Versión de producción de Flappy Bird, optimizada para **Twitter/X Player Cards**.

## 🎮 Características

- Física con delta-time real
- Partículas y screen shake
- Dificultad progresiva
- Sistema de medallas (10 / 25 / 50)
- Sonidos generados con Web Audio API
- High score persistente
- Diseño premium y responsive
- Listo para embeber en posts de X

## 🚀 Cómo usarlo

### 1. Subir a GitHub Pages

1. Creá un repositorio (o usá el existente `Flappy-Bird`)
2. Subí estos archivos a la rama `main`:
   - `index.html`
   - `play.html`
   - `README.md`
   - `preview.jpg` (creala vos)
3. Activá **GitHub Pages** en Settings → Pages → Deploy from branch `main` / root

Tu juego quedará en:
```
https://loscaco.github.io/Flappy-Bird/
```

### 2. Configurar Player Card

Editá en `index.html` y `play.html`:

```html
<meta name="twitter:site" content="@TU_USUARIO_REAL" />
```

Y asegurate de que las URLs apunten a tu dominio real.

### 3. Imagen de preview

Creá un archivo `preview.jpg` (recomendado **512×512** o **360×640**) con el pajarito + título "Flappy Bird Pro" y subilo a la raíz del repo.

### 4. Validar la Card

1. Andá a → https://cards-dev.x.com/validator
2. Pegá la URL de tu `index.html`
3. Verificá que detecte la **Player Card** correctamente

### 5. Postear en X

Publicá el link:
```
https://loscaco.github.io/Flappy-Bird/
```

En la web de X debería aparecer el player embebido.

## 📁 Estructura

```
/
├── index.html      ← Página de share (la que posteás)
├── play.html       ← El juego real (cargado por el player)
├── preview.jpg     ← Imagen de la card (la tenés que crear)
└── README.md
```

## 🛠️ Personalización rápida

- Cambiar dificultad → variables `CFG` dentro de `play.html`
- Colores → buscar los valores hex en el CSS y canvas
- Textos → función `tone()` y objeto `SFX`

---

Hecho con calidad de producción.
