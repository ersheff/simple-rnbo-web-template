# Simple RNBO Web Template

A bare minimum "single oscillator with frequency and volume controls" example for RNBO Web Export.  

- Web Audio requires a user-initiated event to start the audio context - a "Start Audio" button is provided for this purpose.
- HTML slider elements are provided to control the "osc-frequency" and "master-volume" parameters in the rnbo~ patch.
- During RNBO export, choose "Web Export" and set "Output Directory" to the export folder in this repository.
- FYI, if the "File Name" is changed during export, this will also need to be changed in the app.js file.
- Start a local server to launch exported project in a browser (e.g. using Live Server in VS Code).