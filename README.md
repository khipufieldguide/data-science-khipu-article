<a name="readme-top"></a>

<br />
<div align="center">

  <h3 align="center">How Can Data Science Contribute to Understanding the Khipu Code?<br/><i>by Manuel Medrano and Ashok Khosla</i></h3>

  <p align="center">
    Support Documentation, Data, and Code
  </p>

  <a href="https://doi.org/10.5281/zenodo.8125718"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.8125718.svg" alt="DOI"></a>

</div>

[![][fieldguide_image]](https://www.khipufieldguide.com)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-this-repository">About This Repository</a> </li>
    <li><a href="#prerequisites">Prerequisites</a></li></li>
    <li><a href="#data">Data</a></li>
    <li><a href="#source">Source</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About This Repository:
This repository contains companion data and code for the article ***How Can Data Science Contribute to Understanding the Khipu Code?*** by Manuel Medrano and Ashok Khosla. All of this companion information is presented in more detail and with additional analyses on Khosla's companion website [www.khipufieldguide.com](https://www.khipufieldguide.com/notebook/index.html).

## Prerequisites
Data are stored in three formats. Khipus are stored as KhipuFieldGuide Excel Spreadsheets, and as SQL database compatible with the Open Khipu Repository Format. Generated data is stored as CSV (comma-separated values) text files and can be read by Excel, R, Python or any spreadsheet aware software. The SQL file is a SQL "dump" created by the open-source MySQL package MariaDB.

## Data
The data folder contains:

* A [**KFG_DB_Excel**](./data/KFG_DB_Excel) Directory of the 650 khipus used in the Khipu Field Guide (KFG) to construct the article. More information on the creation of the KFG database can be viewed at the [KFG Codebook](https://www.khipufieldguide.com/databook/Database_Build.html)
* A [**KFG_DB_SQL**](./data/KFG_DB.SQL) Directory of the 650 khipus used in the Khipu Field Guide (KFG) to construct the article. More information on the creation of the KFG database can be viewed at the [KFG Codebook](https://www.khipufieldguide.com/databook/Database_Build.html)
* An [**Ascher Sum Relations**](./data/ascher_sum_relations) Directory containing Ascher summation relations for all the Ascher summation relations in the 650 khipu, as well as a [summary file](./data/ascher_sum/relations/ascher_sum_relationships.csv).
  These files generally come in pairs (mostly, but not always) - a summary file, showing the number of sums/relations for each khipu, and a more detailed relations file, containing each summation and its location and other useful information.
  More detailed viewing and analyses of these relationships is available at https://www.khipufieldguide.com/notebook/analyses/ascher_sums_overview.html
* A [**Khipu Summary**](./data/khipu_summary.csv) CSV file, containing summary information about every khipu in the KFG.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Source
Expository source code, excerpted from Khosla's Khipu Field Guide, is provided for the following sections of the article. Each page is an HTML page, created using Jupyter and Quarto, which shows both explanatory text, and code.

The following pages have been created, roughly in the order presented in the article:

  1. [Overall Khipu Database Metrics](./source/01_general_khipu_info.html)
  2. [Ascher Summation Relationships](./source/02_ascher_sum_relationships.html)
  3. [Top Cords](./source/03_top_cord_studies.html)
  4. [Reconstructing Broken Khipus](./source/04_reconstructing_broken_khipus.html)
  5. [Summation Handedness](./source/05_summation_handedness.html)
  6. [Identifying Khipu Grammars](./source/06_khipu_grammars.html)
  7. [Discussion](./source/07_discussion.html)

  <p align="right">(<a href="#readme-top">back to top</a>)</p>

## License
Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact
Manuel Medrano - mmedrano@g.harvard.edu<br/>
Ashok Khosla - ashok@khosla.com

## Project Link:
[https://www.khipufieldguide.com](https://www.khipufieldguide.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[fieldguide_image]: https://www.khipufieldguide.com/sketchbook/images/khipu/UR231_wide.jpg
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
