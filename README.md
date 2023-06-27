<img align="right" src="https://github.com/Aswendt-Lab/AIDAqc/blob/main/AIDA_Logo_wide.001.png" width="500">
<h1>AIDA<i>qc</i></h1>

*An automated and simple tool for fast qualtiy analysis of animal MRI*
<br/>
<br/>
<h3>Features</h3> 

- **Input:** Bruker raw data or NIFTY (T2-weighted MRI, diffusion weighted MRI or DTI, and rs-fMRI)
- **Calculations:** SNR, tSNR, movement variability, data quality categorization (finds bad quality outlier)
- **Output Format:** CSV sheets & pdf & images

<img align="left" src="https://github.com/Aswendt-Lab/AIDAqc/blob/main/AIDAqc_workflow.png">

<br/>
<br/>

[**See the poster for all details**](https://github.com/Aswendt-Lab/AIDAqc/blob/main/AIDAqc_Poster_Summary.pdf) 

<h3>Installation</h3> 
Download the repository => Install Python 3.6 (Anaconda) => Import AIDAqc conda environment aidaqc.yaml

Main function: *ParsingData*

See the full manual [here](https://github.com/Aswendt-Lab/AIDAqc/blob/main/AIDAqc_v2_1.pdf).

<h3>The story behind this tool</h3> 

It can be challenging to acquire MR images of consistent quality or to decide for the good vs. bad qualtiy data in a large databases. Manual screening without quantitative criteria is strictly user-dependent and for large databases is neither practical nor in the spirit of good scientific practice. In contrast to clinical MRI, in animal MRI, there is no consensus on standardization of quality control measures or categorization of good vs. bad quality images. As we were forced for a recent project to sreen hundreds of scans, we decided to automate this processa as part of our Atlas-based Processing Pipeline (AIDA).

<h3>Download test dataset</h3>
https://gin.g-node.org/Aswendt_Lab/AIDAqc_testdata

[<h3><b>CONTACT</h3></b>](https://neurologie.uk-koeln.de/forschung/ag-neuroimaging-neuroengineering/)
Aref Kalantari (aref.kalantari-sarcheshmehATuk-koeln.de) and Markus Aswendt (markus.aswendtATuk-koeln.de)

<h3><b>LICENSE</h3></b>

[GNU General Public License v3.0](https://github.com/aswendtlab/AIDAqc/blob/main/LICENSE)
