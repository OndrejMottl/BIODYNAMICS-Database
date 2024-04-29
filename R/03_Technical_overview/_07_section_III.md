# Section III: Assembly details of VegVault 1.0.0


The **VegVault** version **1.0.0** has been assembled from other
publicly available databases.

## Assembly process

Here is a general visualisation of the assembly process:

<img src="DB_assembly_visualisation/assembly_viz_01.png"
style="width:100.0%" data-fig-align="center" />

**Figure legend**:

1.  **[Neotoma Paleoecology Database](https://www.neotomadb.org/)** -
    open, community-curated data and services for paleoecological and
    paleoenvironmental data
    - source of fossil pollen data
2.  **[sPlotOpen](https://idiv-biodiversity.de/en/splot/splotopen.html)** -
    The open-access version of sPlot
    - source of current vegetation plot data
3.  **[Botanical Information and Ecology
    Network](https://bien.nceas.ucsb.edu/bien/)** - global patterns of
    plot inventories and surveys
    - source of current vegetation plot and vegetation trait data
4.  **[TRY Plant Trait
    Database](https://www.try-db.org/TryWeb/Home.php)** - open access
    plant trait data
    - source of vegetation trait data
5.  **[Climatologies at High resolution for the Earth’s Land Surface
    Area](https://chelsa-climate.org/)** - Long-term, transient modern-
    and paleo-climate data
    - source of abiotic data
6.  **[World Soil Information
    Service](https://www.isric.org/explore/wosis)** - harmonised soil
    profile database
    - source of abiotic data
7.  **[FOSSILPOL](https://hope-uib-bio.github.io/FOSSILPOL-website/)** -
    The workflow that aims to process and standardise global
    palaeoecological pollen data for macroecological studies
    - a method to obtain and process fossil pollen data
8.  **[RBIEN R package](https://github.com/bmaitner/RBIEN)** - Tools for
    accessing the BIEN database
    - a method to obtain current vegetation plot data
9.  **[VegVault-FOSSILPOL GitHub
    repo](https://github.com/OndrejMottl/VegVault-FOSSILPOL/tree/v1.0.0)**
    - a Tag (v1.0.0) to obtain and process fossil pollen data
10. **[VegVault-Vegetation_data GitHub
    repo](https://github.com/OndrejMottl/VegVault-Vegetation_data/tree/v1.0.0)**
    - a Tag (v1.0.0) to process current vegetation plot data
11. **[VegVault-Trait_data GitHub
    repo](https://github.com/OndrejMottl/VegVault-Trait_data/tree/v1.0.0)**
    - a Tag (v1.0.0) to process vegetation trait data
12. **[VegVault-abiotic_data GitHub
    repo](https://github.com/OndrejMottl/VegVault-abiotic_data/tree/v1.0.0)**
    - a Tag (v1.0.0) to process abiotic data
13. **[VegVault GitHub repo](https://github.com/OndrejMottl/VegVault)**
    - a Tag (v1.0.0) to transfer the data into the SQLite database
14. **VegVault** - SQLite database (v1.0.0)

### Note on GitHub Tags

*…Tags are ref’s that point to specific points in Git history. Tagging
is generally used to capture a point in history…*

Here, the Tags have been used to ensure reproducibility of this version
of \*\*VegVault\*. GitHub repo can change but the specific Tag used here
(and also used in the code to source the data) ensure the transparency
of the state of the database.
