![](runelite-client/src/main/resources/net/runelite/client/ui/clfinal.png)
# cleanlite [![Travis](https://img.shields.io/travis/runelite/runelite.svg)](https://travis-ci.org/runelite/runelite) [![Discord](https://img.shields.io/discord/301497432909414422.svg)](https://discord.gg/mePCs8U)

CleanLite is a free, open source fork of Runelite, the most popular Oldschool Runescape client. The aim of CleanLite is to create a client that is as close to the vanilla client as possible, while maintaining important QOL and Performance features such as GPU rendering and increased draw distance.

If you have any questions, please join our [Discord](https://discord.gg/WwsJsNs) server.

## Project Layout

- [cache](cache/src/main/java/net/runelite/cache) - Libraries used for reading/writing cache files, as well as the data in it
- [http-api](http-api/src/main/java/net/runelite/http/api) - API for api.runelite.net
- [http-service](http-service/src/main/java/net/runelite/http/service) - Service for api.runelite.net
- [runelite-api](runelite-api/src/main/java/net/runelite/api) - RuneLite API, interfaces for accessing the client
- [runelite-client](runelite-client/src/main/java/net/runelite/client) - Game client with plugins

## Usage

Open the project in your IDE as a Maven project, build the root module and then run the RuneLite class in runelite-client.  
For more information visit the [RuneLite Wiki](https://github.com/runelite/runelite/wiki).

### License

Cleanlite is licensed under the BSD 2-clause license. See the license header in the respective file to be sure.

## Contribute and Develop

We've set up a separate document for our [contribution guidelines](https://github.com/runelite/runelite/blob/master/.github/CONTRIBUTING.md).
