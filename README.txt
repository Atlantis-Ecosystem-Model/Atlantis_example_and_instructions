This folder contains input files needed to run example SE Tasmanian Atlantis ecosystem model. 
For more details about the model see https://github.com/Atlantis-Ecosystem-Model/Atlantis_example_and_instructions#input-files

The example files provided here will run the simulation for 365 days. This takes about 1-2 minutes on a standard laptop computer.  

######################
To run the SE Tasmanian example model on Windows: 

1. Put the atlantis exectutable file (atlantismain.exe) and all .dll files that come with it into 
the same folder as your input files. 
2. Open the command terminal 
3. Navigate to the folder that has atlantismain.exe, .dll files and input files. \
4. Type the name of the .bat file, in this case run_example.bat 

######################
Note, Atlantis will start loading input files, and output a lot of warning messages. 
Most of these warning messages just inform users about the spatial position of their functional groups, missing non-essential parameters
and other model aspects and can be ignored for now. 

When all input files are loaded and checked and the actual simulations start Atlantis will start producing daily output like this: 

t = 0.5, hd.t = 1.75, TofY: 0, % Done: 0.136986
t = 1, hd.t = 2.25, TofY: 1, % Done: 0.273973
t = 1.5, hd.t = 2.75, TofY: 1, % Done: 0.410959
...

When simulations end Atlantis will print:

t = 364, hd.t = 365.25, TofY: 364, % Done: 99.726027
t = 364.5, hd.t = 1.153843746e+032, TofY: 364, % Done: 99.863014
Freeing general box arrays
Freeing model variables
Freeing biology specific arrays
Freeing the home range structures
Freeing fishery specific arrays
Freeing physics specific arrays
Skip freeing assessment specific arrays
Freeing box geometry
Freeing biological arrays
Freeing names
Freeing fisheries arrays
Freeing market arrays
Freeing fuel arrays
Freeing assessment arrays
Freeing performance measures
Freeing physiochem property memory

##################### 
The example above is only a very brief introduction into running Atlantis. For more details check 
For more details about the model see https://github.com/Atlantis-Ecosystem-Model/Atlantis_example_and_instructions#input-files 
which will direct you to further information on Atlantis user guide and wiki 
