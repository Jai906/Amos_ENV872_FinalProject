# Amos_ENV872_FinalProject

Final project for Spring 2023 environmental data analytics course

```         
# <NanoInformatics Knowledge Commons (NIKC) Database>

## Summary

This repository contains all files pertaining to analysis of the NIKC database relating to the 2023 Environmental Data Analytics course.

## Investigators

Jaleesia Amos, Duke University, Pratt School of Engineering, jaleesia.amos@duke.edu, Graduate Student and Database Curator

## Keywords

<Nanomaterial, Exposure, Toxicity, Nanoinformatics>

## Database Information

Original publication on database: Amos, J. D. et al. The NanoInformatics Knowledge Commons: Capturing spatial and temporal nanomaterial transformations in diverse systems. NanoImpact 23, 100331 (2021).

The following was taken from the abstract of the previously mentioned publication.

  'The empirical necessity for integrating informatics throughout the experimental process has become a focal point of the nano-community as we work in parallel to converge efforts for making nano-data reproducible and accessible. The NanoInformatics Knowledge Commons (NIKC) Database was designed to capture the complex relationship between nanomaterials and their environments over time in the concept of an ‘Instance’. Our Instance Organizational Structure (IOS) was built to record metadata on nanomaterial transformations in an organizational structure permitting readily accessible data for broader scientific inquiry. By transforming published and on-going data into the IOS we are able to tell the full transformational journey of a nanomaterial within its experimental life cycle. The IOS structure has prepared curated data to be fully analyzed to uncover relationships between observable phenomenon and medium or nanomaterial characteristics. Essential to building the NIKC database and associated applications was incorporating the researcher’s needs into every level of development.  We started by centering the research question, the query, and the necessary data needed to support the question and query. The process used to create nanoinformatic tools informs usability and analytical capability. In this paper we present the NIKC database, our developmental process, and its curated contents.'


## Folder structure, file formats, and naming conventions 

There are three folders found in the repository:

Data - Contains the processed (nikc_processed_2) and raw data files (nikc_raw_20200326.csv). Note the data folder contains the subfolders 'Processed' and 'Raw'.

Figure - NIKC curation structure database; two figures from the original publication can be found here as jpeg files.

Paper - Scratch work for analysis 

## Metadata

The following was taken from the Amos et. al. publication.

  'The measurement tab is where literature data and raw data are deconstructed and reorganized into the NIKC-IOS. Data and metadata are entered into the measurement tab, connecting the metadata to the data point that it describes. We list the DOI or dataset ID that the data entry belongs to. Each new row entry into the Excel spreadsheet is given a measurement ID. The data is then classified into one of five categories in the MeasurementType column. Data entries are linked together to tell the journey of the nanomaterial through the ReferencingID column.   
    We are able to follow the timeline of measurements, endpoints, and characterizations by recording how much time has passed since the last related data entry, and when possible, the date and time a measurement is taken. The parameter column is used to name the data entry. Who reported or measured the data entry is recorded to establish trust in the data, whether defining characteristics were measured by the experimenters or the manufacturer. 
    We classify the format of the data entry as numerical or text. If the data entry is a textual description, we enter the text in the parameterText column.  If the data entry is numerical, we then record and statistically describe the numerical data.  Our endeavor to build and grow our database is through collaborations with partners, so we record which group or organization owns the data being curated.  We link every data entry with its measurement protocol and instrument.'
>

## Scripts and code

All data was analysis was completed in R.

## Quality assurance/quality control

The following was taken from the Amos et. al. publication.

  'Researchers and curators work together to determine when literature curation is complete, and is guided by the experimental questions and needs of researchers based on a fit-for-purpose model.  Raw literature curation is reserved to CEINT and CEINT collaborators who agree on parameters surrounding data quality.  ISA-TAB-nano48 is used as a guidepost for determining what parameters should be curated to ensure reproducibility for both literature and raw curation. One of our purposes for curating is for data analysis through custom-built apps such as the Nano Product Hazard and Exposure Risk Assessment Tool (NanoPHEAT) developed for the Consumer Product Safety Commission and Army Corps of Engineers. Curating for data analysis according to NanoPHEAT requirements, has focused our efforts to capturing quantitative data from literature sources.
  Many published studies of nanomaterials inadequately characterize either the nanomaterial or the medium, or in some cases, both. To ensure high-quality data from literature sources, we curate papers with nanomaterial characterizations performed by the researchers themselves or their partners, whether the nanomaterial is purchased or synthesized in-house.  We also look for papers that characterize the exposed medium of the nanomaterial, whether that be a cell culture medium or an organism.  Many published studies of nanomaterials inadequately characterize either the nanomaterial or the medium, or in some cases, both. There are currently no standards that have been adopted and required by journals regarding characterization of the nanomaterial or the medium.
  We verify that the nanomaterial’s core and surface compositions are provided and other primary characterizations such as the size, surface charge, and hydrodynamic size. For living organisms, we minimally curate the class, Latin name, and species. For cell lines, we minimally curate the class, Latin name, species, and cell line.'
```
