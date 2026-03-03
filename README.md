# Timberborn Bad Apple

It was inevitable...

With the addition of automation - in particular HTTP Levers and Indicators - to Timberborn, we can now do vido playback with the help of some magic trickery.

I have also included the source code inside `src.zip` for anyone that wants to poke around and such.

The version on this github repo is a slightly older version with fewer optimisations, so the framerate will be lower than on the YouTube video (https://youtu.be/nNB-Dwe72mk).

## Setup

Please note, this has been built for Windows. I haven't checked it on Linux or MacOS, but I'm pretty sure it won't work for them (awww shucks)

Now, I'll be honest, the setup is going to get into the weeds a bit, as you'll need to have the .NET 10 runtime installed for this:

1) Download the files
2) Take the `Bad Apple.timber` file, create a new folder inside your Timberborn saves folder (be sure to create it in the Experimental Saves folder if you're on experimental branch), and pop the .timber file inside it.
3) Open the save, select the speaker on the bottom left side of the display, and open the sounds folder. Put the audio file included in this repository in there and set the speaker to play that sound. That will complete the Timberborn side of the setup.
4) If you do not have it installed already, install the [.NET 10 runtime](https://dotnet.microsoft.com/en-us/download/dotnet/10.0).
5) Extract the Server.zip archive to whatever file location your heart desires.
6) When you're in the Bad Apple save game, ensure that the game is playing (not paused), turn on the API (select one of the HTTP Levers behind the display to see the option), and then run the TimberNet.Demo.exe file - this will launch the server, which should hook into the game's API
7) Enjoy!
