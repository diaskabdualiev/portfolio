# Медиа для проектов / Project media

Сюда складываются фото и видео-доказательства для кейсов из `_portfolio/`.
Каждому проекту — своя папка по slug'у (совпадает с permalink), например:
`images/projects/unitree-g1-visual-search/`.

## Как добавить ФОТО

1. Положи изображения в папку проекта, напр. `1.jpg`, `2.jpg`, `cover.jpg`.
2. Открой соответствующий файл в `_portfolio/<slug>.md`.
3. Раскомментируй блок `gallery:` в front matter и (опц.) `header.teaser`
   для картинки на карточке. Пути указываются ОТНОСИТЕЛЬНО `images/`,
   то есть `projects/<slug>/1.jpg`.

## Как добавить ВИДЕО

В front matter проекта раскомментируй ОДИН из вариантов:

- **YouTube/Vimeo (embed-ссылка):**
  `video_url: https://www.youtube.com/embed/ВИДЕО_ID`
  (важно: именно `/embed/`, не обычная `watch?v=` ссылка)

- **Локальный файл .mp4:** положи `demo.mp4` в папку проекта и укажи
  `video_file: projects/<slug>/demo.mp4`

Видео встраивается адаптивно через `_includes/video.html`.

> Пока медиа не добавлены, в кейсе на месте видео/галереи стоят заглушки
> «coming soon» — они исчезнут автоматически, как только заполнишь front matter.
