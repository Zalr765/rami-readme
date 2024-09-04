```
<div class="container-fluid">
    <div class="row d-flex justify-content-center">
        <div class="col-12 col-lg-9 col-xl-6">
            <div class = "my-5">
               <div class="vk-video my-5" data-video="Тут ссылка из iframe" data-img="Тут ссылка до картинки">
                    <img src="/assets/img/snippets/Play.svg" style="cursor:pointer" />
                </div>
            </div>
        </div>
    </div>
</div>
```
## data-video
data-video это датаатрибут в который нужно вставить ссылку на видео.
## Откуда брать ссылку?
1. Нужно нажать правой кнопкой мыши на видео и выбрать "копировать код для встраивания"

Чтобы вставить изображение в файл README.md, выполните следующие шаги:

Добавьте изображение в репозиторий. Поместите изображение в папку проекта, например, в папку assets или images.

Используйте Markdown синтаксис. Вставьте изображение в README.md с помощью следующего синтаксиса:

markdown
Копировать код
![Alt text](path/to/image.png)
Alt text — это альтернативный текст, который будет отображаться, если изображение не загрузится.
path/to/image.png — это путь к изображению относительно файла README.md.
Пример:
Если изображение находится в папке images, путь к изображению будет images/my-image.png, и строка в README.md будет такой:

markdown
Копировать код
![Alt text](https://i.ibb.co/8j7Z9dW/2024-09-04-16-59-42.png)
получиться что-то на подобии этого
```
<iframe src="https://vk.com/video_ext.php?oid=-26892927&id=456240257&hash=d305e90bcd9512c6" width="640" height="360" frameborder="0" allowfullscreen="1" allow="autoplay; encrypted-media; fullscreen; picture-in-picture"></iframe>
```
2. Нужна только ссылка из src
```
https://vk.com/video_ext.php?oid=-26892927&id=456240257&hash=d305e90bcd9512c6
```
эту  ссылку нужно вставить в data-video.
## data-img
В data-img находится ссылка на картинку
## Если хотим взять preview с вк
Открываем код элемента и ищем класс и из него берем ссылку на картинку
![Alt text](https://i.ibb.co/wgkxQR7/image.png)
