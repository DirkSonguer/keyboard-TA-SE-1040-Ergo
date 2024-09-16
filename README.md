# Triumph-Adler SE 1040 Ergo Study
This repo documents the Triumph-Adler 1040 Ergo Study keyboard. Personally, I have been a fan of Triumph-Adler keyboards for quite some time, especially the [TA 1040 series of keyboard computers](https://github.com/DirkSonguer/keyboard-TA-SE-1040). In 2023, I came across a weird version that I couldn't identify - the "Ergonomiestudie".

![TA SE 1040 Ergo Front View](https://github.com/DirkSonguer/keyboard-TA-SE-1040-Ergo/blob/main/images/TA-SE-1040-Ergo-front.jpg "TA SE 1040 Ergo Front View")

I was able to obtain the keyboard from the estate of Gernot Haltenorth, a previous technical writer for Triumph-Adler. Haltenorth rescued the "Ergonomiestudie" ("Ergo Study") prototype board when the company closed its development and production facilities around 1993, as any unfinished or unsellable inventory was about to be destroyed. In fact, besides many regular Triumph-Adler typewriters and computers, the collection did contain many prototypes based around existing boards.

![Triumph-Adler Collection & Prototypes](https://github.com/DirkSonguer/keyboard-TA-SE-1040-Ergo/blob/main/images/TA-SE-1040-Ergo-collection-prototypes.jpg "Triumph-Adler Collection & Prototypes")

What makes the ergo study special is that Triumph-Adler never released any ergonomic keyboard layout - neither on a typewriter, not with their Aphatronic computers. So while this study looks pretty complete and usable, it never made it into production.

The other interesting aspect is the time. As far as I can date the keyboard, it was likely created in the mid to late 1980s. This puts it right in the [early wave of ergonomic studies](http://xahlee.info/kbd/i2/split_keyboard__david_Rempel_2008_HF.pdf), around the time of the [TRON keyboard](http://xahlee.info/kbd/TRON_keyboard.html). This was before the APple Adjustable keyboard (1992), the Kinesis Corporation Model 100 (1992) and the Microsoft Natural Keyboard (1994).

It seems like the ergo study was specifically created for just that - scientific and technical studies on typing preference, ergonomics, features, and internal components. I couldn't find any official documentation of mention of the board, expect one: A [technical illustration](https://www.provinz.bz.it/katalog-kulturgueter/de/neu-erfasste-objekte.asp?kks_priref=150016971) in the typewriter museum "[Peter Mitterhofer](https://www.schreibmaschinenmuseum.com/en/)" in Switzerland (shown below with permission). Note that the illustration describes the keyboard as an SE 1041, which is the SE 1040 edition with internal memory expansion & external 5.25 floppy disk drive.

![Triumph-Adler Museum Peter Mitterhofer](https://github.com/DirkSonguer/keyboard-TA-SE-1040-Ergo/blob/main/images/TA-SE-1040-Ergo-SMM_003005_00large.jpg "Triumph-Adler Museum Peter Mitterhofer")

With this, my aim is to document the 1040 ergo study as detailed as possible for fans of Triumph-Adler boards, as well as ergo keyboard enthusiasts.

## A quick look inside
Opening the case immediately confirms that this is a prototype board. While the top was cleaned up and treated to look like a proper mold, the bottom reveals that the case was likely from a regular TA SE 1040, but with retrofitted cuts and additional material grafted onto it to create the shape for the split alpha keys.

![Triumph-Adler Collection & Prototypes](https://github.com/DirkSonguer/keyboard-TA-SE-1040-Ergo/blob/main/images/TA-SE-1040-Ergo-interior-details.jpg "Triumph-Adler Collection & Prototypes")

Looking at the plate, the biggest difference between the ergo study and a regular SE 104x keyboard unit is the change in display. While the regular SE 104x series used a [Vacuum Fluorescent Display](https://en.wikipedia.org/wiki/Vacuum_fluorescent_display) (VFD), the ergo study uses an LCD. This is not unheard of, as the [SE 1035/C](https://www.provinz.bz.it/katalog-kulturgueter/de/suche.asp?kks_priref=150008271) (released in 1985) also used an LCD in a keyboard unit very similar to this. Notably, it had the brightness dial on the right side of the display, instead of the left.

Shown below: The Ergo study on top, below a regular SE 1041.
![Triumph-Adler Plate Comparison](https://github.com/DirkSonguer/keyboard-TA-SE-1040-Ergo/blob/main/images/TA-SE-1040-Ergo-plate-comparison.jpg "Triumph-Adler Plate Comparison")

## Looking deeper
TA PCBs are usually dark green with a uniform and clean component assembly. The ergo study however features a light green transparent PCB - as used in prototypes to better see the layers and connections. The components also look very much hand soldered, with hand written notes everywhere.

Shown below: The Ergo study PCB on top, below from a regular SE 1041.
![Triumph-Adler PCB](https://github.com/DirkSonguer/keyboard-TA-SE-1040-Ergo/blob/main/images/TA-SE-1040-Ergo-pcb.jpg "Triumph-Adler PCB")

Also note that the ergo study features a product ID: B130651, edition 0, compared to the SE 1040 series with ID B130533, and editions 1 to 8.

The bottom half of the PCB is similar, connecting the switches to the board. However, the upper half of the PCB is completely different. The SE 1040 series is dominated by the VFD and its 12 Texas Instruments UCN4810A display driver chips. In the  ergo study, the LCD display is located on a daughter board, raised above the actual PCB and connected with a soldered ribbon cable. The driver chips for the display are located below the daughter board and are labelled with little handwritten notes and dates.

![Triumph-Adler Display](https://github.com/DirkSonguer/keyboard-TA-SE-1040-Ergo/blob/main/images/TA-SE-1040-Ergo-display.jpg "Triumph-Adler Display")
