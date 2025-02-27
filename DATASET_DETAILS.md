# Flower Dataset Overview

The **Flowers dataset** from Kaggle is used in this project. It contains labeled images of flowers along with textual descriptions. The dataset is split into three subsets: training, validation, and testing.

## Dataset Split

The dataset is divided into three subsets, each serving different purposes:

| Subset     | Number of Items |
|------------|-----------------|
| Train      | 29,390          |
| Validation | 5,780           |
| Test       | 5,775           |

## Data Format

Each data point in the dataset consists of the following components:

- **Class Label**: A unique identifier for the flower class.  
  Example: `class_00077`

- **Image**: A corresponding flower image.  
  Example: `image_00001`

- **Text Description**: A textual description of the flower's features.  
  Example: "Prominent purple stigma, petals are white in color."

- **Embeddings**: Precomputed embeddings from the text descriptions.  
  Example (first 10 values):  
  `[0.1023, -0.0869, 0.0341, -0.0205, 0.1594, -0.0332, 0.0372, 0.2376, -0.0508, 0.1323]`

## Usage

Different dataset sizes were used for various models based on computational constraints and the specific needs of each approach. Details of the models and their specific dataset usage can be found in the respective sections of the documentation.

## Citation

If you use this dataset in your work, please cite the following:

```bibtex
@misc{flowers-dataset,
  author = {K. Mahesh},
  title = {FlowersHD5Dataset},
  year = {2021},
  howpublished = {\url{https://www.kaggle.com/datasets/kmahesh541/flowershd5dataset}},
}
