# Discord-Spotify-Bot
A Discord Spotify Bot that shows like other Discord bots, but has the feature of real Discord members with a linked spotify that allows group listening.
Should add commands to show what is playing, what is in queue (From spotify), be able to play playlists.
The commands will start with !spotify and be followed by << for previous (or start of song based on how spotify does it), >> for next. || for pause and |> for play

The account attached to the bot can be linked to an appropriately permissioned user of the discord server for a Spotify Premium experience or be left on free without any account linking. I imagine this can be implemented in a way that is similar to how Spotify allows the user to play on different devices, in this case a device will show up as 'Discord' (Or as a Discord servers' name?) since it possible a user may put this bot in multiple servers.

To save the user hastle when it comes other people potentially using his Spotify premium attached bot when the user is not present in the server, the account linking should be removed if the linked account user is not in any of the chat rooms, this should be quite easy to implement through the bots permissions to view who is and isn't in the server.
It should be easy enough to keep the current playlist and current time of the song playing when the Premium user leaves despite the above mentioned issue using the same group listening feature that spotify implemented, (theoretically, but might not be required) using another instance of the Spotify bot on the spotify side, without premium, that is listening to the Premium bot in group listening and takes over when the premium account leaves all of the chat rooms in the server and thereby disconnects the premium account.

In order to save the user the time of opening a browser window and logging into spotify every time they want a premium experience on the bot, I hope to use the same method that the Discord app uses to link to the Spotify Account for this ability although I don't know how much this will be possible.

The premium linking will likely be a late stage feature because of it's complicated nature, I might also make it a paid for feature if I create the majority of the code for this project. If I get more help building this than I put in myself then I'll make it free. We'll see.

The initial goals of the this project will simply be a Spotify instance of a free account that can play, pause, backward and forward songs and playlists on Spotify and stream the audio at 'Normal' quality (From Spotify, that is 96 Kbps) to a Discord server bot in a chat room. The bot should check the channels voice quality settings and store it's original value and then increase it to the maximum (96 Kbps) until the bot leaves, at which point it will return it to the original value.

Seeing as Discord Servers are Bit Rate limited to 96 Kbps there is actually no advantage to using Spotify premium for sound quality (Which allows from Normal - 96 Kbps, up to very High - 320 Kbps) unless the group listening feature that discord uses in the members panel is implemented in a way that the bot can use. Yet another reason to keep the Bot linking premium feature a late stage development.
