|*Doc. #*|*Rédacteur*|*Création*|*Mise à jour*|
|:---:|:---:|---:|:---|
|***0018***|*Loïc Drouet*|_Jeudi 06 juillet 2023_|_Vendredi 07 juillet 2023_|

# XAMPP Basics

## Document root and databases

### 1. Move the document root (`htdocs`)

1. Open `C:\xampp\apache\conf\httpd.conf`
2. Modify the path here :
    ```
    DocumentRoot "C:/xampp/htdocs"
    <Directory "C:/xampp/htdocs">
    ```
3. Copy `htdocs` folder content to the new location

### 2. Move the databases (`datadir`) 

1. Open `C:\xampp\mysql\bin\my.ini`
2. Modify the path here :
    ```
   datadir="C:/xampp/mysql/data"
    ```
3. Copy `data` folder content to the new location

