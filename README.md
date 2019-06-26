# ProtoStax_Weather_Station_Demo
Demo for ProtoStax Weather Station with ePaper Display and Raspberry Pi

![ProtoStax Weather Station Demo](ProtoStax_Weather_Station_Demo.jpg)

using [ProtoStax for Raspberry Pi B+](https://www.protostax.com/products/protostax-for-raspberry-pi-b)

## Prerequisites

Enable SPI on the Raspberry Pi
API Key from Open Weather Map  - [https://openweathermap.org/api](https://openweathermap.org/api)
City ID from Open Weather Map for the city of your choice - see
main.py comments for more details

## Installing

This demo uses the PyOWM library - see [https://github.com/csparpa/pyowm](https://github.com/csparpa/pyowm)
It also uses Waveshare's ePaper libary - see [https://github.com/waveshare/e-Paper](https://github.com/waveshare/e-Paper)
but includes the necessary files from that library directly

```
sudo pip install pyowm
git clone https://github.com/protostax/ProtoStax_Weather_Station_Demo.git
```

## Usage

```
cd ProtoStax_Weather_Station_Demo
```

Edit main.py and add your Open Weather Map API key and City ID for the
city whose weather report you like

```
python3.5 main.py
```

## License

Written by Sridhar Rajagopal for ProtoStax. BSD license, all text above must be included in any redistribution

A lot of time and effort has gone into providing this and other code. Please support ProtoStax by purchasing products from us!
Also uses the Waveshare ePaper library. Please support Waveshare by purchasing products from them!


