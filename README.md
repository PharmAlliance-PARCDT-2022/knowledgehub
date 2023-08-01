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
## 🎯 Training

#### <b>Statistics</b>
- [Statistics for Health Data Science by LSHTM](https://lshtm-hds.github.io/Content-2021/00.%20Welcome.html)
- [Medical Statistics at a Glane](https://www.cmua.nl/Cmua/Wetenschap_files/Medical%20Statistics%20at%20a%20Glance%202nd%20Ed.pdf)

#### <b>R</b>
-  [R for Epidemiology](https://epirhandbook.com/en/)
-  [R for Data Science](https://r4ds.had.co.nz/) - focuses on Tidyverse
-  [Mastering Shiny](https://mastering-shiny.org/basic-app.html)

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
