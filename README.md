# Brukonoid 2010
Sample pure java game, with use of thread and manage of frame per second vs tick per second.
Loader of midi for sound, wav for effects  and various sprite.

Main file: Brukonoid\src\main\java\it\reef\ark\main

Audio resources: Brukonoid\src\main\java\it\reef\ark\resources
Audio manager: Brukonoid\src\main\java\it\reef\ark\manager\audio

Sprite and image manager: Brukonoid\src\main\java\it\reef\ark\manager\image

Action interface: Brukonoid\src\main\java\it\reef\ark\element\action
Actor: Brukonoid\src\main\java\it\reef\ark\element\actor

Txt file to manage level: Brukonoid\src\main\java\it\reef\ark\resources\level
The schema is simple txt file:
Example:
Txt file
 ![TXTLevel10File](https://github.com/xreef/Brukonoid/blob/master/resources/level10file.png)
Schema
 ![TXTLevel10File](https://github.com/xreef/Brukonoid/blob/master/resources/level10.png)
 
 
It's made in the last 2010 but very usefully to understand games logic.  

Eclipse project

Tested with java 1.5+ and maven 

Command to start:
mvn install
Than start with Run As and select Ark class.

Some screen

![Screen](https://github.com/xreef/Brukonoid/blob/master/resources/screen01.png)

![Screen](https://github.com/xreef/Brukonoid/blob/master/resources/screen02.png)

![Screen](https://github.com/xreef/Brukonoid/blob/master/resources/screen03.png)