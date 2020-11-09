# vesta
Vesta is a ro(bot) for Vitality PS. It aims at creating a diverse amount of bot types as a fun project.

Usage
Run Vitality.jar. This jar file has been altered to run with the -javaagent parameter but other than that is the official Vitality launcher. Check the Gradle build file to gain a bit more insight on how attachment of the agent works.

This is an updated version of https://github.com/BJWielink/vesta, which is the original version with open source. I fixed the zulrah bot and changed the command to ::HOME (case sensitive), as it would be pretty easy to catch botters by simply searching for the original ::zulrah command in the client. The ::HOME approach actually teleports you home, so it's more difficult to distinguish from genuine gameplay; also, I was too lazy to create an interface that allows you to just select the script to run without inputting a chat command.
