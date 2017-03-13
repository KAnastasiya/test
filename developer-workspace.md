### Онлайн редакторы кода
1. [JSFiddle] (http://jsfiddle.net/) - test your JavaScript, CSS, HTML or CoffeeScript online
2. [CodePen] (http://codepen.io) - a playground for the front end web
3. [LiveWeave] (http://liveweave.com/) - a HTML5, CSS3 & JavaScript editor with real-time (live) preview

======

### Офлайн редакторы кода
1. [Sublime Text] (http://www.sublimetext.com/) - a sophisticated text editor for code, markup and prose. Настройку см. в [моем репозитории] (https://github.com/KAnastasiya/SublimeText3)
2. [Brackets] (http://brackets.io/) - a modern, open source text editor that understands web design
3. [Atom] (https://atom.io/) - a hackable text editor for the 21st Century

======

### Файл .editorconfig
*Конфигурационный файл, задача которого создать единый формат настроек, и, раз и навсегда, решить вопросы вроде “табы или пробелы” для всех IDE и всех языков программирования.*

1. [Официальный сайт] (http://editorconfig.org/)
2. [Настройка] (https://www.youtube.com/watch?v=p1Ti0wSGG54)
3. [Обзор (habrahabr.ru)] (https://habrahabr.ru/post/220131/)

======

### Автоматизация frontend-а
*Сжатия файлов, оптимизация изображений, создание спрайтов, применение изменений на лету... Это только малая часть того, что компьютер может делать за вас. Хотите разрабатывать быстрее и удобнее? Настройке автоматизацию своего проекта!*

[Автоматизируем процесс разработки] (https://github.com/KAnastasiya/Frontend_automation) (мой репозиторий с полезными ссылками и настройками)

======

### Локальный сервер на базе Node.js
1. [Установить Node.js] (https://nodejs.org/en/).

*Об установке Node на Ubuntu 16.04 см. [здесь] (https://losst.ru/ustanovka-node-js-ubuntu-16-04) !!! для установки ссылки для совместимости  выполнить команду `sudo ln -s /usr/bin/nodejs /usr/local/bin/node`*

2. Создайте каталог своего проекта, перейдите в него и выполните команду `npm init` (эта команда выдает целый ряд приглашений, которые Вы можете пропускать (нажимать Enter)).
3. Установите [Express] (http://expressjs.com/ru/) - веб-фреймворк для приложений Node.js, выполнив в каталоге Вашего проекта комманду `npm install express --save`
4. Создать файл `<ИМЯ ФАЙЛА>.js` с содержимым:
```
var express = require('express');
var app = express();
app.use(express.static('КАТАЛОГ ПРОЕКТА'));
app.listen(3000, function () {
    console.log('Example app listening on port 3000!');
});

5. Запустите сервер, выполнив в каталоге проекта команду `node <ИМЯ ФАЙЛА>.js`. 
6. Откройте в браузере страницу http://localhost:3000/, чтобы просмотреть результат
```

======

### Виртуальные машины
1. [Виртуальные машина с IE] (https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/)
2. [Windows. Доступ с виртуальной машины к локальному серверу] (http://stackoverflow.com/questions/1261975/addressing-localhost-from-a-virtualbox-virtual-machine). Также пригодится вот эта ссылочка - [Windows 7: отображение и скрытие расширений имен файлов] (http://netler.ru/ikt/windows7-extension.htm).
3. [Виртуальная машина с Safari. Инструкция по установке, Ссылки образов] (https://techsviewer.com/how-to-install-mac-os-x-el-capitan-on-pc-on-virtualbox/)
4. [Виртуальная машина с Safari. Видео по установке] (https://www.youtube.com/watch?v=7rM5iXOE7aI)
5. С виртуальной машины MAC подключать к локальному серверу можно заменив `localhost` на IP-адрес соответствующего компьютера. Узнать IP-адрес можно с помощью команды `ipconfig`*
6. [Safari. Как включить инструменты разработчика] (https://developer.apple.com/library/conte
nt/documentation/AppleApplications/Conceptual/Safari_Developer_Guide/GettingStarted/GettingStarted.html )

======

### Плагины для Google Chrome
|         Плагин         |         Назначение плагина, его возможности        |
| ---------------------- | -------------------------------------------------- |
| [PerfexPixel] (https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi?hl=ru) | allows you put a semi-transparent image overlay over the top of the HTML and perform per pixel comparison between them |
| [Page Ruler] (https://chrome.google.com/webstore/detail/page-ruler/jlpkojjdgbllmedoapgfodplfhcbnbpn/related?hl=ru) | lets your draw out a ruler to any page and displays the width, height and position of it |
| [Web Developer] (https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm/related) | adds a toolbar button with various web developer tools |
| [Clear Cache] (https://chrome.google.com/webstore/detail/clear-cache/cppjkneekbjaeellbfkmgnhonkkjfpdn/related?hl=ru) | Clear your cache and browsing data with a single click of a button |
| [ColorZilla] (https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp/related) | you can get a color reading from any point in your browser, quickly adjust this color and paste it into another program... |
| [SimpleExtManager] (https://chrome.google.com/webstore/detail/simpleextmanager/kniehgiejgnnpgojkdhhjbgbllnfkfdk/related?hl=ru) | меню для быстрого включения, выключения и доступа к настройкам расширений |
| [uBlock] (https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm/related?hl=ru) | эффективный блокировщик: использует меньше оперативной памяти и меньше нагружает ЦП, при этом используя больше фильтров |
| [Tunnel Bear] (https://chrome.google.com/webstore/detail/tunnelbear-vpn/omdakjcmkglenbhjadbccaookpfjihpa/related) | обход заблокированных сайтов, защита своих данных в интернет и т.д.|
| [Request Maker] (https://chrome.google.com/webstore/detail/request-maker/kajfghlhfkcocafkcjlajldicbikpgnp) | взаимодействие с сервером, отправка запросов и получение ответов |

======

### Photoshop для верстальщика
1. [Photoshop для кодера] (http://xiper.net/learn/photoshop/) 
2. [A Web Developer’s Guide to Photoshop] (http://rafaltomal.com/a-web-developerss-guide-to-photoshop/)
3. [Установка шрифтов] (https://www.youtube.com/watch?v=tVpmLG1PuVA)
4. [Кадрирование] (https://www.youtube.com/watch?v=BjtVlWN9A10)
5. [Пример нарезки макета для верстки] (http://gearmobile.github.io/photoshop/photoshop-example-cutting-mockup/)
6. [Нарезка картинок с тенями и др. эффектами] (http://paulradzkov.com/2012/photoshop_new_layer_based_slice/)
7. [Photoshop экшены для верстальщика] (http://vovanr.com/posts/photoshop-actions/)
8. [Экспорт слоев из Photoshop в один клик!] (http://jnet.kz/httml/2014/03/13/eksport-sloev-iz-photoshop-v-odin-klik.html)
9. [Плагин для автогенерации стилей из psd-макета] (http://loftblog.ru/material/sokrati-vremya-svoej-verstki-v-3-raza/)
10. [Avocode - прекрасная замена Photoshop] (https://avocode.com/features-developer.html)
11. [Avocode. Подробное руководство за 10 минут (Hillel IT school)] (https://www.youtube.com/watch?v=pAfMkjKY004&utm_source=newsletter&utm_medium=email&utm_campaign=kak_verstat_effektivnee&utm_term=2016-12-14)

======

### Utils
1. [Статистика использования браузеров] (http://gs.statcounter.com/#browser_version_partially_combined-ww-monthly-201501-201601)
2. Проверка поддержки браузерами тех или иных возможностей и стандартов: [caniuse.com] (caniuse.com) и [html5please.com] (html5please.com)
3. PNG-оптимизаторы: [tinypng] (https://tinypng.com/), [compresspng] (http://compresspng.com/ru/) 
4. [JPG-оптимизатор] (http://compressjpeg.com/ru/)
5. [SVG-оптимизаторы] (https://jakearchibald.github.io/svgomg/)
6. [Создание спрайтов] (http://spritepad.wearekiss.com/)
7. [Создание favicon] (http://www.favicon-generator.org/)
8. [Онлайн-конвертация изображений в base64] (http://b64.io/) 
9. Онлайн-конвертер изображений: [cloudconvert] (https://cloudconvert.com) и [image.online-convert.com] (http://image.online-convert.com/ru)
10. [Converter mp3 to ogg] (http://audio.online-convert.com/ru/convert-to-ogg)
11. [Обрезка видео] (http://online-video-cutter.com/ru/)
12. [Видео-конвертер] (http://video.online-convert.com/ru/convert-to-mp4)
13. [JSON-валидатор] (https://jsonformatter.curiousconcept.com/)
14. [Онлайн-генератор “рыбного текста”] (http://www.blindtextgenerator.com/ru)

======

### Прочее
1. [Сервис для учета времени] (https://www.rescuetime.com/dashboard/for/the/day/of/2016-09-10)
2. [Как пользоваться сервером SMTP Google] (https://www.digitalocean.com/community/tutorials/smtp-google)
3. [Online Request Maker] (http://requestmaker.com/)
4. [Консоль разработчика Google Chrome: десять неочевидных полезностей] (https://m.habrahabr.ru/company/ruvds/blog/316132/)
5. [Типографская раскладка Ильи Бирмана] (http://ilyabirman.ru/projects/typography-layout/ )
6. [Спецсимволы] (http://www.copypastecharacter.com/all-characters)
7. [Стандарт аббревиатур языков] (http://www.iana.org/assignments/language-subtag-registry/language-subtag-registry)
8. [Берегите глаза] (http://softhelp.org.ua/?p=6120)