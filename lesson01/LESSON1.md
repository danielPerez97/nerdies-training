### Checking your Computer
Before any of the necessary software is downloaded, we need to make sure you have an appropriate computer that supports 
our version of Minecraft and Forge. A good rule of thumb is start off with a computer that can run ordinary Minecraft pretty well.

Forge runs on Windows(7 and greater), and on Mac(10.8.3 and greater). However, all operating systems must be 64-bit. 
Chromebooks are not supported.

### Setting up your tools 
#### Java
We will be using Kotlin as our programming language, but Kotlin still generates Java bytecode when compiled. This means 
we will need an appropriate Java JDK. The version of Java we need is the latest version of [1.8](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html).
Scroll down on that link and select either Windows x64 or macOS x64 depending on your operating system. You may need to
create an account to install the JDK.

#### IntelliJ
IntelliJ is the IDE we will be using for programming. It handles a lot of the heavy lifting for plugins and dependencies we will need for
Forge mod making.

We will be using the community edition since it is free, but it still includes all of the functionality we will need to use Forge.
The community edition can be downloaded [here](https://www.jetbrains.com/idea/download/).

Perform the first time setup for IntelliJ and allow it to load into the main coding environment.

#### Loading Forge for the first time
One of the more complicated parts of the course was the first time setup after installing IntelliJ and Java. Loading a
project with the Forge plugins for the first time can be a long process depending on the speed of the computer. First start
up IntelliJ and wait for it to load into the coding environment. At the top left go to File->New->Project From Version Control. 
A popup box will appear. Make sure under version control that Git is selected. In the URL portion paste this link
https://github.com/danielPerez97/medieval-gear.git. Hit clone at the bottom of the popup box.

The project will start downloading necessary maven and gradle plugins. Wait until the downloads stop before proceeding. Once 
the downloads are finished, we need to make sure IntelliJ uses Java 8. To do this go to File->Project Structure and at the drop
down box under Project SDk select 1.8. 

Now we can continue setting up Forge. We need to run a Gradle command called 'setupDecompWorkspace'. This will acquire additional dependcies
and download a custom Minecraft client we will use to test our mods. To run this command click on the small elephant icon with the word gradle 
underneath it. A new window should appear on the right side of the screen. On that new window near the top click the small elephant icon. This opens
up a run box in the center of the screen to run gradle commands. Enter setupDecompWorkspace and hit enter. This section of the setup is the longest part since
it will be downloaded many files and running heavy computation. Slower computer can sometimes take over 20 minutes to complete setupDecompWorkspace. 

#### Minecraft Plugin
