Aim: Get enterprise example data for your applications with no hassle.

For security reasons running CentOS.


I plan to use different example databases for different purposes:

  * Northwind-like customer-product-address DB, ~20K records
  * Northwind-like customer-product-address DB, ~200K records
  * Geolocations, e.g. of capitals
  * Big data, content unclear yet, ~ 1 Mio records
  * Big data, content unclear yet, ~ 10 Mio records
  * Big data, content unclear yet, ~ 100 Mio records
 
The idea is that executing 'docker run' will set you up a prefilled, ready-to use DB with enterprise content. 

## General idea

  # ``docker run``
  # Shellscript inside the Docker image loads external (?) data.