# Expressiva_AI

An AI environment developed for music producers. Featuring Allegretta, a Bidirectional LSTM raw-to-MIDI audio converter, and Melodica, an Attention RNN music generator.

*How Melodica works*
Melodica is composed of two parts, the front-end which is in the static folder and the back-end which is in the server folder. The front-end client creates short MIDI files using the players's input which is sent to a Flask server. The server takes that MIDI input and "continues" it using Magenta and TensorFlow which is then returned back to the user and shown as notes on the piano.

*How Allegretta works*
An LSTM was trained on 10 years-worth of International E-piano Competition performances to accurately analyze pitches and rhythms of raw audio and convert to a downloadable MIDI file.
