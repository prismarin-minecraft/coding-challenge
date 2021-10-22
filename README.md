# Java coding challenge

The project should be written in Java 16 and a dependency manager (Maven, Gradle) of your choice.

The following rules should be followed in the plugin.
 - Java convention
 - Good class naming

## Challenge

The main content of this plugin is to create a blacklist.
This means that players can not write registered words in the chat.
The plugin does not need to include an advanced registration system, i.e. no commands.

Create a simple chat listener with a static list of words.

The following words should be blocked:
  - fuck
  - idiot
  - shit

Depending on how the algorithm will look like at the end the blacklist should recognize the following evasions:
  - i d i o t
  - i-d-i-o-t

That means whitespaces and special characters should be recognized by the system.


