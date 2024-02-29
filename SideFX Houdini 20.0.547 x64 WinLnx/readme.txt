The method was tested with no old keys from previous versions of Houdini.
You can delete them manually in the C:Windows/keys folder, you can delete all the files there, or delete the "licenses" file at least, or edit it by deleting all the keys inside.
You can try not deleting the keys.

You can also try not to update the License Server if you already have a previous version of Houdini installed, but in any case you need to replace sesinetd.exe, which is described in the instructions.

1) Install Houdini 20 manually or with Houdini Launcher, install the License Server from Houdini 20 as well.

2) After the installation is complete, go to License Administrator - File - License Tools Services..., stop Sesinetd, don't close the window, it will come in handy later.

3) Replace sesinetd.exe in the C:\Program Files\Side Effects Software\License Server folder with sesinetd.exe from the crack. 

4)Start the Sesinetd service in the License Administrator window, restart the License Administrator.

5)In the Server Information tab find Server Name (in brackets) and Server Code. Open the keygen for Houdini 20 and enter them in the fields with the same names and generate keys.

6)In License Administrator go to File - Import Licenses..., click Manual Install.

7)In the Keys fields enter the keys from the License Keys window of the keygen, first the SERVER key, and then in any order, if necessary, repeat the procedure to enter the remaining keys.

If you have done everything correctly and the keys are still red, then go to License Administrator - File - License Tools Services... again.
Restart Sesinetd, then restart License Administrator and the keys should be connected.

To prevent keys from being lost in future Houdini updates, uncheck the License Server installation option.
If you installed it by accident and everything is lost, try to replace sesinetd.exe again, stopping the Sesinetd service beforehand and starting it after replacing the file, it should help.

You can also install older versions of Houdini, they should work with the keys of version 20, the main thing is not to install License Server.
If you need Karma in Houdini versions lower than version 20, you need to install the Karma Renderer key, and if you need Mantra in Houdini 20, you need the Generic Render key.
