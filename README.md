# xgdier_ · Portafolio

Portafolio de **xgdier_**, desarrollador full-stack de Minecraft: fork de servidor propio (NIGHT), proxies Velocity, plugins, bots de Discord y páginas web para networks.

Es una web estática, sin build ni dependencias: HTML, CSS y JavaScript en un solo `index.html`.

## Qué tiene

- Skin 3D de `xgdier_` con capa, que se puede girar y animar (skinview3d).
- Navegación por pestañas, sin scroll en escritorio: Inicio, Servicios, Experiencia, Proyectos, KaxGuard y Contacto. También con las flechas ← →.
- Fondo con una rejilla de redstone en canvas que reacciona al ratón.
- Visor de proyectos con capturas a pantalla completa.
- Maqueta interactiva del `/setup` del bot KaxGuard.
- Música de fondo con play/pausa, silencio y volumen.

## Estructura

```
index.html                  la web entera
favicon.svg
img/                        capturas, skin, capa y logos del stack
audio/legacy.mp3            música de fondo
vendor/skinview3d.bundle.js visor 3D de skins (MIT, ver vendor/LICENSE-skinview3d)
```

## Verla en local

Hay que abrirla con un servidor, no con doble clic, para que carguen la skin y la música:

```bash
npx serve .
```

## Contacto

- Discord: [abrir ticket](https://discord.gg/XsK4PPQjy7)
- Correo: ediytem@gmail.com
- GitHub: [ediguard23](https://github.com/ediguard23)
