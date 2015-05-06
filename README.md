Simple-Tank-Game
===============================
Simple-Tank-Game (a.k.a. Ex8) was an open-ended assignment from our Games Programming class using Java and OpenGL. 

Navigation
-----------
[Simple-Tank-Game](#tsimple-tank-game) |
[Abstract](#abstract) |
[Screenshot](#screenshot) |
[Team](#team) |
[Requirements](#requirements) |
[Executables](#executables) |
[Folder Structure](#folder-structure) |
[Configuration](#configuration) |
[Building the program](#building-the-program) |
[Running the Program](#running-the-program) |
[Contact](#contact) |
[Licenses](#licenses) |
[TODO](#todo)

Abstract
--------
This game was a project for a CS390A - Game Programming @ MSU Denver, taught by Professor Jerry Shultz. We were to follow loose guidelines, and create a game using only Java and OpenGL. This program is built, and deployed using Gradle. It is written in Java using Java OpenGL bindings provided by Light Weight Java Gaming Library (LWJGL). 

Screenshot
----------
![Picture](http://rabbitfighter.net/wp-content/uploads/2015/04/Simple-Tank-Game.png)

Team
----------------
<ul>
<li>Joshua Michael Waggoner</li>
<li>Dylan Otto Krider</li>
</ul>

Requirements
------------
<ul>
<li> Java vers 1.7+ </l1>
<li> Gradle vers 2.0+ (for installation help go to <a href="https://gradle.org/">Gradle's home page</a>)</li>
</ul>

Executables
-----------
Included in the folder <code>executables</code> are the following files:
<ul>
<li>Simple-Tank-Game-Linux.sh that will run on all linux platforms by:
    <ol>
    <li>making it execuatble using <code>chmod +x Simple-Tank-Game-Linux.sh</li></li>
    <li>Then run it using <code>./Simple-Tank-Game-Linux.sh</code></li>
    </ol>
<li>Simple-Tank-Game-Runnable.jar that will run on any platform with java by typing <code>java -jar Simple-Tank-Game-Runnable.jar</code>.</li>
<li>Simple-Tank-Game-Windows.exe for Windows folks that will work witth a doublee-click.</li>
</ul>

Configuration
-------------
This program requires LWJGL vers 2.9.3 (Light Weight Java Gaming Library) library as well as natives for Windows, Linux, and OSX that come with it. As per our Gradle build program, these files must be in the correct folders in the project structure or the program will fail. Fortunately, all you need to do is clone this repository to get the project in the proper form.

Folder Structure
----------------
<pre>
.
├── build.gradle
├── libs
│   ├── jar
│   │   └── lwjgl.jar
│   └── natives
│       ├── linux
│       │   ├── libjinput-linux64.so
│       │   ├── libjinput-linux.so
│       │   ├── liblwjgl64.so
│       │   ├── liblwjgl.so
│       │   ├── libopenal64.so
│       │   └── libopenal.so
│       ├── macosx
│       │   ├── libjinput-osx.dylib
│       │   ├── liblwjgl.dylib
│       │   └── openal.dylib
│       └── windows
│           ├── jinput-dx8_64.dll
│           ├── jinput-dx8.dll
│           ├── jinput-raw_64.dll
│           ├── jinput-raw.dll
│           ├── lwjgl64.dll
│           ├── lwjgl.dll
│           ├── OpenAL32.dll
│           └── OpenAL64.dll
├── README.md
└── src
    └── main
        └── java
            └── net
                └── rabbitfighter
                    └── game
                        ├── Basic.java
                        ├── Box.java
                        ├── Ex8.java
                        └── Triple.java

12 directories, 24 files

</pre>

The folder structure should look like this before building.

Building the Program
--------------------
<ol>
<li>Navigate into the project directory. From the project directory, run <code>gradle build</code>.</li>
</ol>

Running the Program
-------------------
<ol>
<li>Run the program by typing <code>gradle runJar</code> in the root project directory</li>
<li>Enjoy!</li>
</ol>

Contact
-------
<table>
  <tr>
    <th>Name</th>
    <th>Email</th>		
    <th>Twitter</th>
  </tr>
  <tr>
    <td>Joshua Michael Waggoner</td>
    <td>rabbitfighter@cryptolab</td>		
    <td><a href="https://twitter.com/rabbitfighter81">@rabbitfighter81</a></td>
  </tr>
  <tr>
    <td>Dylan Otto Krider</td>
    <td>dkrider@comcast.net</td>		
    <td><a href="https://twitter.com/dokrider">@dokrider</a></td>
  </tr>
</table>

Licences
---------
<ul>
<li>LWJGL sources and binaries: Copyright (c) 2002-2007 Lightweight Java Game Library Project</li>
<li>All other: CCO Licence (See LICENCE-CCO)</li>
</ul>

TODO
----
This game is a work in progress. We hope you have fun, learn something, or at least kill some time. We will add updates, and clean up code as time allows. For now it is working though. :)
