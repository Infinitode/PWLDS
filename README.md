# PWLDS (Password Weakness and Level Dataset)

PWLDS is a public dataset consisting of over 4 million passwords with varying assigned strength levels. The dataset was designed to help researchers, security professionals, and developers analyze password strength and build more secure systems. The dataset contains 5 classes:

- `very_weak`: Represented by `0` in the dataset
- `weak`: Represented by `1` in the dataset
- `average`: Represented by `2` in the dataset
- `strong`: Represented by `3` in the dataset
- `very_strong`: Represented by `4` in the dataset

For strength level `4`, we used Python's `secrets` module to generate cryptographically secure passwords, ensuring the robustness and security of these passwords.

## Intended Uses

- **Security Analysis**: PWLDS can be used to study common password patterns and weaknesses, helping to identify vulnerabilities and improve password policies.
- **Machine Learning**: The dataset can be used to train machine learning models for password strength estimation or prediction.
- **Educational Purposes**: This dataset is valuable for educational projects and demonstrations related to cybersecurity and data science.
- **Benchmarking**: PWLDS provides a large, labeled dataset for benchmarking password strength estimation algorithms and tools.

## Limitations

- **No Real-World Data**: The dataset is synthetically generated and does not contain real user passwords. While this avoids privacy concerns, it may not fully represent real-world password distribution and usage patterns.
- **Bias in Password Generation**: Since passwords are generated based on predefined rules and patterns, there may be biases that do not reflect the diversity of passwords used in real-life scenarios.
- **Exclusivity to English Words**: The weak and very weak password categories rely heavily on English words, which may not be representative of non-English-speaking populations.

## How to Use the Dataset

1. **Download the Dataset**: You can download the dataset from GitHub or [Hugging Face](https://huggingface.co/datasets/InfinitodeLTD/PWLDS).
2. **Load the Dataset**: Use Python, R, or any data processing tool to load and analyze the dataset. The file is in CSV format for easy use.
3. **Data Structure**: Each entry in the dataset includes a password and its associated strength level (0-4), labels for columns are respectively: `Password` and `Strength_Level`.

## Citation

When using this dataset, please cite as follows:

```
Dataset Title: Password Weakness and Level Dataset (PWLDS)
Author: Infinitode Pty Ltd
Date: 2024
Source: https://github.com/Infinitode/PWLDS
License: Creative Commons Attribution 4.0 International (CC BY 4.0)
```

## License

This dataset is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). See the LICENSE file for more details.

## Contact

For questions or suggestions, please contact us through our website or open an issue on the project's GitHub repository.
