# FOOTPRINT FINDER

### Description

This program allows you to find footprints in antibody sequences. You can use exact or inexact (with one mismatch) search. 

### Running

Open terminal and run:
```
./footprints_finder.py <V-Quest output file with N1 zones> <output directory> <kind of footprint search (exact or inexact)>
```
The results will be saved to "exact_result.txt" or "inexact_result.txt" depending on the selected search.

### Running example
```
./footprints_finder.py '/Users/Desktop/my_folder/N1_zones.csv' '/Users/Desktop/my_folder' exact
```

## Authors

* **Adel Gazizova** - [flowdel](https://github.com/flowdel)
* **Anastasiya Vinogradova** - [newCarroll](https://github.com/newCarroll)
