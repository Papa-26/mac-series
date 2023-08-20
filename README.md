# A digital legacy for the Mac series of medical, educational computer simulations
This repository serves the construction of browser based representations of the historic mac-series computer simulations for medical education.

The mac-series of educational computer simulations was designed in the early 1970's. It was a cooperative project between a British and a Canadian medical school. The software was written in FORTRAN and ran initially on a main frame, later on DOS. It was long before graphical user interfaces. 

It contains:

    * models
        macman
        macpee
        macpuf
        macdope
    * manuals
        macman.pdf
        macpee.pdf
        macpuf.pdf
        macdope.pdf (will be added shortly)
    * demos
        MacDopeDemo.mp4 (quick and dirty OBSStudio animation)
The four model directories are organized identically:

    * a batch file ('man', 'pee', 'puf', and 'dope') to start the corresponding simulation
    * an input helper file 'readcon.com'
    * a graphics helper file 'METAWNDO.exe'
    * a printer helper file 'PRTSCRN.exe' (not used)
    * a binary program file 'mac*.exe' in DOS (ega)
    * a data repository 'DPXDRG.DAT' (macdope only)
    * required font files ('*.fnt')
