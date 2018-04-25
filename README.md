# Postcodes Around London PHP array
A PHP array of postcode first halfs within radius of the M25 around London. useful for populating database tables that you need to test locational queries. Some of these postcodes have 100 mile + distance between them.

Loop over them, use Google Maps API to grab coordinates of eah and store in DB table. From there you can test MySQL Geospacial functions, measuring distances, getting results based on distance etc.
