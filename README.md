# Redrix
Redrix is a free Destiny 2 crucible companion app available for iOS and Android that helps you track and improve you PvP skills.

You can find more information at [redrix.io](http://redrix.io)

## Features

Features include:
*  Current crucible map and game type displayed as you are loading into a match.
*  Combined and individual stats for recent games, including K/D, efficiency, and opponents defeated.
*  Current valor and glory level.
*  Current valor and glory streaks (accurate across characters and playlists).
*  Detailed graphs showing trends over recent games.
*  Ability to easily switch between characters and players.
*  Support for destiny accounts on PC, Xbox and Playstation.

## Releases

[Release Notes](RELEASE.md)


## Usage

Using the app is simple. Install the app, enter your gamer tag and select your platform. Once your information is loaded, you can change characters and players by tapping the menu on the top right of the screen.

In order to see your current crucible activity, click the refresh icon at the top as you are loading into your game.

You can view historical graphs for your stats by clicking the graph icon on the left of the summary stats row.

## FAQ

### General

#### How much does Redrix cost?

Redrix is free.

#### Where can I report a bug or log feature requests?

You can submit feature requests, or log bugs [here](https://github.com/redrixapp/support/issues).


#### Does Redrix support crossplay accounts?

Yes. Just log in with your primary account.

#### What format do you I use to input my gamertag for PC?

For PC you must enter you Steam 64 ID, which you can find in game by typing the "/id" command. You can find more information at [redrix.io/steam](https://redrix.io/steam)

#### Which stats are displayed for my match history and what do they mean?

Redrix currently displays the following stats in your match history:

*  **K+A** : Kills + Assists : This is the same as opponents defeated displayed within Destiny 2.
*  **KA / D** : Kills + Assists / Deaths. This is the efficiency value displayed within Destiny 2.
*  **K / D** : Kills / Deaths. This is your kills to deaths ratio, not including assists.

#### Why doesn't my streak match up with my game history?

Streaks are calculated across characters, glory / valor and resets, and thus may not always reflect your current win streak in your activity feed. However, the streaks presented are from Bungie, and accurate.

### Errors

#### I got an "Error communicating with Destiny server" error, what should I do?

This error occurs when the app cannot communicate with the Destiny 2 API server, usually caused by lack of network connection. Check that you have internet connectivity and try again.

#### I got an "Unable to sign in. Check your gamer tag and try again." error, what should I do?

This error occurs when your gamertag cannot be found for the specified platform. Make sure that you:

* Select the correct platform
* Use the correct case for your gamer tag (tags are case sensitive)
* If on PC, make sure you are entering your Steam 64 ID and not your nickname.

#### I got an "Your Bungie.net privacy settings are too restrictive." error, what should I do?

Redrix requires that your privacy settings for your Destiny 2 / Bungie account are set to be public. You can update your privacy settings by logging into your Bungie account at [bungie.net](https://www.bungie.net), and navigating to Settings > Privacy.

Redrix requires the following two items to be checked:

*  Show my Destiny game Activity Feed on Bungie.net
*  Show my Progression (what I've completed in Destiny, and my current status)


#### I got an "No characters found for account." error, what should I do?

This error occurs if you have created a bungie Id, but have yet to create any characters in Destiny 2.

#### I got an "Destiny API is currently down for maintenance." error, what should I do?

This error means that the Destiny 2 API is down for maintenance, usually occurring during weekly resets. Simply wait a few minutes until the API is available.

#### I got an "An unknown error has occurred" error, what should I do?

You may get this error is something unexpected occurs, usually a temporary issue with the Destiny 2 API. Often the issue will go away on its own, or after an app restart. If it does not, please [log an issue](https://github.com/mikechambers/redrix/issues), including your gamertag and platform.

#### I got a "Fatal error. Please restart app." error, what should I do?

In general, means that something went wrong that prevents the app from running. If you hit this error, please [log an issue](https://github.com/redrixapp/support/issues).

Potential work arounds include:

*  Restarting the app (make sure to completely close it)
*  Deleting and reinstalling the app
*  Ensure you are not out of storage space on your device
