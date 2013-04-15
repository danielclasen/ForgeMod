ForgeMod
========

Maven parent POM for building mods with [Minecraft Forge](http://minecraftforge.net/) using [SpecialSourceMP](https://github.com/agaricusb/SpecialSourceMP).

Add to your parent pom.xml, for example (Minecraft 1.5; [1.4.7](https://github.com/agaricusb/ForgeMod/tree/MC147) is also supported):

      <parent>
        <groupId>net.md-5</groupId>
        <artifactId>ForgeMod</artifactId>
        <version>1.5-7.7.1-SNAPSHOT</version>
      </parent>

then run:

    mvn initialize -P -built
    mvn package

The mod will be compiled and reobfuscated in `target/`.

For more information see the wiki: https://github.com/agaricusb/ForgeMod/wiki

