# Taita Jairo Mavisoy Chindoy — Página biográfica

Sitio web estático (HTML + CSS puro) para la marca personal del Taita Jairo Mavisoy Chindoy.

## Estructura del proyecto

```
taita-jairo/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── taita-hero.png      ← foto hero (pantalla completa)
│   └── taita-about.png     ← foto sección "Sobre él"
└── README.md
```

## Cómo subir a GitHub

1. Entra a [github.com](https://github.com) con tu cuenta
2. Clic en **New repository**
3. Nombre sugerido: `taita-jairo-web`
4. Déjalo en **Public**, sin README (ya tienes este)
5. Clic en **Create repository**
6. Sigue las instrucciones que aparecen en pantalla para subir una carpeta existente:

```bash
# Desde la terminal, dentro de la carpeta del proyecto:
git init
git add .
git commit -m "Sitio inicial - biografía Taita Jairo"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/taita-jairo-web.git
git push -u origin main
```

## Cómo desplegar en Vercel

1. Entra a [vercel.com](https://vercel.com) con tu cuenta de GitHub
2. Clic en **Add New → Project**
3. Selecciona el repositorio `taita-jairo-web`
4. Vercel lo detecta automáticamente como sitio estático
5. Clic en **Deploy**
6. En menos de 1 minuto tendrás una URL tipo: `taita-jairo-web.vercel.app`

## Para actualizar el sitio

Cualquier cambio que hagas y subas a GitHub se desplegará automáticamente en Vercel.

```bash
git add .
git commit -m "Descripción del cambio"
git push
```

## Pendientes

- [ ] Confirmar usuario de Instagram del taita
- [ ] Reemplazar cita con una frase real del taita
- [ ] Añadir más fotos cuando estén disponibles
- [ ] Segunda página: Ceremonias y espacios de medicina
