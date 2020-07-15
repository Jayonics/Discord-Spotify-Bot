# Discord-Spotify-Bot
A Discord Spotify Bot that shows like other Discord bots, but has the feature of real Discord members with a linked spotify that allows group listening.
Should add commands to show what is playing, what is in queue (From spotify), be able to play playlists.
The commands will start with !spotify and be followed by << for previous (or start of song based on how spotify does it), >> for next. || for pause and |> for play

The account attached to the bot can be linked to an appropriately permissioned user of the discord server for a Spotify Premium experience or be left on free without any account linking. I imagine this can be implemented in a way that is similar to how Spotify allows the user to play on different devices, in this case a device will show up as 'Discord' (Or as a Discord servers' name?) since it possible a user may put this bot in multiple servers.

To save the user hastle when it comes other people potentially using his Spotify premium attached bot when the user is not present in the server, the account linking should be removed if the linked account user is not in any of the chat rooms, this should be quite easy to implement through the bots permissions.

In order to save the user the time of opening a browser window and logging into spotify every time they want a premium experience on the bot, I hope to use the same method that the Discord app uses to link to the Spotify Account for this ability although I don't know how much this will be possible.
