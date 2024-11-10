# Mock RDBMS with B-Tree Indexing

## Overview
This project demonstrates a simple implementation of an RDBMS with custom indexing using B-Trees. It highlights how indexes can improve the performance of database queries by reducing the number of data pages loaded from the disk.

## Key Features
<u>B-Tree Indexing:</u> Custom implementation of B-Tree data structures to create indexes.

<u>Page Scan vs Index Seek:</u> Comparison between the performance of page scans (without indexes) and index seeks (with B-Tree indexes).

<u>Improved Query Performance:</u> By using index seeks, the number of data pages read from the disk is minimized, leading to faster query execution.

## How It Works
<u>Without Index:</u> Queries are served by performing a full page scan, which requires reading all data pages.
<u>With Index:</u> An index is created using B-Trees, which allows queries to be executed using index seek. This reduces disk I/O and improves performance by loading fewer data pages.
