Readme for creation of volcanic/solar forcing figure
IPCC AR6 Chapter 2

1. Download relevant data
* file: eVolv2k_v3_EVA_AOD_-500_1900_1.nc location: https://cera-www.dkrz.de/WDCC/ui/cerasearch/entry?acronym=eVolv2k_v3
* file: SSI_14C_cycle_yearly_cmip_v20160613_fc.nc, location: https://pmip4.lsce.ipsl.fr/doku.php/data:solar_satire
* file: solarforcing-ref-mon_input4MIPs_solar_CMIP_SOLARIS-HEPPA-3-2_gn_18500101-22991231.nc, location: http://solarisheppa.geomar.de/cmip6
* file: TSI_WLS_mon_1882_2008.txt http://solarisheppa.geomar.de/cmip5

2. Modify directories in Matlab script 'IPCC_load_and_save_volc_solar_data_Final.m'
* replace location to save data files in line 5
* replace locations for all data downloaded in step 1
* replace locations for data files included in this package, including tau.map_2002.txt, tau.map_2012.12b.txt and TSI_Composite.xlsx

3. Run script 'IPCC_load_and_save_volc_solar_data_Final.m'
* this will create excel spreadsheets including the global mean, annual mean data to be plotted

4. Modify directories in Matlab script 'IPCC_Ch2_plot_volc_solar_RF_Final.m'
* have 'data_dir' point to where you saved the spreadsheets produced in step 3
* have 'fig_save_dir' point to where you want te output figure saved

5. Run 'IPCC_Ch2_plot_volc_solar_RF_Final.m'

for help or more information, contact Matthew Toohey, matthew.toohey@usask.ca

https://doi.org/10.5281/zenodo.6355884




