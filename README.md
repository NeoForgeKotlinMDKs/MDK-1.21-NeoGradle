# Kotlin MDK

This is a fork of NeoForge's MDK that is configured to use Kotlin. The following modifications have been made:
- Port existing Java code to Kotlin
- Adjust necessary resources for running on Kotlin (i.e. depend on KFF)
- Added an example Mixin to emphasize that Mixins should only be written in Java

> [!NOTE]
> The Kotlin experience is not very good in Eclipse. The original MDK may be made to work with Eclipse as well,
> but if you want to use Kotlin, the best choice is IntelliJ IDEA with the Minecraft Development Plugin.

---

Original README:

Installation information
=======

This template repository can be directly cloned to get you started with a new
mod. Simply create a new repository cloned from this one, by following the
instructions at [github](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).

Once you have your clone, simply open the repository in the IDE of your choice. The usual recommendation for an IDE is either IntelliJ IDEA or Eclipse.

> **Note**: For Eclipse, use tasks in `Launch Group` instead of ones founds in `Java Application`. A preparation task must run before launching the game. NeoGradle uses launch groups to do these subsequently.

If at any point you are missing libraries in your IDE, or you've run into problems you can
run `gradlew --refresh-dependencies` to refresh the local cache. `gradlew clean` to reset everything 
{this does not affect your code} and then start the process again.

Mapping Names:
============
By default, the MDK is configured to use the official mapping names from Mojang for methods and fields 
in the Minecraft codebase. These names are covered by a specific license. All modders should be aware of this
license. For the latest license text, refer to the mapping file itself, or the reference copy here:
https://github.com/NeoForged/NeoForm/blob/main/Mojang.md

Additional Resources: 
==========
Community Documentation: https://docs.neoforged.net/  
NeoForged Discord: https://discord.neoforged.net/
