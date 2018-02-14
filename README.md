# MIDBL
McInDev Bukkit Library

## Development library

Gradle project with all public libraries used in development of projects (public in private) ready to generate a fat-jar.

### Libraries

This is only a gradle project with dependencies to all public projects used in development of public and private plugins. Private libraries are obviously not included.

#### Essential module

##### [JwIUtils](https://github.com/JonathanxD/JwIUtils)

My tiny utility library, used in development of my projects (almost all of them).

##### [KWCommands](https://github.com/JonathanxD/KWCommands)

My command line interface, used to register, parse and dispatch commands, with reflection and json support.

##### [KWCommandsBukkit](https://github.com/JonathanxD/KWCommandsBukkit)

Implementation of a compatible layer between KWCommands and Bukkit.

- KWCommands commands are valid Bukkit commands
- Auto-completation
- Permission Requirement
- Custom message for permission requirement
- Bridge between `CommandSender` and `Printer` with color support

##### [Config](https://github.com/JonathanxD/Config)

Key-based map-based configuration system.

#### Extra module

##### Kores for runtime ([Kores](https://github.com/JonathanxD/CodeAPI) and [Kores-BytecodeWriter](https://github.com/JonathanxD/CodeAPI-BytecodeWriter))

Code representation and runtime code generation library.

##### [KoresProxy](https://github.com/JonathanxD/CodeProxy)

Proxy generation library
