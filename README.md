# ESG-dataset Background
Comprehensive ESG dataset from Chinese listed companies' reports (listed companies from 2008 to 2022?). ESG reports serve as an essential platform for companies to disclose their economic, environmental, and social impacts, reflecting their contributions to sustainable development goals. With the increasing demand for corporate transparency, ethical business practices, and sustainable development, ESG reports have gained significant attention from both academia and practitioners.

# Dataset Content

The dataset consists of two core parts: the topic label dataset and the quality label dataset. Specifically:

Annotated Dataset: A total of 8,467 sentences were annotated, each with two labels: topic and quality.
Topic Labels: Classified into 37 different categories, covering various aspects such as climate change, employee health and safety, community engagement, and more.
Quality Labels: Divided into three categories: "Quantitative Text," "Qualitative Text," and "Irrelevant Text."

# Dataset Purpose

The primary purpose of this dataset is to evaluate the completeness of ESG reports. Currently, it is mainly used for ESG classification to measure the completeness of ESG reports. However, this dataset has a broad potential for various other purposes, such as:

- Automated generation and optimization of ESG reports
- Content analysis and trend prediction of ESG reports
- Development of decision support systems for investment
- Evaluation of corporate social responsibility (CSR) strategies

# ESG Multiclass Dataset

This repository contains a comprehensive dataset for Environmental, Social, and Governance (ESG) multiclass classification tasks. The dataset is designed for training and evaluating classification models in the field of ESG analysis.

## Dataset Description

The ESG dataset includes the following categories:

1. **Environmental (E):** Data related to environmental factors such as carbon footprint, resource usage, and waste management.
2. **Social (S):** Data covering social aspects like labor practices, human rights, and community engagement.
3. **Governance (G):** Data on governance issues such as corporate policies, board diversity, and executive compensation.

Each category is further divided into multiple subcategories, providing a detailed and nuanced dataset for classification purposes.

## File Structure

- **data/**
  - `environmental.csv` - Contains environmental data points and labels.
  - `social.csv` - Contains social data points and labels.
  - `governance.csv` - Contains governance data points and labels.
- **README.md** - This documentation file.
- **LICENSE** - The license for the dataset.

## Usage

To use this dataset, you can clone the repository and load the data files into your preferred data analysis environment.

```bash
git clone https://github.com/yourusername/ESG-Multiclass-Dataset.git

@dataset{esg_multiclass_2024,
  author    = {Anonymous},
  title     = {ESG Multiclass Dataset},
  year      = {2024},
  url       = {https://github.com/yourusername/ESG-Multiclass-Dataset},
}