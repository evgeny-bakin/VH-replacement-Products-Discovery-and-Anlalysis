# IMGT V-QUEST BOT
IMGT v-quest bot (**IVB**) is a script written on python 3 allows you automatically form and send
 requests to the online tool [**IMGT v-quest**](http://www.imgt.org/IMGT_vquest/vquest). IVB takes the fasta input file containing the sequences 
and creates an output file in csv format, which contains information on the position and sequence of the N1 region.

### Installation
In order to start using IVB, download it and move it into one of your directories, and then go to the directory where 
is **IMGT\_V-QUEST\_BOT.py** and run it in the command line. To run, you need python 3 
and the following libraries:  

* [_selenium_](http://selenium-python.readthedocs.io/installation.html)   
* [_biopython_](http://biopython.org/)  
* [_argparse_](https://docs.python.org/3/library/argparse.html#)
  
When you start, you need to enter arguments, you can read more about this in the arguments section.

### Arguments
The command is formed in command line as follows:
   
```
python3 IMGT_V-QUEST_BOT.py -In path\to\file.fasta -Out path\to\file.csv -lc 2 -sp 1
```

Description of the arguments:  
**-h** - call the description of the arguments  
**-In** - specifies the input file in fasta format. You must specify `path/to/file.fasta`  
**-Out** - specifies the output file in csv format. You must specify `path/to/file.csv`  
**-lc** - specifies the locus, specify number of necessary locus on the IMGT v-quest  
**-sp** - specifies the species, specify number of necessary species on the IMGT v-quest  