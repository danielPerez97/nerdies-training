# Learning Kotlin

Think to how you and I communicate with each other. We both speak English to convey
questions, thoughts, and commands. We have English in common so we are able to have
conversations. Programming is kind of of like that, only it is mostly commands you will be
"speaking" with the computer. 

- "Ok, what language does the computer speak?". 

That depends on what you need it to do. For websites, you may need to "speak" JavaScript.
For iOS apps, you may need to "speak" Swift, which is their programming language.
For our purposes, we need to speak Kotlin, so that is what we will focus on for this
lesson, which will enable us to start adding items and blocks and more to Minecraft later.

It is ok to feel lost, that is normal and your mentors are here to try and help you understand.
When you think you understand, have fun with it, tinker around and make goofy things happen, 
programmers do it all the time for laughs, and you can too.

## Variables

## Math

## Functions

## Loops

## Minecraft Modding History
To cap off our lesson on Kotlin, let's take a step back and see how we got to Minecraft modding.

Minecraft modding has quite a rich history that predates some of your guys's age! Minecraft itself first came out in a very
early, early form called "Classic" on May 17, 2009. At this point, Minecraft was a side project, it was 
never meant to become the phenomenon that it is now. Players at the time took interest and what followed
was a very dedicated community to the game with interest growing quickly. deadmau5, a world-renowned electronic 
music producer also helped the game's popularity by streaming it, creating a server for fans to play on, 
and generally giving the game a lot more exposure. 

Over a year after it's Classic release, the Alpha version came out on June 28th, 2010. Sales increased and the
creator was able to work on Minecraft fulltime, ramping up it's development and creating Mojang. In December
2010, Mojang hired Jens Bergensten, more widely known as Jeb. Jeb was exceptional, for he had been
programming since he was 11 years old(some of you are already ahead of him now!) and was pivotal for Minecraft's
development then and now. Before working for Mojang, Jeb was already modding Minecraft with a famous server
mod called Bukkit. Bukkit allowed server admins to have more fine control over their servers, making their job
easier in the end. The Bukkit team included Jeb and Dinnerbone, both developers for Minecraft now.

During this time, the community was making mods that were an absolute joy to play with. Very rare was it
you had a true sandbox game where you could do whatever you wanted and have a blast, rarer even that a game
gave you the modding potential Minecraft had. I remember seeing a tornado mod which I haven't seen since. 
There was a problem however.

You and I are used to playing with modpacks, which is a privilege early Minecraft did not have. Before, 
it was one mod and that was all you got. Naturally, players wanted to use multiple mods together, 
which was not possible yet. Thanks to the volunteer efforts of a few exceptional community members, ModLoader
came to solve this problem, which provided modders with a set of tools that would allow them to build mods and 
make sure players could use multiple mods. ModLoader eventually became ForgeModLoader, which we now know as just
Forge. This is the tool we will be using for this camp. It's a tool we are very fortunate to have per the result
of people spending their personal time on it just for the sake of enabling people to have fun. 

Here are a few names pivotal in Minecraft modding history:

Risugami
Eloraam
SpaceToad
Flowerchild
LexManos
cpw
tterag
Dinnerbone
Jeb


### Advanced Topics(For the curious)
- "Why Kotlin?"

Java is an older language that first came out in 1996. That's before even I was born! With it's age,
we as programmers have to deal with some of it's older baggage. Kotlin is usually easier to pick up 
and allows you to go a bit faster than you would with Java. We felt it was a better language to work
with for an introduction to programming and would allow us to write mods faster without overwhelming
as much as Java would.

- "What else can Kotlin do?"

Anything Java can do! Java runs a lot of server's, which are computers that serve you data anytime 
you use a website, or play a videogame online. Java also allows you to create Android apps, so by
extension, Kotlin does too!

- "Doesn't Minecraft need Java to make mods?"

YES, at least until recently. To hash this out, some background might help.
Java IS a progarmming language, just like Kotlin is a programming language,
it's whats under the hood that enables us to use Java. Java uses a 
**Virtual Machine**(a virtual computer within a computer!) to run it's programs,
including Minecraft! Java needs to generate special code for this virtual machine
called **bytecode**. Once the virtual machine has bytecode(which is our code, but translated,
i.e. think English to Spanish) it can run that code on itself and then our own computer.
Kotlin is doing the same thing. It generates bytecode for the virtual machine, and because
Minecraft runs on that virtual machine, we are allowed to use Kotlin.