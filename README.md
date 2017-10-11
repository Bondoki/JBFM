# JBFM
Mirror clone of the [JBFM][JBFM-link] to simulate polymeric systems with the bond-fluctuation model [1][BFM1] [2][BFM2] for educational purpose.

# Usage with GUI
Run the application by typing into your favorite shell
```sh
$ cd /path/to/JBFM.jar/
$ java -jar JBFM.jar
```

# Usage without GUI
For running the application as simulation tool, you first need to create a file with JBFM with GUI (save button).

```sh
$ cd /path/to/JBFM.jar/
$ java -jar JBFM.jar
# create conformation and file e.g. poly.bfm (save button)
# exit the GUI of JBFM
# to further run the simulation without GUI type and dump output into file
$ java -jar JBFM.jar --nogui directory filename simulationtime savetime
# e.g. java -jar JBFM.jar --nogui ./ poly.bfm 10000 1000
# open the GUI and load the conformation
```

