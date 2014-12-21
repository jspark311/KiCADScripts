Ian's KiCAD Scripts
=======================
As I collect more of these, I will post them here for others to use.


bom-parse.php
------------------
This script will accept BOMs (bills of material) files formatted in CSV, and if you have provided (and exported) the fields in your KiCAD schematic, it will scrape Digikey for part costs and give a report.

The script also respects the quantity discount fields from Digikey, and takes into account how many of a given part per unit, and how many units you are planning on building.

If anyone at Digikey or Mouser ever read this:
It would be *awesmoe* if you would expose some kind of API for this sort of thing. Scraping HTML files costs you bandwidth, and me sanity. :-)
