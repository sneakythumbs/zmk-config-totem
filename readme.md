To flash:
1.Download firmware in actions tab

2.keep both halves powered on

3.plug in left half and press reset button twice quickly.  This will open up a directory on your computer.

4.drag and drop settings reset file onto left half

5.unplug left and plug in right side press reset twice quickly. This will open a directory on your computer.

6.drag and drop the settings reset file onto the right half

7.unplug right half and plug in left half again

8.press settings reset twice

9.drag and drop the totem left firmware file

10.uplug left and plug in right 

11.press reset twice

12.drag and drop the totem right firmware file.



## HOW TO USE

- fork this repo
- `git clone` your repo, to create a local copy on your PC (you can use the [command line](https://www.atlassian.com/git/tutorials) or [github desktop](https://desktop.github.com/))
- adjust the totem.keymap file (find all the keycodes on [the zmk docs pages](https://zmk.dev/docs/codes/))
- `git push` your repo to your fork
- on the GitHub page of your fork navigate to "Actions"
- scroll down and unzip the `firmware.zip` archive that contains the latest firmware
- connect the left half of the TOTEM to your PC, press reset twice
- the keyboard should now appear as a mass storage device
- drag'n'drop the `totem_left-seeeduino_xiao_ble-zmk.uf2` file from the archive onto the storage device
- repeat this process with the right half and the `totem_right-seeeduino_xiao_ble-zmk.uf2` file.
