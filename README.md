# AMS 2026 Student Conference: Open Science

<img src="thumbnails/thumbnail.png" alt="thumbnail" width="300"/>

This repository includes materials presented during the **Open Science Best Practices** presentation during the [2026 AMS Student Conference](https://annual.ametsoc.org/2026/program-events/conferences-and-symposia/25th-annual-student-conference/)

## Contents

1. [Link to slide deck presentation](https://docs.google.com/presentation/d/1GtGkTsKZXVvnFl-zNbmwVxQMBIGWvxlK/edit?usp=drive_link&ouid=100480712069334762220&rtpof=true&sd=true)

1. [An example of a reproducible, interactive research paper from a graduate-level atmospheric science class.](https://www.atmos.albany.edu/facstaff/ktyle/AMS2026_OpenSci/)

## Authors

[Kevin Tyle](https://github.com/ktyle), [Max Grover](https://github.com/mgrover1), Doug Schuster

### Contributors

[Kristina Vrouwenvelder](https://orcid.org/0000-0002-5862-2502)
[Evan Belkin](https://orcid.org/0009-0003-5740-1155)
### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the repository:

   ```bash
    git clone https://github.com/ktyle/AMS2026_OpenScience
   ```

1. Move into the `AMS2026_OpenScience` directory
   ```bash
   cd AMS2026_OpenScience
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate AMS2026_OpenScience
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
