# ps-csv-split
Split a CSV file into x number of files of a defined line count while preserving the header

## Parameters

`-CSVPath` (required)  
The.. location of the file. Can be a relative or full path.

`-ChunkSize` (optional) (default: 50)  
The number of lines each chunk should contain. The actual line count will be 1 more than defined if you include the header.

`-NewBasename` (optional)  
The name of each output file, by default, the original filename will be used.
In both cases `_SPLIT$int++` will be appended.
