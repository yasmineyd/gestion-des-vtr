========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "LocationV.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
Explication:
1. telecharger le fichier RAR
2. implimenter la base de donnees avec les instances 
3. cliquer sur l'exicutable 
4.inserer l'adresse et le mot de passe enregistrer dans la base de donnees
5.apres l'authentification la page d'accueil s'affichera 
6.vous cliquer sur n'importe quel etiquette sur le menu [
par ex: clien: pour gerer les client ajout supprission modification et meme consultation de la liste des clients ]
pour modifier vous devez selectionner un tuple sur la table et faire les modifications puis cliquer sur le botton modifier pour aporte des modifications.
pour la supprission vous devez juste a cliquer sur un tuple puis le botton supprimer.
et cela pour toute entités
si vous avez finis avec l'utilisation de l'appllication vous allez juste a cliquer sur le botton deconnecter puis sur oui .
