# A digital legacy for the Mac series of medical, educational computer simulations
This repository serves the construction of browser based representations of the historic mac-series computer simulations for medical education. The ultimate aim is to create an archival site that transmits the spirit of the mac series:

![concept outline](Concept.png)

The mac-series of educational computer simulations was originally designed in the early 1970s. It was a cooperative project between a British and a Canadian medical school. The software was written in FORTRAN and ran first on a main frame at McMaster, in the 1980s an updated version was issued on DOS at St. Bartholomew's. It was long before graphical user interfaces. 

Thanks to [Jeff Par](https://github.com/jeffpar) the mac-series simulations now run in [browsers](https://www.pcjs.org/software/pcx86/app/other/mac-series/1.0/). Google Chrome or Brave are the recommended browsers. Set the operating frequency (right lower corner) as high as it will go.

The repository contains:

    * models
        macman
        macpee
        macpuf
        macdope
    * manuals
        MacMan.pdf
        MacPee.pdf
        MacPuf.pdf
        MacDope.pdf
    * demos
        MacDopeDemo.mp4 (quick and dirty OBSStudio animation)
The four model directories are organised identically:

    * a batch file ('man', 'pee', 'puf', and 'dope') to start the corresponding simulation
    * an input helper file 'readcon.com'
    * a graphics helper file 'METAWNDO.exe'
    * a printer helper file 'PRTSCRN.exe' (not used)
    * a binary program file 'mac*.exe' in DOS (ega)
    * a data repository 'DPXDRG.DAT' (macdope only)
    * required font files ('*.fnt')
