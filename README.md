# 264662_MINIPROJECT

Python MiniProject For LTTS


![cc3](https://user-images.githubusercontent.com/80335764/115119782-cbb6df80-9fc7-11eb-9724-a183aa4a08d8.png)


This is a currency converter that uses historical rates against a reference currency (Euro).

Currency data sources
---------------------

The default source is the `European Central Bank <https://www.ecb.europa.eu>`_. This is the ECB historical rates for 42 currencies against the Euro since 1999.
It can be downloaded here: `eurofxref-hist.zip <https://www.ecb.europa.eu/stats/eurofxref/eurofxref-hist.zip>`_.
The converter can use different sources as long as the format is the same.

Installation
------------
Use the Python package:

  $ pip install --user currencyconverter

Command line tool
-----------------

After installation, you should have ``currency_converter`` in your ``$PATH``:

 $ currency_converter 100 USD --to EUR
 100.000 USD = 87.512 EUR on 2016-05-06
 
