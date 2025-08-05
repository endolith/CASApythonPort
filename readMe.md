# DUET Sound Separation Algorithm

Python code that implements the DUET (Degenerate Unmixing Estimation Technique) blind source separation algorithm.

Converted from yvesx's [CASA 495](https://github.com/yvesx/casa495) MATLAB code repository, which in turn was adapted from the Appendix of this publication:

- Rickard, S. (2007). [The DUET Blind Source Separation Algorithm](https://web.archive.org/web/20170513041921/http://www.cs.northwestern.edu/~pardo/courses/casa/papers/DuetSourceSeparationTutorial). In S. Makino, H. Sawada & T.-W. Lee (Eds.), *Blind Speech Separation* (pp. 217-241). Springer. <https://doi.org/10.1007/978-1-4020-6479-1_8> (ISBN 978-1-4020-6478-4)

It was converted to python to be more 'open source' - not everyone has MATLAB up and running and Octave doesn't do everything MATLAB can.

Course webpages:

- [EECS 495-022 Computational Auditory Scene Analysis](https://web.archive.org/web/20180521125513/http://www.cs.northwestern.edu/~pardo/courses/casa/papers.php)
- [University College Dublin](https://web.archive.org/web/20100329094309/http://eleceng.ucd.ie/~srickard/bss.html) (older [Princeton](https://web.archive.org/web/20050212232452/http://www.princeton.edu:80/~srickard/bss.html) version)

The 5-source mixtures audio example files in the [./data](./data/) folder are taken from the above webpages.  They are not the same files or mixing parameters as in the 2007 paper.

All the sound files present in the Data folder are credited to the original casa495 project.

## Credits

1. Scott Rickard
2. [yvesx](https://github.com/yvesx/casa495)
3. [harmeet88523](https://github.com/harmeet88523/CASA495_Python_Port)
4. [NareshPeshwe](https://github.com/NareshPeshwe/CASA495-Python-Code)
5. [bhargavvader](https://github.com/bhargavvader/CASApythonPort)

## See also

- <https://github.com/BrownsugarZeer/BSS_DUET/>
