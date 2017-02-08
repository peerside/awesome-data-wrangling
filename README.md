### Excel to CSV conversion

[xlsx2csv](https://github.com/dilshod/xlsx2csv)
Command line tool to convert xslx to csv. Fast and works for large xlsx files. Doesn't handle passwords.

[libreoffice](https://www.libreoffice.org/)
Use [GUI](https://www.libreoffice.org/) or [headless mode](http://shades-of-orange.com/post/How-to-Convert-an-XSLX-File-to-CSV-with-UTF-8-Encoding-Using-LibreOffice-OpenOffice) to convert xlsx to CSV. Doesn't seem to handle passwords or multiple sheets in headless mode 

[Apache POI](https://poi.apache.org/download.html)
Java APIs for manipulating various file formats based upon the Office Open XML standards. Can be used to extract text from spreadsheets, supports passwords etc. but can be memeory intensive.

[Excel Streaming Reader](https://github.com/monitorjbl/excel-streaming-reader#implementation-details)
Java streaming Excel reader using Apache POI - use for reading in large files without exhausting memory

### JSON Processing
[jq](https://stedolan.github.io/jq/)
A lightweight and flexible command-line JSON processor

### CSV Processing

[XSV CSV Toolkit](https://github.com/BurntSushi/xsv)
Fast, command line toolkit for CSV manipulation and analysis. Written in RUST

### Compression Tools
[zstandard](http://facebook.github.io/zstd) 
Fast, efficient compressor for small data sets (less than 100MB) leveraging pre trained dictionaries.

[shoco](http://ed-von-schleck.github.io/shoco/#home)
A fast acii biased, entropy encoder, for short strings using trained bigrams. Trained on english by default, supports training custom models.

[smaz](https://github.com/antirez/smaz)
Dictionary based compressor for very small strings (less than 100 bytes). By default uses english dictionary but can be customized via code.

### Data Exploration and Sharing
[Redash](https://github.com/getredash/redash)
Connect to any data source, easily visualize and share your data via dashboard. Open source and self hostable.

[Superset](https://github.com/airbnb/superset)
Data exploration platform designed to be visual, intuitive, and interactive. From Airbnb, python based, supports druid alo with other SQL sources.

[Metabase](https://github.com/metabase/metabase)
Visual analytics and dashboards from a wide range of SQL sources. Java based, SQL and non SQL modes, easy to share.
