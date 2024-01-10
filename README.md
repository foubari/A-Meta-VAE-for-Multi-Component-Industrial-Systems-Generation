# A Meta-VAE for Multi-Component Industrial Systems Generation

This repository contains the code and data related to the paper "A Meta-VAE for Multi-Component Industrial Systems Generation".

## Repository Structure

- `models/`: Contains the saved model architectures in scripts.
- `dataset/`: Contains the dataset used in the experiments and the datasets used in training.
- `saves/` Contains four subfolders named after the model types (e.g., meta_vae, vanilla_vae...), each containing five instances of the same model, trained independently with identical hyperparameters and PyTorch's default initialization for increased robustness.
- `notebooks/`: Contains two Jupyter notebooks:
    - `dataset_generation.ipynb`: Used to generate and save the dataset explained in the paper.
    - `experiments.ipynb`: Used to load the models, plot different generations, distributions, error histograms as explained in the paper.

## Getting Started

1. Clone this repository:
```
git clone https://github.com/foubari/A-Meta-VAE-for-Multi-Component-Industrial-Systems-Generation.git
cd A-Meta-VAE-for-Multi-Component-Industrial-Systems-Generation
```

2. Create a virtual environment and install the required packages:
```
python -m venv venv
source venv/bin/activate # On Windows, use venv\Scripts\activate
pip install -r requirements.txt
```

3. Navigate to the `notebooks` folder and run the Jupyter notebooks:

To generate the datasets, open and run the "dataset_generation.ipynb" notebook. To generate the experiment visuals, open and run the "experiments.ipynb" notebook. Please note that the figures are displayed within the notebooks.

## Dependencies

```
The following libraries are required to run the code:

- numpy==1.24.2
- pandas==1.5.3
- torch==1.13.1
- tqdm==4.65.0
- matplotlib==3.7.1
- scipy==1.10.0
```

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License - see the [LICENSE.md](LICENSE.md) file for details.

## Citation

If you use this code or data in your research, please cite:

Oubari, F., Meunier, R., Décatoire, R., & Mougeot, M. (2024). A Meta-VAE for Multi-Component Industrial Systems Generation. In Proceedings of the Computing Conference 2024 (Springer's Lecture Notes in Networks and Systems). [Volume], [Page numbers]. DOI/URL (to be updated)
