# Mock RDBMS with B-Tree Indexing

## Overview

This project demonstrates a simple implementation of an RDBMS with custom indexing using B-Trees. It highlights how indexes can improve the performance of database queries by reducing the number of data pages loaded from the disk.

## Key Features

### B-Tree Indexing: Custom implementation of B-Tree data structures to create indexes.

### Page Scan vs Index Seek: Comparison between the performance of page scans (without indexes) and index seeks (with B-Tree indexes).

### Improved Query Performance: By using index seeks, the number of data pages read from the disk is minimized, leading to faster query execution.

## How It Works

### Without Index: Queries are served by performing a full page scan, which requires reading all data pages.

### With Index: An index is created using B-Trees, which allows queries to be executed using index seek. This reduces disk I/O and improves performance by loading fewer data pages.
