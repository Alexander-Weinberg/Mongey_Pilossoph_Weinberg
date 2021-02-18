This repository contains the code which replicates "[Which Workers Bear the Burden of Social Distancing?](Mongey_Pilossoph_Weinberg_Social_Distancing_Feb_2021.pdf)" by Simon Mongey, Laura Pilossoph, and Alex Weinberg. 

This replication package downloads the data available online and reproduces the results available in our paper.

## Work-from-home measures

The following data on occupation work-from-home ability and physical-proximity may be useful for your research:
- [2 digit Census OCC](Files/lwfh_pp_occ_2digit.csv)
- [3 digit Census OCC](Files/lwfh_pp_occ_3digit.csv)

## Source data

We use publicly available data from:
- [O\*NET](https://www.onetcenter.org/db_releases.html)
- [OES](https://www.bls.gov/oes/home.htm)
- [ATUS](https://www.bls.gov/tus/)
- [CPS](https://www.bls.gov/cps/)
- [PSID](https://psidonline.isr.umich.edu/)

We include here the extracts of those data sources necessary to replicate our paper. If you wish to download separately, please download:
- ONET Database 24.2
- OES 2018 National and Industry-specific
- ATUS 2018 
- March 2019 Annual Social and Economic Supplement to CPS
- CPS is downloaded from [IPUMS](https://cps.ipums.org/cps/)
	- February, April, and August 2010-2020
	- May-November 2020 **Covid Module**
	- January 2008 and February 2010
- Tomer and Cain 2020 essential industry [classification](https://www.brookings.edu/wp-content/uploads/2020/03/Front-Line-Workers-Appendix.docx).

## Replication instructions

1. Download this repository by clicking the green `Clone or download` button above. Unzip into the directory of your choice. 
2. Open `main.do`.
3. Set the working directory.
4. If necessary, download the required packages.
5. Run `main.do`.



