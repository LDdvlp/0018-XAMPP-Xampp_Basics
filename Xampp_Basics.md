|*Doc. #*|*Rédacteur*|*Création*|*Mise à jour*|
|:---:|:---:|---:|:---|
|***0018***|*Loïc Drouet*|_Jeudi 06 juillet 2023_|_Mercredi 18 octobre 2023_|


# XAMPP Basics


<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [XAMPP Basics](#xampp-basics)
  - [1. Think to back up `php.ini`](#1-think-to-back-up-phpini)
  - [2. How to move the document root (`htdocs`) ?](#2-how-to-move-the-document-root-htdocs-)
  - [3. How to move the databases (`datadir`) ?](#3-how-to-move-the-databases-datadir-)

<!-- /code_chunk_output -->



## 1. Think to back up `php.ini`

1. Open `C:\xampp\php`
2. Copy `php.ini` file to your back up location

## 2. How to move the document root (`htdocs`) ?

1. Open `C:\xampp\apache\conf\httpd.conf`
2. Modify the path here :
    ```
    DocumentRoot "C:/xampp/htdocs"
    <Directory "C:/xampp/htdocs">
    ```
3. Copy `htdocs` folder content to the new location

## 3. How to move the databases (`datadir`) ?

1. Open `C:\xampp\mysql\bin\my.ini`
2. Modify the path here :
    ```
   datadir="C:/xampp/mysql/data"
    ```
3. Copy `data` folder content to the new location
