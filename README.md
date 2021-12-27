# kprice

Plot the price of cryptocurrencies on the Kraken exchange in gnome terminal using teletext characters.
This a single python script, which depends on the `requests`, `pandas`, and `numpy` packages. 
It uses the [Symbols for Legacy Computing](https://en.wikipedia.org/wiki/Symbols_for_Legacy_Computing) unicode block for plotting directly inside the terminal emulator. Most terminals based on the Gnome terminal support these characters. 

This pulls price data from the Kraken exchange, but it is not affiliated with Kraken in any way. 

![eg](https://user-images.githubusercontent.com/687425/147474259-e1edd0a8-830e-4c3a-be78-b4995c0fc2ec.png)

To changes colors, styles, defaults, etc, edit the python source code. This is provided as a self-contained demonstration of calling Kraken's REST API and plotting using unicode characters in the command line. The expectation is that users will modify/incorporate parts of this into their own script. 
