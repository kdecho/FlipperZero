# Upgrade or Downgrade your Flipper level (Official firmware)!

## NOTE: To fix issue with recent firmware changes, file should start with a period `.`

Github doesn't like files that start with a period so please make sure to rename it after download.

If your flipper level is moving too slow for you, there are ways you can fix that! Are you are the tinkering kind? See [DroomOne's](https://github.com/DroomOne/FlipperScripts) Python script. (All the files below were made with this script. I've notated the numbers used as _DO#_ later.)

If you would rather just "git'r'done" then grab one of the following files depending on your need.

`dolphin.state.ZERO` - Starting from scratch, just a n00b... _(DO#: 0)_<br>
`dolphin.state.TOP1` - Next action you do upgrades to LVL 2 _(DO#: 734)_<br>
`dolphin.state.LVL2a` - Instant LVL 2 animation on reboot _(DO#: 735)_<br>
`dolphin.state.TOP2` - Next action you do upgrades to LVL 3 _(DO#: 2939)_<br>
`dolphin.state.LVL3a` - Instant LVL 3 animation on reboot _(DO#: 2940)_<br>
`dolphin.state.FIN3` - You're the king, nothing left... _(DO#: 2941 or greater)_

Now that you have downloaded the dolphin.state file you want to a location you know, RENAME IT to just `.dolphin.state`<br>
Next, open up qFlipper and head to the file browser section to transfer your new file:

![File_browser](https://user-images.githubusercontent.com/57457139/169634442-38acca0a-94e0-4038-aa54-dd33ebdffa29.png)

You should see the internal and external (SD) there - double-click on `Internal Flash`:

![Int_Flash](https://user-images.githubusercontent.com/57457139/169634459-a9e87dac-d180-4e09-b047-86dc7cad49f9.png)

There's not a lot here, but the important file is! Enable hidden files and you should see a `.dolphin.state` file already present:

![Dolphin_State](https://user-images.githubusercontent.com/57457139/181995552-43311409-227a-4e70-a736-b5dcff6df3ac.png)

Right-click on it and select "Rename..."

![Rename_File](https://user-images.githubusercontent.com/57457139/181995473-8a41b499-7e14-40d6-b770-5428f5e76dd4.png)

Give it a name that you'll know what it is still and can go back. I picked `.dolphin.state.mine`:

![Renamed_File](https://user-images.githubusercontent.com/57457139/181995480-8c88a714-7b6f-4c90-8244-c1a5b2149ea6.png)

Great! Now drag and drop the `.dolphin.state` file you downloaded from this repo right into the same spot:

![Copy_New_File](https://user-images.githubusercontent.com/57457139/181995490-882fac5d-01f8-4174-9ac7-eef23e556058.png)

That's it! Now [restart Flipper](https://docs.flipperzero.one/basics/reboot) and enjoy your new level!

![L337_Level](https://user-images.githubusercontent.com/57457139/169634673-889e823f-4757-4911-ac34-5dd962e7f907.png)

If you find yourself longing for your original friend as it was, it's easy to go back. Repeat the process above, but now DELETE<br>
the `.dolphin.state` file, then rename your `.dolphin.state.mine` (or whatever you picked) back to `.dolphin.state`.<br>
Finally, retart Flipper again and you should be back to where you started! (This can be done as many times as you like.)
