# ProPresenter-vMix

Uses the ProPresenter Stage Display network API to feed current slide text into a vMix text input for lower thirds.

This was quickly written one morning before service, and still needs some serious cleanup. Please read through the comments in the code to see what info needs changed to match your environment.

Rename config.js.example to config.js and update the values to match your environment. Then open index.html in the browser of your choice.

Set the slide notes to `novmix` on a slide to prevent it from being sent to vMix (useful for slides with more text than you would want in a lower third).