this is misha's repo for testing out rna-seq data analysis with rna-seq files from nasa's osdrFor now, it just contains a Python script that:

- Downloads paired FASTQ files for a sample from OSDR using `curl` in parallel threads
- Decompresses the downloaded `.gz` files
- Recompresses them after any processing (currently just decompress/recompress to keep data unchanged)
- Saves all files inside a `FASTQ` folder in the current user’s home directory (C:\Users\<username>\FASTQ)

this is by no means professional please use something else 
