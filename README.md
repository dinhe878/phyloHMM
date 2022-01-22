# phyloHMM (now this is underconstruction)
per-site amino-acid frequency profiles of protein domains


## Usage
1. Clone the repo.
2. Go to the project's root folder.
3. Please install python and biopython.
4. Use python to execuate your files.

### Required parameter
#### --ali (input alignment) 
#### --output_path (path)  
the directory of your output path

### Optional parameter
#### --mode con(default)|rep
how to construct a sequence for HMM data base search
+ con : generate a consensus sequence found using `hmmemit --symfrac 0`
+ rep : pick up a representative single sequence from input alignment with highest pairwise similarity

#### --database (hmm database)   
the hmm database you want to use. (default version: 3.1b1 | May 2013)


#### --file_name (output file name)  
your output file name. (default is your input file name)

#### --hmmer_path (path)
  the path of your hmmer scripts (hmmfetch hmmpress hmmscan hmmbuild hmmemit)  (default version: h3.1b2 | February 2015)

#### --gb_path (path)
the path of your gblocks file (default version: 0.91b)
#### --iq_path (path)
the path of your iqtree file (default version: 1.6.10)

## Example 
### use command:
python3 freq_extractor.py --ali example_files/example_input.fasta --output_path output --file_name example1
## Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
