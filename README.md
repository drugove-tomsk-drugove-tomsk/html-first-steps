# Первые шаги по освоению html
## Инструкция по запуску проекта
1. Скачиваем Vagrant & Virual box
1. Клонируем репозиторий в удобную нам папку с помощью команды
        
        git clone git@github.com:drugove-tomsk-drugove-tomsk/html-first-steps.git
        
1. Переходим в папку **html-first-steps** 'cd html-first-steps'
1. Запускаем виртуальную машину: 'vagrant up'
1. Заходим в коммандную строку виртуальной машины  по SSH-протоколу: 'vagrant ssh'
## Инструкция по базовой работе с Git
1. 'git add' добавляет файл в индекс
1. 'git commit' создает коммит из всех файлов индекса
1. 'git commit -m "Comment"'позволяет добавить комментарий 
1. 'git push' залить в удаленный репозиторий
1. 'git pull' принять из удаленного репозитолрия
1. 'git clone'

## Работа HTML
### Подключение скриптов и стилей

* скрипты можно подключить с помощью тега `<script>`:

        <script type="text/javascript">
            //Объявлем пременную j и присваиваем ей значение 10
            var j = 10;
            console.log(j);
        </script>
        <script src="index.js" type="text/javascript"></script>
                 
 * стили создаются с помощью тега `<style>`:
 
         <style>
                 h1,h2,h3,h4 {
                     text-align: center;
                     background: red;
                 }
                 .class{
                     color: #ba0;
                 }
         
             </style>
             
 ### Подключение файлов
 
 * Чтобы подключить файл со скриптом необходимо прописать:
 
          1. Стили:
          `<link rel="stylesheet" href="index.css">`
       или
          2. Скрипты:
          `<script src="index.js" type="text/javascript"></script>`
          
 ### Рисуем таблицы
          <table style="border: 1px solid black;">
              <thead>
              <tr><!--Строка-->
                  <td>Number</td><!--Ячейка-->
                  <td>Name</td>
                  <td>Phone</td>
                  <td>E-mail</td>
              </tr>
              </thead>
              <tbody>
              <tr><!--Строка-->
                  <td>1</td><!--Ячейка-->
                  <td>Женя</td>
                  <td>***67</td>
                  <td>E-mail</td>
              </tr>
              <tr><!--Строка-->
                  <td>2</td><!--Ячейка-->
                  <td>Никита</td>
                  <td>***43</td>
                  <td>E-mail</td>
              </tr>
              <tr><!--Строка-->
                  <td>3</td><!--Ячейка-->
                  <td>Адриан</td>
                  <td>-</td>
                  <td>E-mail</td>
              </tr>
              <tr><!--Строка-->
                  <td>4</td><!--Ячейка-->
                  <td>-</td>
                  <td>-</td>
                  <td>-</td>
              </tr>
              </tbody>
              <tfoot>
          
              </tfoot> 