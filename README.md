# DataEx DWE 2023 Challenge  ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
(Developed on March 2nd, 2023.) <br/>
This is a DW developed to a Challenge for the bootcamp Data Women Engineers 2023 from DataEx in partnership with Microsoft.

<br/>

<b>Build with:</b> <br/><br/>
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
<br/>
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
<br/>
T-SQL

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Project Composition](#project-composition)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

<br />

## Overview

### <b id="the-challenge">The challenge</b>
<br/>
Analyze the execution of Government expenses, data source from the Transparency Portal, referring to data from Jan/22 to Mar/22.
<br/>
At the end of the challenge, you will have to send the data dictionary, the dimensional diagram of the applied modeling and the jupyter notebook.
<br/><br/>

### <b id="project-composition">Project Composition</b>
1- DW_09_CHALLENGE_DICIONARIO_DADOS.pdf
<br/>
A document that contains metaata about the data within a database. It serves as a comprehensive reference guide that provides detailed information about the structure, organization and meaning of the data elements stored int he system.
<br/><br/>

2- DW_09_CHALLENGE_DIAGRAMA.pdf
<br/>
Dimensional diagram used to organize and represent data for analytics and reporting purposes.
<br/><br/>

3- DESAFIO_ALUNA09.ipynb
<br/>
Jupyter notebook containing the solution to the challenge.
<br/>
Developed the process of extracting raw data from sources, transforming it into a usable format, including cleaning, filtering, aggregating the data and loading it into a destination where it can be accessed and analyzed effectively.
<br/><br/>

### <b id="links">Links</b>
- [YouTube Link](https://www.youtube.com/watch?v=77hcDTVg7mI&ab_channel=BiancaEmi)

## <b id="my-process">My Process</b>

### <b id="built-with">Built with</b>
- The project was developed using the Azure environment and T-SQL im Jupyter Notebook
- A log table was created to assist in the development process and store error messages incase of failure.
<br/>

### <b id="what-i-learned">What I learned</b>
- This project was my first endeavor in the field of data engineering, and the entire ETL process was a completely new experience for me.
- With the correction, I understood how the time dimension works and realized that I failed to apply it in this project.
- In the table "UnidadeGestora", there were records where the same code had different names. To handle this, I created a temporary table, grouping the codes into partitions and sorting them alphabetically. Then, I selected the first record from each partition.
<br/><br/>

## Author
<div sytle="display: inline-block;">
    <figure>
        <a href="https://github.com/bemibrando" target="_blank">
            <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/102377919?v=4" width="100px" alt="Bianca Emi profile's photo"> <br />
            <sub style="text-align: center; font-size: 1.4em;"><b>Bianca Emi</b></sub>
        </a>
    </figure>
    <p>Made with ♥ by <a href="https://github.com/bemibrando" target="_blank">Bianca Emi</a> 👋 Get in touch!</p>
    <div align="start">
        <a href="https://www.linkedin.com/in/bianca-emi/" target="_blank">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
        </a>   
        <a href="https://twitter.com/bemibrando" target="_blank">
            <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">
        </a>   
        <a href="mailto: bemi.brando@outlook.com">
            <img src="https://img.shields.io/badge/bemi.brando@outlook.com-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white">
        </a><br/>
    </div>
</div>
<br/><br/>

## Acknowledgments
- [DataEx](https://www.dataex.com.br/en/) is a consolidated company which offers consulting services in Power BI, Business Intelligence, Artificial Intelligence, Analytics, Cloud Transformation Journey, Data Management and App Development, for companies.
- [Andre Rosa](https://www.linkedin.com/in/andre-rosa77/) Bootcamp instructor, a Brazilian professional with over 20 years of experience in Information Technology.
- [Microsoft](https://www.microsoft.com/pt-br) Bootcamp supporter. Microsoft is an American multinational corporation and technology company
