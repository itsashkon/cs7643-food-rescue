# Food Rescue Through Computer Vision

Food rescue project to combat food waste and expedite donation center intake.

## Team
- Ash Rahbari
- Arjot Rai

## Project Summary
Food waste and food insecurity are two of the largest societal challenges, affecting both underserved communities and demographically advanced countries alike. This project validates whether deep learning based computer vision models can automatically identify food items from images. We compare convolutional neural networks and vision transformers to evaluate their effectiveness on food classification.

## Approach
Core implementation focuses on food classification using Food-101 (101 categories, 101,000 images). We fine-tune pretrained ResNet18 (CNN) and ViT-B/16 (vision transformer) models, comparing performance across different amounts of training data (10%, 50%, 100% of the dataset) to evaluate data efficiency and generalization.

## Datasets
- Food-101: https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/

## Repo Structure
- `data/` - Food-101 downloads (gitignored)
- `notebooks/` - Colab notebooks for exploration and training
- `src/` - reusable Python code (data loading, splits, model setup)
- `results/` - metrics CSVs and saved plots
- `report/` - LaTeX report files

## How to Run
(to be filled in as pipeline is built)
