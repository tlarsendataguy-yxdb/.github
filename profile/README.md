# YXDB

This organization contains repositories for libraries and tools which can read the YXDB file format.

### What is YXDB?

YXDB is a file format created by Alteryx to store and transfer data. It is moderately compressed for faster reads and is self-contained; all field metadata is included in the YXDB header.

### Why YXDB?

YXDB is an excellent data transfer format because of its moderate compression and embedded metadata. The moderate compression provides a balance between smaller file sizes and fast reads. The embedded metadata eliminates questions about the data format of individual fields.

YXDB is a superior alternative to the popular CSV format for several reasons:

* YXDB files are smaller than CSV
* All common data types are properly represented in YXDB. CSV only correctly represents strings and numbers.
* In YXDB, there are no questions about what data type each field contains. CSV requires knowing the intent of the original data source.

### Libraries

Libraries have been created for 4 major platforms/languages:

* [yxdb-go](https://github.com/tlarsendataguy-yxdb/yxdb-go), written in Go
* [yxdb-java](https://github.com/tlarsendataguy-yxdb/yxdb-java), written in Java for JVM
* [yxdb-net](https://github.com/tlarsendataguy-yxdb/yxdb-net), written in C# for .NET
* [yxdb-py](https://github.com/tlarsendataguy-yxdb/yxdb-py), written in Python
