# STOP_LOSS_MARKET_PROJECT
This version includes a test data version and a real data version.

This program is intended to simulate setting up a STOP_LOSS_MARKET SELL order type for the Binanace online trading platform.

This version is similar to the "MBX_STOP_LOSS" project except for a few key differences.

To run this file you will need the following:

  1) All of the files in this repository.
  2) A working API key and secret key for Binance.

For the test.py version you do not need API Keys or a Secret Key. You only need to enter the parameters.
It is currently set to a setting that will end it rapidly, so feel free to adjust the "market price change" to test more data.


In addition, this program is run from the command line by inputting your parameters.


For example, if you wanted to simulate a market sell stop loss order of 10.0 BNB for BTC at a price of 0.0014500 you would enter the following into the command line: "python3 real.py BNBBTC STOP_LOSS_MARKET SELL 10.0 @ 0.0014500".

The order does not matter, however you must include an "@" before the trigger price for your stop loss market sale.

You must also put a space in between each argument you give on the command line.
