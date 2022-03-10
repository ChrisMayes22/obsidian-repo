![[Pasted image 20220310110026.png]]

Files are binary arrays, usually stored on a physical medium such as a hard disk or (in "the old days") computer tape. 

There are several problems with flat files as a strategy for achieving data persistence: 

1) Random access is inefficient, since relevant pieces of data may be large distances apart on the physical medium and linear search is slow.
2) Change to the file structure requires a change to the overall program, which makes maintenance difficult.
3) Different data may have different security requirements. Since file access tends to be all or nothing, this means there will tend to be "secure" and "non-secure" versions of files, which leads to duplicate data. Keeping that data consistent is then a maintenance challenge.

Modern "flat file" persistence tends to use data contracts that achieve a virtual [[hierarchical storage]] or [[network storage]] solution, as in XML or JSON files. 