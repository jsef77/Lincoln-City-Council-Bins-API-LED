# Lincoln-City-Council-Bins-API-LED
Node.js application to control an Ardunio LED depending on which bins to put out for the upcoming bin day
To simply save a .json file see [here](https://github.com/jsef77/Lincoln-City-Council-Bins-API/tree/main)

## Requirements

- Arduino board with FirmataStandardPlus sketch loaded ([See Here](https://github.com/rwaldron/johnny-five/wiki/Getting-Started#troubleshooting))
- Connected RGB LED (ensure that the correct pins are set in led-controller.js)

Tested with a [SparkFun RedBoard](https://www.sparkfun.com/products/13975) and a [Genuino UNO](https://uk.pi-supply.com/products/genuino-uno).

## Usage
in .env, enter the following:
- postcode
- [UPRN](https://www.findmyaddress.co.uk/search) (**preceded with '000'**, *e.g 000123456789*)
- LED colour (optional)

install the dependencies with:
```bash
npm install
```
run the application with:
```bash
node index.js
```
