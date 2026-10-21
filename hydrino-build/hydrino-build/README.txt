BUILD (needs internet + Java 21):
  gradle build        -> build/libs/hydrino-1.0.0.jar
or push this folder to a GitHub repo; Actions builds the jar (Actions tab > Artifacts).
INSTALL: put hydrino-1.0.0.jar in .minecraft/mods next to Meteor Client (1.21.11).
If build fails on versions, copy the version numbers from meteor-addon-template's gradle.properties.
