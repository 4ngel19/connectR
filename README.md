<!-- README.md is generated from README.Rmd. Please edit that file -->
<div style="display: flex; justify-content: space-between; align-items: center; width: 100%;">
  <img src="images/icono_connectR.png" width="130">
  <a href="https://chuchodc.github.io/ConnectR/README_ES">
    <img src="https://img.shields.io/badge/Ver%20en%20espa%C3%B1ol-%23FFFFFF?style=for-the-badge&logoColor=white&color=blue" alt="Ver en español">
  </a>
</div>

# **ConnectR** 

<br>

This is a software fully developed in R, which calculates indices proposed by [Sidor et al. (2013)](https://doi.org/10.1073/pnas.1302323110).

Such indexes include:<br>
**Biogeographic Connectedness**, **Network Cluserting**, **Average Ocurrences**, and **Average Endemics**.

The final user only needs to create the input file into the correct format, indicate
which index, if not all of them, will be calculated, and determine the number of
ages (number of pages) to assess. 

The software will obtain the desired index by each temporality at the time it also carries out 
parametric sampling of the indexes and plot them.
These calculations are complementary to complex network visualizations created either 
in [Gephi](https://gephi.org/) or [igraph R package](https://igraph.org/).

These kind of analyses are relevant since they allow us perform biogeographical studies on fossil
fauna based exclusively on geographical ocurrences. Besides documentation, [ConnectR](https://github.com/ChuchoDC/ConnectR) 
includes an empirical dataset of Cretaceous fossil fishes, Aulopiformes, 
a worldwide distributed group with a pretty well-known and numerous fossil record. 


In order for this library to work correctly, the dependencies required are:<br>
`readxl`<br>
`dplyr` <br>
`ggplot2`<br>
`gridExtra`<br>
`scales`<br>
`pbapply`<br>

## Content

- [Installation guide and requirements](Installation_Dependencies.md)
- [Documentation](Documentation.md)
- [Example of execution]() 


**Important to notice**<br>
The software is in its final stage of development. 
Authors are testing it with empirical and simulated datasets to ensure its correct operation.   

<br><br>
## **Authors**:
[Angel Angeles Cortés](https://github.com/4ngel19)  
email:
<a href="mailto:angel_10@ciencias.unam.mx" class="email">angel_10@ciencias.unam.mx</a>

[Dr. Jesús Alberto Díaz-Cruz](https://github.com/ChuchoDC)  
email:
<a href="mailto:vertebrata.j@ciencias.unam.mx" class="email">vertebrata.j@ciencias.unam.mx</a>

