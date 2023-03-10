**DASmrrcoh**
======

## Description

**DASmrrcoh** package is used to store the reproducible and open-access scripts for denoising DAS data using MRR and enhancing earthquake detection by COHerency measure.

## Reference
If you find this package useful, please do not forget to cite the following paper.

    Chen, Y., Savvaidis, A., Chen, Y., Saad, O.M., and Fomel, S., (2023). Enhancing earthquake detection from distributed acoustic sensing data by coherency measure and moving-rank-reduction filtering, under review.
    
BibTeX:
	
	@article{dasmrrcoh,
	  author={Yangkang Chen and Alexandros Savvaidis and Yunfeng Chen and Omar M. Saad and Sergey Fomel},
	  title = {Enhancing earthquake detection from distributed acoustic sensing data by coherency measure and moving-rank-reduction filtering},
	  journal={TBD},
	  year=2023,
	  volume=X,
	  issue=X,
	  pages={under review},
	  doi={XXX},
	}

-----------
## Copyright
    Authors of the dasmrrcoh paper, 2021-present
-----------

## License
    GNU General Public License, Version 3
    (http://www.gnu.org/copyleft/gpl.html)   

-----------

## Install
Using the latest version

    git clone https://github.com/chenyk1990/dasmrrcoh-dataonly
    cd dasmrrcoh-dataonly
    addpath(genpath('./')); #in Matlab command line
    
-----------
## Examples
    The "main" directory contains all runable scripts test_figNO.m to reproduce all figures in the paper.
 
-----------
## Dependence Packages
* MATdrr (https://github.com/chenyk1990/MATdrr)
    
-----------
## Development
    The development team welcomes voluntary contributions from any open-source enthusiast. 
    If you want to make contribution to this project, feel free to contact the development team. 

-----------
## Contact
    Regarding any questions, bugs, developments, collaborations, please contact  
    Yangkang Chen
    chenyk2016@gmail.com

-----------
## NOTES:
 
1. To run the reproducible scripts (test_xxxx.m), please first download the required package from: https://github.com/chenyk1990/MATdrr. 

2. Please put the MATdrr package in the main directory and add its sub-directories to the Matlab toolbox path. 

3. The scripts beginning with "test_" are runnable scripts.

4. The script [test_processall.m](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/test_processall.m) is the script that generates all the results in the folders processed and figresults.

5. The directory [subroutines](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/subroutines) stores all the required subroutines. 

6. The directory [figresults](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/figresults) stores all the results from the proposed denoising workflow.

7. The directory [raw](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/raw) stores all the segmented multi-channel DAS seismic data at the SAFOD site. 

9. The directory [processed](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/processed) stores all the denoised DAS data. 

9. The current version is based on Matlab. Future versions will also support Python and be optimized regarding computational efficiency. 

10. All datasets used in these DEMO scripts or produced from massive processing based on this package are in a separate repository https://github.com/chenyk1990/dasmrrcoh-dataonly (for easier downloading). 

11. The difference between the two "similar repositories" [dasmrrcoh](https://github.com/chenyk1990/dasmrrcoh) and [dasmrrcoh-dataonly](https://github.com/chenyk1990/dasmrrcoh-dataonly) is that the latter is only used for storing the data (several GBs) and the former is only used for storing the scripts (less than 1 MB). 

12. All figures (except for fig1, which is a schematic plot) in the DASmrrcoh paper are in the following directory for a quick look (https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/gallery/). 

13. The label fonts are different across different Matlab versions and platforms (Linux, Max). The figures presented in the paper are from Mac-Pro Matlab 2022b. 

14. If the package is too large for downloading, the following option can be used:

	svn co https://github.com/chenyk1990/dasmrrcoh/trunk dasmrrcoh
	
	svn co https://github.com/chenyk1990/dasmrrcoh-dataonly/trunk/raw dasmrrcoh/raw
	
	Then, run the scripts in dasmrrcoh. 


-----------
## Gallery
The gallery figures of the DASmrrcoh package can be found at
    https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/gallery/
Each figure in the gallery directory corresponds to a test_figNO.m script in the "main" directory with the exactly the same file name (figNO.png).

These gallery figures are also presented below. 

Figure 2 Generated by [test_fig2.m](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/test_fig2.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/dasmrrcoh/fig2.png' alt='Slicing' width=960/>

Figure 3 Generated by [test_fig3.m](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/test_fig3.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/dasmrrcoh/fig3.png' alt='Slicing' width=960/>

Figure 4 Generated by [test_fig4.m](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/test_fig4.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/dasmrrcoh/fig4.png' alt='Slicing' width=960/>

Figure 5 Generated by [test_fig5.m](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/test_fig5.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/dasmrrcoh/fig5.png' alt='Slicing' width=960/>

Figure 6 Generated by [test_fig6.m](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/test_fig6.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/dasmrrcoh/fig6.png' alt='Slicing' width=960/>

Figure 7 Generated by [test_fig7.m](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/test_fig7.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/dasmrrcoh/fig7.png' alt='Slicing' width=960/>

Figure 8 Generated by [test_fig8.m](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/test_fig8.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/dasmrrcoh/fig8.png' alt='Slicing' width=960/>

Figure 9 Generated by [test_fig9.m](https://github.com/chenyk1990/dasmrrcoh-dataonly/tree/main/test_fig9.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/dasmrrcoh/fig9.png' alt='Slicing' width=960/>

