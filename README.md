# Pinocchio

Welcome to Pinocchio, the all in one SC games protocol understanding and exploitation. Pinocchio is an open source project supported by the community.

## BIG WIP
Pinocchio is actually a big WIP project. It's built with vanilla java, with all the boilerplates to allow an easy understanding of the code in the hope to have more people involved.

# What's working:

* Clash Royale patcher
* Clash of Clans patcher
* Boom Beach patcher
* Clash Royale proxy
* Clash of Clans proxy
* Boom Beach proxy
* Protocol definitions and parser

# TODO
* Port all the messages from the know ones to Pinocchio java mapper
* Make proxy and patchers for bb and hh
* Make utils to rebuild messages

# How to start
```java -jar Pinocchio.jar```

# Commands
* help 

Show help

* patch [cr - coc - bb - hh - bs] [host] [key optional]

Patchers. HayDay and BrawlStars are TODO. Extract libg from android device through adb, patch it (ONLY ARM) and upload it back.

* proxy [cr - coc - bb - hh - bs]

Proxies. HayDay and BrawlStars are TODO. 