# AMFA
What is this?  A mod for ants.  In Minecraft.

Basically, create an ant farm and have ants do things for you.  Inspired by Forestry's bees and Mariculture's fish, but intended to be more approachable.

## Compiling
I don't like Eclipse, so here's a step-by-step for how to build this by hand.

Dependencies: JDK, JRE, Gradle (tested with 1.10).

### Once
1. Set the GRADLE_HOME environment variable to wherever you installed Gradle (the folder that contains bin, init.d, lib, etc.).
2. Add JDK\bin, JRE\bin, and GRADLE_HOME\bin to your PATH.

### Every time
1. Navigate to the AMFA source tree.
2. Run "gradle".
3. The result will be in the "build\libs".
