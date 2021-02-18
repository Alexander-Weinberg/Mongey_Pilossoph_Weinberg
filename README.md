This repository contains the code which replicates "[Which Workers Bear the Burden of Social Distancing?](Mongey_Pilossoph_Weinberg_Social_Distancing_Feb_2021.pdf)" by Simon Mongey, Laura Pilossoph, and Alex Weinberg. 

## Work-from-home measures

The following data on occupation work-from-home ability and physical-proximity may be useful for your research.
- [2 digit Census OCC](Files/lwfh_pp_occ_2digit.csv)
- [3 digit Census OCC](Files/lwfh_pp_occ_3digit.csv)

## Source data

We use publicly available data from:
- [O\*NET](https://www.onetcenter.org/db_releases.html) Database 24.2
- [OES](https://www.bls.gov/oes/home.htm) 2018
- [ATUS](https://www.bls.gov/tus/) 2018
- [CPS](https://www.bls.gov/cps/) 
	- March 2019 Annual Social and Economic Supplement to CPS
	- **Monthly CPS**: February, April, and August 2010-2020 and January 2008.
	- **Covid Module**: May-November 2020 

- [PSID](https://psidonline.isr.umich.edu/) 2018
- Tomer and Cain 2020 essential industry [DHS classification](https://www.brookings.edu/wp-content/uploads/2020/03/Front-Line-Workers-Appendix.docx)

## Replication instructions

1. Download this repository by clicking the green `Clone or download` button above. Unzip into the directory of your choice. 
2. Open `main.do`.
3. Set the working directory.
4. If necessary, download the required packages.
5. Run `main.do`.


## Code organization

### Raw Data
Raw data is available in the `Raw Data` folder. Subfolders indicate the source of the data. 

### Code
The code which replicates our paper is available in the `Do` folder. 
The following scripts clean the ONET and OES data and create our social-distancing exposure measures.

1. `clean_ONET.do`
2. `clean_OES.do`
3. `construct_exposure_measures.do`

The following scripts clean the worker data. The clean data is saved in `Data`. 

4. `essential_occupations.do`
5. `clean_PSID.do`
6. `clean_CPS.do`
7. `clean_ATUS.do`

The following scripts create the figures in the body of the paper and the appendix. The figures are saved in the `Figures` folder.

- `fig1.do`
- `fig2.do`
- `fig3.do`
- `fig4.do`
- `fig5.do`
- `fig6.do` 

- `figB1.do`
- `figB2.do`
- `figB3.do` 
- `figB4.do`

The following scripts create the tables in the body of the paper and the appendix. The tables are saved in the `Tables` folder.

- table1.do

- tableA1.do 
- tableA2.do 
- tableA3.do 
- tableA4.do

- table_B1_B2_B3.do
- table_B4_B5.do
