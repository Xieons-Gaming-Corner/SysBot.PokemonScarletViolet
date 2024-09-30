 # A custom SysBot.NET tradebot for Pokémon Scarlet/Violet
![License](https://img.shields.io/badge/License-AGPLv3-blue.svg)

This is the trade bot running on my Twitch channel at [https://twitch.tv/berichandev/](https://twitch.tv/berichandev/)
If all you want is to request Pokémon, please go there!

This is a custom sysbot, the Scarlet/Violet functionality of this bot is not created or supported by the PKHeX developers, please do not pester them!
[Read the official startup instructions](https://github.com/kwsch/SysBot.NET/wiki/Bot-Startup-Details) if you've never hosted a switch sysbot.

[Download the latest build of this bot here](https://berichan.github.io/GetNHSE?sv)

## Support Discord:

This is an archival fork of Berichan's code. The original source code came from them, which XGC forked. Berichan had previously forked it, and we're several layers deep into forks at this point. 
The official support Discord for XGC's Bots can be found at [Xieon's Gaming and Tech Corner](https://discord.gg/Xieon) 


## Support/Useful Github Repo's
Note: Unless specifically stated these REPO's and the people maintaining them are not affiliated, albeit perhaps tangentially as we're all part of the same dev community - but they don't officially assist or endorse, condone, or support any of XGC's forks, and projects. 
* [Berichan](https://github.com/Berichan)
* [Olizor](https://github.com/Olizor)
* [KwSch](https://github.com/KwSch)
* [Xieon](https://github.com/Xieon)



For support on setting up your own instance of this SysBot, feel free to join the discord! (This sysbot isn't supported by the PKHeX-Projects discord, please do not ask for help there or bother them with questions related to this bot.)

[![Discord Widget](https://discord.com/api/guilds/829181609156411463/widget.png?style=banner2)](https://discord.gg/Xieon)

## SysBot.Base:
- Base logic library to be built upon in game-specific projects.
- Contains a synchronous and asynchronous Bot connection class to interact with sys-botbase.

## SysBot.Tests:
- Unit Tests for ensuring logic behaves as intended :)

# Example Implementations

The driving force to develop this project is automated bots for Nintendo Switch Pokémon games. An example implementation is provided in this repo to demonstrate interesting tasks this framework is capable of performing. Refer to the [Wiki](https://github.com/kwsch/SysBot.NET/wiki) for more details on the supported Pokémon features.

## SysBot.Pokemon:
- Class library using SysBot.Base to contain logic related to creating & running Pokémon bots.

## SysBot.Pokemon.WinForms:
- Simple GUI Launcher for adding, starting, and stopping Pokémon bots (as described above).
- Configuration of program settings is performed in-app and is saved as a local json file.

## SysBot.Pokemon.Discord:
- Discord interface for remotely interacting with the WinForms GUI.
- Provide a discord login token and the Roles that are allowed to interact with your bots.
- Commands are provided to manage & join the distribution queue.

## SysBot.Pokemon.Twitch:
- Twitch.tv interface for remotely announcing when the distribution starts.
- Provide a Twitch login token, username, and channel for login.

## SysBot.Pokemon.YouTube:
- YouTube.com interface for remotely announcing when the distribution starts.
- Provide a YouTube login ClientID, ClientSecret, and ChannelID for login.

Uses [Discord.Net](https://github.com/discord-net/Discord.Net) , [TwitchLib](https://github.com/TwitchLib/TwitchLib) and [StreamingClientLibary](https://github.com/SaviorXTanren/StreamingClientLibrary) as a dependency via Nuget.

## Other Dependencies
Pokémon API logic is provided by [PKHeX](https://github.com/kwsch/PKHeX/), and template generation is provided by [AutoMod](https://github.com/architdate/PKHeX-Plugins/).

# License
Refer to the `License.md` for details regarding licensing.
