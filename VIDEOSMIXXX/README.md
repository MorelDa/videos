# VIDEOSMIXXX

Videos alojados en este repositorio.

Los archivos `.mp4` **no** están en el historial de git (GitHub bloquea ficheros de más de 100 MB).
Se publican como *assets* de GitHub Releases, en la carpeta virtual `VIDEOSMIXXX/`.

## Descargas

| # | Archivo | Calidad | Tamaño | Enlace |
|---|---------|---------|--------|--------|
| 1 | `VIDEOSMIXXX.video-1.mp4` | 1200x720 @30fps, H.264 | 1008 MB | [Descargar](https://github.com/MorelDa/videos/releases/download/v1/VIDEOSMIXXX.video-1.mp4) |

## Uso

La URL directa (`.../releases/download/...`) se puede usar tal cual en:

- `ffmpeg` / `VLC` / cualquier reproductor
- `<video src="...">` en una web
- `yt-dlp -o video.mp4 "<url>"` para bajar el archivo completo

## Notas técnicas

Los assets de un Release permiten hasta **2 GB** por archivo, por eso los vídeos grandes
se publican así y no con `git push` (límite duro: 100 MB por fichero).
