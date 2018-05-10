# Первые шаги по освоению html 
## Инструкция по запуску проекта 
1. Скачиваем Vagrant и VirtualBox
2. Клонируем репозиторий в удобную папку с помощью команды

        git@github.com:Gosha5513/html-first-staps.git
1. Клонируем в папку  "cd html-first-staps"
1. Запускаем виртуальную машину      
1. Заходим в командную строку проекта по SSH протоколу   
## Инструкция по базовой работе с git
1.    "git add" - добавляет файл в индекс
1.    "git commit" - делает коммит файлов в индексе 
1.    "git push" - залить изменения
1.    "git pull" - принять изменения с локального репозитория 
## Работа с HTML 
### Подключение скриптов и стилей 
 *Скрипты можно подключить тегом `<script>`
 
         <script type="text/javascript">
             var j =10;
             console.log(j);
         </script>
         <script src="index.js" type="text/javascript"></script>
     
 *Стили создаются с помощью тега `<style>`
     
         body{
             background-color: red;
         }
         
### Подключение файлов
 *Чтоыб подключить файл со скриптом необходимо прописать `<script>` с атребутом `scr`
         
         <script src="index.js" type="text/javascript"></script>     
         
 *Для подключения файла со стилями прописываем тег `<link>` с атребутами `rel="stylesheet" href="index.css"`
