This site contains course materials for SISG Module QG4: WGS Data Analysis, June 10-12, 2026. 

- **Instructors:** [Laura Raffield](https://www.med.unc.edu/genetics/directory/laura-raffield-phd/) and [Matthew Conomos](https://www.biostat.washington.edu/people/matt-conomos)

## Course Description
This module will provide an introduction to analyzing genotype data generated from whole genome sequencing (WGS). It will focus on extensions of standard GWAS analyses (e.g. rare-variant association tests) and “post-GWAS” follow-up analyses (e.g. conditional analysis, fine-mapping), and how WGS may improve results or be best utilized for these analyses; methods that incorporate variant annotation information will be highlighted.

Methods and examples will be informed by the instructors’ experience in large human genetics consortia (e.g. TOPMed), and, therefore, will focus on analyzing human data, but may be applicable/extendable to other organisms. A basic introduction to cloud computing will be provided, and students will perform hands-on exercises on a genomic analysis cloud platform.

### Learning Objectives
After attending this module, participants will be able to: 
1. Understand how to perform association analyses for rare variants measured in WGS data using aggregate tests
2. Access variant annotation resources and understand how to incorporate annotation information into analyses to improve power and inform results
3. Understand the theory of, and how and when to perform, various “post-GWAS” follow-up analyses 
4. Leverage multi-ancestry WGS data
5. Appreciate the utility of existing genomic analysis cloud platforms and get hands-on experience with cloud computing on one of these platforms

## Course Format

### Lectures
Course material will be presented through lectures. Slides for lectures are linked in the schedule below.

### Tutorials
Many of the lectures will be followed with hands-on tutorials/exercises. Students are encouraged to work through the tutorials together. Afterwards, the instructors will walk through the tutorials and lead a discussion.

To run the tutorials, log into [NHLBI BioData Catalyst powered by Seven Bridges](https://platform.sb.biodatacatalyst.nhlbi.nih.gov) with your username and password -- we will use this platform for live demonstrations during the course.

#### Setting up a BioData Catalyst account
If you are affiliated with a US-based institution, you will log into the platform using eRA Commons credentials. [eRA Commons](https://www.era.nih.gov/register-accounts/create-and-edit-an-account.htm) is the system used by NIH to administer grants, and it also serves as a mechanism for authenticating researchers to work with controlled access data. To create a BioData Catalyst account, please follow steps on the page [Sign up for BioData Catalyst Powered by Seven Bridges](https://sb-biodatacatalyst.readme.io/docs/sign-up-biodata-catalyst-powered-by-seven-bridges) in the documentation. 

If you are not affiliated with a US institution that is already registered in eRA Commons, or you do not already have an eRA Commons ID in advance of the workshop, you will still be able to fully participate in the module exercises. Please see this [document](https://drive.google.com/file/d/1yylewFR4jQoTKexm-0_HQR-KdUWvL7pN/view) for instructions. 

After you create an account, we will add you to the SISG 2025 WGS Analysis Module course project.  

- You will retain access to the Seven Bridges platform, including the SISG course project with all of the course materials even after the course ends. The SISG25 Workshop billing group will remain available to you for a short period of time, after which you will need to set up another payment method to run analyses. You can [request pilot cloud credits](https://biodatacatalyst.nhlbi.nih.gov/resources/cloud-credits) ($500 worth) from BioData Catalyst. Additionally, there is guidance available for [writing BioData Catalyst cloud costs into your grant proposal budget](https://bdcatalyst.gitbook.io/biodata-catalyst-documentation/written-documentation/getting-started/writing-biodata-catalyst-into-a-grant-proposal). 

All of the R code and data can also be downloaded from the [github repository](https://github.com/UW-GAC/SISG_WGS_Data_Analysis) from which the site is built and run on your local machine. Download the complete workshop data and tutorials: [https://github.com/UW-GAC/SISG_WGS_Data_Analysis/archive/main.zip](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/archive/main.zip)


## Course Schedule and Materials

We strongly encourage everyone to ask questions and engage in the discussion in class. Therefore, the exact timing of the schedule is subject to change, depending on the amount of time we end up spending on each topic. <br>
- Coffee breaks are daily from 10:00am-10:30am and 3:00pm-3:30pm
- Lunch break is daily from 12:00pm-1:30pm.

**Wednesday (half-day)**

| Topic | Materials |
| --- | --- |
| Introduction | [Slides](https://docs.google.com/presentation/d/1lJYW5cpLUHwPqaXj1a0m0zlC1hyhlTMzgfttjYIC420/preview?slide=id.p) |
| Intro to Cloud Computing for WGS Data Analysis | [Lecture Slides](https://docs.google.com/presentation/d/1G-0eZca5qL7Aa3JbjdYsBm8cQdafyvwZC7kobDPKd5A/preview?slide=id.p) |
| Intro to GDS Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/01_gds_intro.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/01_gds_intro.html) |
| GWAS Crash Course | [Lecture Slides](https://drive.google.com/file/d/1jIAraJ2g4B9iMaw4ADH_lerWic11fxCd/view?usp=drive_link) |
| GWAS Tutorial | [Slides](https://docs.google.com/presentation/d/1pVNjQOnLc_NAdCK7A6EWAphiPL2j9ghV34GuENn-VlY/preview?slide=id.g3618502b3b6_1_29) \| [.Rmd](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/02_GWAS.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/02_GWAS.html) |
| _Extra_: Population Structure and Relatedness Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/02.1_pop_structure_relatedness.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/02.1_pop_structure_relatedness.html)
| _Extra_: GWAS: Advanced Model Extenstions Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/02.2_advanced_GWAS.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/02.2_advanced_GWAS.html) |
| _Extra_: GENESIS Model Explorer Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/02.3_GENESIS_model_explorer.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/02.3_GENESIS_model_explorer.html)

**Thursday**

| Topic | Materials |
| --- | --- |
| Leveraging Multi-Ancestry Data | [Lecture Slides](https://drive.google.com/file/d/1aYCYK0gFjNJuZfjq8rOWsNvl2CFV_tsu/view?usp=drive_link) |
| LD Exercise | [.pdf](https://drive.google.com/file/d/1ezSde3iCuXHgyHxty7QLlgZOteuKsoUk/view?usp=drive_link) \| [_NEJM_ 2020](https://drive.google.com/file/d/1P36sRyq1yXVfdfg2DR309ODGYlBRT_t-/view?usp=drive_link) \| [_Nature_ 2021](https://drive.google.com/file/d/1K8JTEv9_wublRO_yWeTOJ_2Lim2auKKP/view?usp=drive_link)  \| [KEY](https://drive.google.com/file/d/1t8rfyVAtiivfQ8aLL0oxMi0-3enyzNfA/view?usp=drive_link) |
| TOPMed Telomere Length Conditional Analysis | [Slides](https://docs.google.com/presentation/d/1XJAFuM5tFfX1EylWkUZwpt5Y4Wd6-df47I6golrek-s/preview?slide=id.g336ccf40533_0_0) |
| Locus Zoom and Conditional Analysis Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/03_conditional_analysis.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/03_conditional_analysis.html) |
| Variant Annotation | [Lecture Slides](https://drive.google.com/file/d/1gthJmVkpsh1ANaJH8xZoir7pqITKHRjo/view?usp=drive_link) |
| UCSC Genome Browser and FAVOR Tutorial | [.pdf](https://drive.google.com/file/d/1nHgPoWNFy8ok20mUO99boYSETCCf-ond/view?usp=drive_link) \| [chr16 SNPs to Annotate](https://drive.google.com/file/d/1kVf1Jj6tBPC24N19DRgSE5BVAQqj9FPX/view?usp=drive_link) \| [KEY](https://drive.google.com/file/d/1juKziK-PhKjvSyFjl_sajxILo6p-XYpi/view?usp=drive_link) \| [KEY chr16 SNPs custom track](https://drive.google.com/file/d/1FSjjkAmBjxcR77Uo7LToEhPpzQwrJmAY/view?usp=drive_link) |
| Annotation Explorer Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/04_annotation_explorer.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/04_annotation_explorer.html) |
| _5:00pm-6:00pm_: Tutorial Open Q&A Session | |

**Friday**

| Topic | Materials |
| --- | --- |
| Multi-Variant Association Tests | [Lecture Slides](https://drive.google.com/file/d/1Mtp4fpKEXl_U4OZP7oAQ8hKffLtzfs2-/view?usp=drive_link) | 
| Multi-Variant Association Tests Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/05_aggregate_tests.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/05_aggregate_tests.html) |
| STAAR | [Lecture Slides](https://drive.google.com/file/d/1hZ-WvuK5hJQO-JZR39ONGYAvIdkDTgoF/view?usp=drive_link) | 
| STAAR Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/06_STAAR.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_WGS_Data_Analysis/blob/main/06_STAAR.html) |
| Recent Findings and Resources for WGS Analysis | [Lecture Slides](https://drive.google.com/file/d/1RFvUVNFXIE3J1BtKUT6KpNORA09qhNGf/view?usp=drive_link) |
| Open Q&A | |

## R packages used

- [GENESIS](http://bioconductor.org/packages/release/bioc/html/GENESIS.html)
- [SeqArray](http://bioconductor.org/packages/release/bioc/html/SeqArray.html)
- [SeqVarTools](http://bioconductor.org/packages/release/bioc/html/SeqVarTools.html)
- [SNPRelate](http://bioconductor.org/packages/release/bioc/html/SNPRelate.html)
- [Biobase](https://bioconductor.org/packages/release/bioc/html/Biobase.html)
- [GenomicRanges](https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html)
- [GGally](https://cran.r-project.org/web/packages/GGally)


## Resources

A detailed tutorial and relevant R scripts for STAAR pipeline are available at [https://github.com/xihaoli/STAARpipeline-Tutorial](https://github.com/xihaoli/STAARpipeline-Tutorial).

If you are new to R, you might find the following material helpful:

- [Introduction to R](http://faculty.washington.edu/kenrice/rintro/) materials
- Graphics with [ggplot2](https://ggplot2.tidyverse.org/)
- Data manipulation with [dplyr](http://dplyr.tidyverse.org/)
