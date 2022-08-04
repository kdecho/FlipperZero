# Adding additional frequencies (TX/RX)

## Note: You must be on the latest release!

Some changes I made to the available frequency settings (including unlocking them all). The file is found here:

![Sub-Ghz_Changes](https://user-images.githubusercontent.com/57457139/174948988-f6955976-2318-4e3e-b658-93f0465bb22e.png)

Officially supported frequencies: 300-348 MHz, 387-464 MHz, and 779-928 MHz (from [CC1101 chip docs](https://www.ti.com/product/CC1101))<br>
Unofficially supported frequencies: 281-361 MHz, 378-481 MHz, and 749-962 MHz (from [YARD Stick One](https://greatscottgadgets.com/yardstickone/) CC1111 docs)

Official & Unleashed currently do not allow anything outside of the officially supported CC1101 specs.<br>
RogueMaster allows unofficially supported frequencies with the `extend_range` file.

**NOTE: Going outside the supported frequencies may DAMAGE YOUR FLIPPER AMP.<br>
Please understand what you're doing if trying to break out of official frequencies.**

You'll need to edit some code and recompile if you want to break outside of the officially supported frequencies. [Proceed with caution.](https://github.com/UberGuidoZ/Flipper/blob/main/Sub-GHz/Restaurant_Pagers/SubGHz_changes.md)

# CAUTION within 402-408 range!<br>Medical devices can operate here.

This range is purposefully not included in my file above.