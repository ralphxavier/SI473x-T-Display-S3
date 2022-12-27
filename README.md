# SI473x T-Display S3
SI4735/SI4732 Radio with Lilygo T-Display S3

# [Volos_TEmbedFMRadio_Port](Volos_TEmbedFMRadio_Port): TEmbedFMRadio sketch from Volos Projects ported to Si473x.
(For more detailed information, see the [README](Volos_TEmbedFMRadio_Port/README.md) at Volos_TEmbedFMRadio_Port)

This Si473x Radio uses the amazing library written by [PU2CLR (Ricardo Caratti)](https://github.com/pu2clr/SI4735). It is based on sketch from [Volos Projects](https://github.com/VolosR/TEmbedFMRadio). [Volos Projects](https://www.youtube.com/@VolosProjects) YouTube channel has a lot of tips and tricks for Lilygo T-Embed and Lilygo T-Display. I recommend this YouTube channel if you want to know more about this device and also about the tft_espi library, especially how to use sprites.

I am using a [Lilygo T-Display S3](https://github.com/Xinyuan-LilyGO/T-Display-S3), which is an ESP32S3 board with a 1.9 inch display with a 8-Bit Parallel Interface, but I believe it will also run on [Lilygo T-Embed](https://github.com/Xinyuan-LilyGO/T-Embed) by commentting out the line "#define I_use_T_Display_S3" and use a right TFT_eSPI library for that board.
