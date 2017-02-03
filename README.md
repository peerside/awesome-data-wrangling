### Excel to CSV conversion

[xlsx2csv](https://github.com/dilshod/xlsx2csv)
Command line tool to convert xslx to csv. Fast and works for large xlsx files. Doesn't handle passwords.

[libreoffice](https://www.libreoffice.org/)
Use [GUI](https://www.libreoffice.org/) or [headless mode](http://shades-of-orange.com/post/How-to-Convert-an-XSLX-File-to-CSV-with-UTF-8-Encoding-Using-LibreOffice-OpenOffice) to convert xlsx to CSV. Doesn't seem to handle passwords or multiple sheets in headless mode 

[Apache POI](https://poi.apache.org/download.html)
Java APIs for manipulating various file formats based upon the Office Open XML standards. Can be used to extract text from spreadsheets, supports passwords etc. but can be memeory intensive.

[Excel Streaming Reader](https://github.com/monitorjbl/excel-streaming-reader#implementation-details)
Java streaming Excel reader using Apache POI - use for reading in large files without exhausting memory

### JSON
[jq](https://stedolan.github.io/jq/)
A lightweight and flexible command-line JSON processor

### CSV Processing

[XSV CSV Toolkit](https://github.com/BurntSushi/xsv)
Fast, command line toolkit for CSV manipulation and analysis. Written in RUST
