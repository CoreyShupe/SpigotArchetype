# SpigotArchetype
A simple spigot based archetype for quick starting spigot plugins.

## How to use
Steps to use this archetype: <br />
<br />
First we have to install this archetype into our maven .m2 <br />
To do this we can clone the repo then simply run install. <br />
Command line example:
```
git clone https://github.com/CoreyShupe/SpigotArchetype.git
cd SpigotArchetype
mvn install
```
Next it depends on your IDE <br />
Most IDEs when creating maven projects let you use a custom archetpye. <br />
When asked for the group-id, artifact-id, and version you can input these: <br />
```
group-id: me.fixed
artifact-id: spigot-archetype
version: 0.0.4
```