# wild_plant_crop_interface_review

The code is written by Alexey Mikaberidze, professor in plant diseases and crop protection at the University of Goettingen (alexey.mikaberidze@uni-goettingen.de)

The code supports the manuscript "The epidemiology of wild plant–crop interfaces: Integrating ecology, evolution, and management through modeling" by Del Ponte*, Mikaberidze*, Bebber, Halliday, Cunniffe (*equal contributions). Preprint available at https://doi.org/10.31220/agriRxiv.2025.0035 

## Reproducible environment

The figures were generated using:
- Python version recorded in `python_version.txt`
- Dependencies listed in `requirements.txt`

## To reproduce

Clone this repository and set up the environment:

    git clone git@github.com:mikalexey/wild_plant_crop_interface_review.git
    
    cd wild_plant_crop_interface_review
    python3 -m venv venv
    source venv/bin/activate     # On Linux or macOS
    # venv\Scripts\activate      # On Windows
    pip install -r requirements.txt

Then launch Jupyter Lab or Jupyter Notebook:

    jupyter lab
    # or
    jupyter notebook

and open `wild_crop_interface.ipynb`, run the entire notebook and
the figures will be generated in the subdirectory 'figures'.
