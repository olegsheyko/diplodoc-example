# Простой проект документации с помощью YFM


## Структура проекта
Базовый проект содержит несколько конфигурационных файлов и страниц с фактическим содержимым. Файлы конфигурации и markdown объединены в следующую структуру:

```
input-folder
|-- .yfm (config file for whole project)
|-- toc.yaml (table of content)
|-- presets.yaml (presets for vairables)
|-- index.yaml (index page)
|-- pages (Content pages)
    |-- faq.md
    |-- how-to.md
|-- _assets (directory with pictures)
    |-- image1.png
    |-- image2.png
|-- _includes (directory for reusable content)
    |-- faq_shared_block.md
```


