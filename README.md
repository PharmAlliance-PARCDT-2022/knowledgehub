# PharmAlliance Collaboration Knowledge Hub


## About this Repository

This respository is designed to allow for greater collaboration between University College London, University of North Carolina Chapel Hill, and Monash University on pharmacoepidemiological research. 

This repository follows the recommendations and guidance provided in *[The Turing Way](https://the-turing-way.netlify.app/welcome)* handbook to data science.

This repository includes information about researchers involved, including their specialities and technical skills, an overview of the data available at each site, codelists and code for analysis and plots, and resources for training.

---
## Repository Structure

```
├── LICENSE
├── README.md          <- The top-level README for users of this project.
├── CONTRIBUTING.md    <- Information on how to contribute to the project.
├── analysis_code
    ├── README.md      <- Information on how to contribute to add a code for analysis of data.
    ├── R    
    ├── Python 
    └── SAS  
├── codelists
    ├── README.md      <- Information on how to contribute to add a Codelist and in what format.
    ├── CPRD_Gold    
    ├── CPRD_Aurum  
    └── READ_Codes 
├── data_management_code
    ├── README.md      <- Information on how to contribute to add a code for data extraction and management.
    ├── R    
    ├── Python 
    └── SAS     
├── plot_code
    ├── README.md      <- Information on how to contribute to add a code for producing plots.
    ├── R    
    ├── Python 
    └── SAS 
├── useful_slides      <- Slides from talks that may be useful to the team.
└──
```

---

## 🌎 Meet the Team
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
  <h3><b>UCL</b></h3>
    <tr>
      <td align="center" width="250px"><a href="https://iris.ucl.ac.uk/iris/browse/profile?upi=OBRYA73"><img src="https://media.licdn.com/dms/image/D4E03AQGiu-LdHBHK8A/profile-displayphoto-shrink_800_800/0/1678731034057?e=2147483647&v=beta&t=mQnJcXPkvZiAh31ZBGgnvg4D__yyQuNEWkHB-7XuOzk" width="200px;" alt="Olivia Bryant"/><br /><b>Olivia Bryant</b></a><br />
      First Year PhD Student<br/>
      🔬 Dementia, antipsychotic use, data visualization methods</br>
      👩‍💻R (advanced), SAS (beginner), Python (intermediate)</td>
      <td align="center" width-="250px"><a href="https://orcid.org/0000-0003-2320-0470"><img src="https://avatars.githubusercontent.com/u/47313528?v=4" width="200px;" alt="Wallis Lau"/><br /><b>Wallis CY Lau</b></a><br />
      Lecturer in Pharmacoepidemiology and Drug Safety<br/>
      🔬</br>
      👩‍💻</br></br></br></td>
      <td align="center" width="250px"><a href="https://orcid.org/0000-0003-2320-0470"><img src="https://avatars.githubusercontent.com/u/47313528?v=4" width="200px;" alt="Wallis Lau"/><br /><b>Person</b></a><br />
      Title<br/>
      🔬 Research Interets</br>
      👩‍💻 technical skills/research methods</br></br></br></td>
    </tr>
  </tbody>
</table>
<table>
  <tbody>
  <h3><b>UNC</b></h3>
    <tr>
      <td align="center" width="250px"><a href="https://orcid.org/0000-0003-2320-0470"><img src="https://avatars.githubusercontent.com/u/47313528?v=4" width="200px;" alt="Wallis Lau"/><br /><b>Person</b></a><br />
      Title<br/>
      🔬 Research Interets</br>
      👩‍💻 technical skills/research methods</br></br></br></td>
      <td align="center" width="250px"><a href="https://orcid.org/0000-0003-2320-0470"><img src="https://avatars.githubusercontent.com/u/47313528?v=4" width="200px;" alt="Wallis Lau"/><br /><b>Person</b></a><br />
      Title<br/>
      🔬 Research Interets</br>
      👩‍💻 technical skills/research methods</br></br></br></td>
      <td align="center" width="250px"><a href="https://orcid.org/0000-0003-2320-0470"><img src="https://avatars.githubusercontent.com/u/47313528?v=4" width="200px;" alt="Wallis Lau"/><br /><b>Person</b></a><br />
      Title<br/>
      🔬 Research Interets</br>
      👩‍💻 technical skills/research methods</br></br></br></td>
    </tr>
  </tbody>
</table><table>
  <tbody>
  <h3><b>Monash</b></h3>
    <tr>
      <td align="center" width="250px"><a href="https://orcid.org/0000-0003-2320-0470"><img src="https://avatars.githubusercontent.com/u/47313528?v=4" width="200px;" alt="Wallis Lau"/><br /><b>Person</b></a><br />
      Title<br/>
      🔬 Research Interets</br>
      👩‍💻 technical skills/research methods</br></br></br></td>
      <td align="center" width="250px"><a href="https://orcid.org/0000-0003-2320-0470"><img src="https://avatars.githubusercontent.com/u/47313528?v=4" width="200px;" alt="Wallis Lau"/><br /><b>Person</b></a><br />
      Title<br/>
      🔬 Research Interets</br>
      👩‍💻 technical skills/research methods</br></br></br></td>
      <td align="center" width="250px"><a href="https://orcid.org/0000-0003-2320-0470"><img src="https://avatars.githubusercontent.com/u/47313528?v=4" width="200px;" alt="Wallis Lau"/><br /><b>Person</b></a><br />
      Title<br/>
      🔬 Research Interets</br>
      👩‍💻 technical skills/research methods</br></br></br></td>
    </tr>
  </tbody>
</table>

---
## Data Sources

#### The Health Improvement Network (THIN)
Available at: UCL

THIN is a nationwide database that contains electronic primary care records from UK general practices for 15 million individuals. THIN covers a 6% representative sample of the UK population. Multiple diagnoses and lifestyle variables recorded in THIN database, including cardiovascular diseases, diabetes, obseity and smoking, have been used and validated for pharmacoepidemiological research. THIN is subject to the UK Data Protection Act 2018 and EU General Data Protection Regulation (GDPR). Data obtained have been anonymised and consent was previously collected.

Description taken from: </br>
Ilomäki, J., Bell, J.S., Chan, A.Y.L. et al. Application of Healthcare ‘Big Data’ in CNS Drug Research: The Example of the Neurological and mental health Global Epidemiology Network (NeuroGEN). CNS Drugs 34, 897–913 (2020). [https://doi.org/10.1007/s40263-020-00742-4](https://doi.org/10.1007/s40263-020-00742-4)

#### Clinical Practice Research Datalink (CPRD) GOLD
Available at: UCL

CPRD GOLD is a database of anonymised longitudinal routinely-collected electronic health records from UK primary care practices that use the Vision software. It contains demographic information, drug exposure, diagnoses, symptoms, laboratory tests, vaccination history, and referrals to hospital and specialist care. As of March 2023, there were over 21 million acceptable patients in the database. CPRD databases can be linked with other databases, including death registrations from the Office for National Statistics, various metrics for deprivation, Hospital Episode Statistics, and cancer registries. Data in CPRD GOLD are coded using READ codes. CPRD databases are representative of the national population. CPRD GOLD can be combined with CPRD Aurum.

The data specification is available [here.](https://cprd.com/sites/default/files/2022-02/CPRD%20GOLD%20Full%20Data%20Specification%20v2.5.pdf)

Herrett E, Gallagher AM, Bhaskaran K, Forbes H, Mathur R, van Staa T, Smeeth L. Data Resource Profile: Clinical Practice Research Datalink (CPRD). Int J Epidemiol. 2015 Jun 6;44(3):827–36. [https://doi.org/10.1093/ije/dyv098](https://doi.org/10.1093/ije/dyv098)

#### Clinical Practice Research Datalink (CPRD) Aurum
Available at: UCL

CPRD GOLD is a database of anonymised longitudinal routinely-collected electronic health records from UK primary care practices that use the EMIS Web software. As of September 2018, CPRD Aurum included 19 million patients, including 7 million who were alive and contributing to the database, and represented 13% of the population of England. Like CPRD GOLD, CPRD Aurum is representative of the national population and can be linked with other databases. Data in CPRD Aurum are coded using the SNOMED coding system.

The data specification is available [here.](https://cprd.com/sites/default/files/2023-04/CPRD%20Aurum%20Data%20Specification%20v2.9.pdf)

Wolf A, Dedman D, Campbell J, Booth H, Lunn D, Chapman J, Myles P. Data resource profile: Clinical Practice Research Datalink (CPRD) Aurum. Int J Epidemiol. 2019 Mar 11. pii: dyz034. [https://doi.org/10.1093/ije/dyz034](https://doi.org/10.1093/ije/dyz034)

####  Australian Pharmaceutical Benefits Scheme (PBS) Data
Available at: Monash

Australian Pharmaceuitcal Benefits Scheme data covers a random 10% of the Australian population (approximately 2.5 million people).

Details about the data source are available [here.](https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-015-1616-8)

Mellish, L., Karanges, E.A., Litchfield, M.J. et al. The Australian Pharmaceutical Benefits Scheme data collection: a practical guide for researchers. BMC Res Notes 8, 634 (2015). https://doi.org/10.1186/s13104-015-1616-8

#### Linked Victorian Primary Care and Hospital Data
Available at: Monash

The Monash team has access to linked medication, primary care, and hospital records for more than 400,000 residents of Victoria over the age of 30 from 2012 to 2018.

#### Sample of Medicare
Available at: UNC

UNC have access to a 20% sample of the US Medicare claims database from 2007 to 2019. Medicare is nationally representative of older adults in the US. The data includes information on diganosis, procedures, prescription refill records, both inpatient and outpatient services, and demographic information. Use of the data is readily-available when working with UNC-affiliated researchers, for a fee.

---
## 🎯 Training

#### <b>Statistics</b>
- [Statistics for Health Data Science by LSHTM](https://lshtm-hds.github.io/Content-2021/00.%20Welcome.html)
- [Medical Statistics at a Glane](https://www.cmua.nl/Cmua/Wetenschap_files/Medical%20Statistics%20at%20a%20Glance%202nd%20Ed.pdf)

#### <b>R</b>
-  [R for Epidemiology](https://epirhandbook.com/en/)
-  [R for Data Science](https://r4ds.had.co.nz/) - focuses on Tidyverse
-  [Mastering Shiny](https://mastering-shiny.org/basic-app.html)
-  [An Introduction to Machine Learning with R](https://lgatto.github.io/IntroMachineLearningWithR/an-introduction-to-machine-learning-with-r.html)

#### <b>Epidemiology</b>
- [Causal Inference: What If](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)
- [Basic Epidemiology, WHO](http://apps.who.int/iris/bitstream/handle/10665/43541/9241547073_eng.pdf)

---
## 📫 Contact


For any organisation related queries or concerns, you can directly reach out to Olivia Bryant by emailing [olivia.bryant.22@ucl.ac.uk](mailto:olivia.bryant.22@ucl.ac.uk).

♻️ License
---

This work is licensed under the MIT license (code) and Creative Commons Attribution 4.0 International license (for documentation).
You are free to share and adapt the material for any purpose, even commercially,
as long as you provide attribution (give appropriate credit, provide a link to the license,
and indicate if changes were made) in any reasonable manner, but not in any way that suggests the
licensor endorses you or your use, and with no additional restrictions.
