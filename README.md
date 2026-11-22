# Exquis key test

A free page in the browser that tests an Exquis controller: every pad, button and encoder, the pressure of each pad, and MPE (velocity, X, Y and Z).

Open it here: https://alejo-end.github.io/exquis-test/

## How to use it

1. Plug the Exquis into the computer with a USB cable that carries data.
2. Close the Exquis app and any music software. Only one program can hold the Exquis.
3. Open the page in Chrome or Edge. Safari has no Web MIDI.
4. Press Connect, and allow MIDI access.

The tab "Pads, buttons, encoders" puts the Exquis into Developer Mode. Each control turns from red to green, on the screen and on the Exquis, when it sends. A yellow ring marks a pad that reached full pressure. "Give the Exquis back" ends Developer Mode.

The tab "MPE" lets the Exquis play as itself. Put it in MPE mode (the LED shows blue). Hit notes soft and hard, then rock each finger left and right (X, pitch bend), toward you and away (Y, CC 74), and press down (Z, pressure). Each check turns green when its range is reached.

Everything runs in the browser. No data leaves the computer.

## Notes

- In Developer Mode the Exquis may send every hit at velocity 127. Test velocity in the MPE tab.
- If X moves only a little, the Exquis's per-note pitch bend range is set low. The bar is scaled to the largest bend seen.

This is an independent page, not made by or affiliated with Intuitive Instruments. Exquis is their product.

## License

MIT. See LICENSE.
