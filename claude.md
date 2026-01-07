# Context del Projecte - Web Credencial Zoopa/VIENA

## Objectiu
Crear una pàgina web credencial de Zoopa mostrant el projecte VIENA com a cas d'èxit per a una licitació del **Departament de Política Lingüística de la Generalitat** (servei de disseny gràfic 2026).

---

## Fitxer principal
`/Users/cop/Documents/claudecode/Politica_Linguistica_GENERALITAT/LICITACION_GRAFISMO/VIENA/index.html`

---

## Estructura actual de la web (9 seccions amb scroll continu)

1. **Hero** - Logo ZOOPA, títol "Projecte VIENA", fons portada.webp
2. **Introducció** - "VIENA 2024-2025" amb estadístiques
3. **Capacitat tècnica** - Vídeo autoplay (display-mati.mp4) + enllaç zoopa.cat
4. **Adaptabilitat** - Grid 3 formats (carousel, stories, web)
5. **Qualitat gràfica** - Grid 3 productes
6. **Qualitat lingüística** - Característiques + imatge B/N
7. **Sistema de validació** - 4 fases amb línia de progrés
8. **Portafolis audiovisual** - Grid 6 vídeos amb controls
9. **Footer** - Logo ZOOPA + www.zoopa.cat + Barcelona

---

## Assets disponibles

### Imatges (`assets/images/`)
- portada.webp / portada.jpg
- logos-tazas.webp / logos-tazas.jpg
- hi-chai-model.webp / hi-chai-model.jpg
- matxa-xa-model.webp / matxa-xa-model.jpg
- matxa-xa-model-gs.webp / matxa-xa-model-gs.jpg
- toffee-coffee-model.webp / toffee-coffee-model.jpg
- carousel-matxa-xa.webp / carousel-matxa-xa.jpg
- carousel-toffee-coffee.webp / carousel-toffee-coffee.jpg
- captura-pantalla.webp / captura-pantalla.jpg

### Vídeos (`assets/videos/`)
- display-mati.mp4 (2.3MB) - vídeo destacat amb autoplay
- video-01.mp4 (1.2MB)
- video-02.mp4 (4.8MB)
- video-03.mp4 (7.8MB)
- video-04.mp4 (1.6MB)
- video-05.mp4 (6.1MB)
- video-06.mp4 (3.3MB)

### Logos Zoopa (`assets/logos/`)
- logo-zoopa-white.svg (per fons fosc)
- logo-zoopa-black.svg (per fons clar)

### Thumbnails vídeos (`assets/thumbnails/`)
- thumb-video-01.jpg
- thumb-video-02.jpg
- thumb-video-03.jpg
- thumb-video-04.jpg
- thumb-video-05.jpg
- thumb-video-06.jpg

---

## Estètica i disseny

### Paleta de colors
- Chai: #C4A574
- Matcha: #9CBD5C
- Toffee: #E89B3C
- Cream: #FAF8F5
- Text: #1A1A1A

### Tipografies
- Display: Playfair Display (Google Fonts)
- Body: DM Sans (Google Fonts)

### Animacions
- Fade-in al scroll (IntersectionObserver)
- Transicions suaus (cubic-bezier)
- Hover effects a cards i botons

---

## Requisits tècnics
- Idioma: Català (ortografia i accents correctes)
- Responsive: Mòbil, tablet, desktop
- Rendiment: Usar WebP per imatges
- Navegació: Scroll continu + menú fix amb ancoratges

---

## Context de la licitació

La web serveix per mostrar les capacitats de Zoopa:
- **Capacitat tècnica:** Disseny gràfic, animació (After Effects), producció audiovisual
- **Adaptabilitat multiformat:** Creativitats concebudes per múltiples canals
- **Qualitat gràfica:** Claredat comunicativa, coherència visual
- **Qualitat lingüística:** Revisió per lingüistes certificats
- **Sistema de validació:** 4 fases (revisió creativa, comprovació tècnica, validació lingüística, control final)

---

## Comandes útils

```bash
# Obrir la web al navegador
open /Users/cop/Documents/claudecode/Politica_Linguistica_GENERALITAT/LICITACION_GRAFISMO/VIENA/index.html

# Generar thumbnail d'un vídeo
ffmpeg -i assets/videos/video-01.mp4 -ss 00:00:01 -vframes 1 assets/thumbnails/thumb-video-01.jpg

# Verificar pes total
du -sh assets/
```

---

## Instruccions per continuar

```
Continua amb la implementació de la web credencial Zoopa/VIENA.

Fitxer: /VIENA/index.html

Tasques:
1. Thumbnails + icona play als vídeos del portafolis
2. Revisar mida i estructura d'imatges (no tallades)
3. Estadístiques: 18 Productes, 42 Vídeos, +90 Formats
4. Usar logos SVG de Zoopa (assets/logos/)

En acabar, obre al navegador.
```
