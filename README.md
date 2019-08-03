# phyloHMM (now this is underconstruction)


## Purpose

per-site amino-acid frequency profiles of protein domains

***
## Usage
1.Clone the repo.

2.Go to the project's root folder.

3.Please install python and biopython.

4.Use python to execuate your files.
***
## required parameter
### --ali (input alignment) 

### --output_path (path)  
the directory of your output path

## optional parameter
### --database (hmm database)   
the hmm database you want to use. (default version: 3.1b1 | May 2013)


### --file_name (output file name)  
your output file name. (default is your input file name)

### --hmmer_path (path)
  the path of your hmmer scripts (hmmfetch hmmpress hmmscan)  (default version: h3.1b2 | February 2015)

### --gb_path (path)
the path of your gblocks file (default version: 0.91b)
### --iq_path (path)
the path of your iqtree file (default version: 1.6.10)
***
## example 
### use command:
python freq_extractor.py --ali example_files/example_input.fasta --output_path output --file_name example1
## Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
