# FlashCards2
New version of Flash Cards with buttons to track correct answers.

  Flash Cards application with 
  Grove - 2x16 LCD RGB Backlight.

  Hardware needed:
    SD Card - I'm using external with SPI. 
      You could also use Teensy with
    Grove 2x16 LCD RGB Backlight. 
      You could moidfy for other screens.
    2 Buttons for correct and incorrect response.
      You decide if you are correct or not.

    Adjust FC_DELAY for you reading comfort.

    Program assumes file, fcards.txt, has alternating lines,
      first line is one language, next line is translation.
      While I am coding for Tagalog and English, you can use any
      2 languages. Set TagalogFirst to false if you want second 
      language displayed first.

  Copyright 2021 Tom Dison
  Licensed under GPL 3
  https://gnu.org/licenses/gpl-3.0.html
