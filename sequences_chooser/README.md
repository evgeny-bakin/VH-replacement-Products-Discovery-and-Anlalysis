# Sequences chooser

### Description

This code will help you to form clonal-independent sample of antibody sequences. Before running the program, you must use [Partis](https://github.com/psathyrella/partis) tool on your data with "partition" argument. 

### Running

Open terminal and run:
```
./create_families <fasta file with sequences> <Partis output file>
```
The results will be saved to "chosen_sequences.fasta". 

### Running example

You can check program's work using test files.
```
./create_families test.fasta test.csv
```

## Authors

* **Adel Gazizova** - [flowdel](https://github.com/flowdel)
* **Anastasiya Vinogradova**
