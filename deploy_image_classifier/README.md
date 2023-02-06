# [Deploy модели классификации изображений](https://github.com/WhiteNivis/projects/tree/main/deploy_image_classifier)

Ресурсы:

 - `images` - примеры изображений;
 - `templates` - макет страницы;
 - `app.py` - исполняемый файл;
 - `Dockerfile`, `requirements.txt` - файлы Docker

Команды Docker:

 : docker build -t image_classifier .
 : docker run -d -p 5050:5050 image_classifier

  
