# ESP8266_Spotify_Control
Use your ESP8266 to control your Spotify Tracks. The project uses a series of electronic components coupled with the ESP8266 to control your spotify tracks via a Circuit on a Breadboard!
The Project use a Flask server coded in Python that uses the Spotipy

I had always wanted to interface a retro-looking display like a 16x2 LCD Display with some of the applications I use on a fairly daily basis. So I decided to create an efficient display that displays the song playing on your spotify in real time and can be controlled with the help of just 3 buttons!

The code has two parts the ESP8266 and the Python Flask server:
## 1. ESP8266 : 
The ESP8266 executes GET requests to the Flask Server and prints the data to the LCD Display connected. The buttons, when pressed, execute POST requests to the Flask server which can either pause or play or can be used to change the song to the next or the previous track.

## 2. Python Flask Server :

The Python server uses the ‘Spotipy Library’ to get the information from Spotify using the Spotify API. The Server essentially reduces the data set to the required key-value pairs and makes the deserialization of the data faster and also significantly makes coding the ESP8266 easier as well.

### Materials Required : 

1.16x2 Segment Display.
2. I²C Module ( to help interface the Display with the ESP8266 using I²C protocol)
3. Node MCU ESP8266
4. Male - Male Jumper wires
5. Male- Female Jumper wires
6. Resistors (I used 10k Ohm (Ω) here)
7.3 x Buttons
8.Breadboard 
9. Micro USB cable

You can assemble the circuit as shown in the picture below and keep an eye out for the legend in the bottom right corner.
