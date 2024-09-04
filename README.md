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
![Alt text](https://github.com/Zalr765/rami-readme/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-09-04%20%D0%B2%2016.59.42.png)
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
