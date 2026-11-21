# Block-Level Syncing & Deduplication

Seafile splits files into 1MB - 3MB blocks using CDC (Content-Defined Chunking). When a file is modified, only updated blocks are transferred across the network, reducing sync bandwidth by up to 95%.
