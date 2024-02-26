
# TrustGuard: Verifiable Fraud Detection

## Overview 
This project implements a cutting-edge fraud detection system utilizing a hybrid approach that combines machine learning (ML) with verifiable computation to enhance the accuracy and integrity of fraud detection in financial transactions. By leveraging the synthetic Banksim dataset, we aim to not only identify fraudulent activities with high precision but also ensure the verifiability of our ML model's predictions, providing cryptographic proof of their correctness. 
## Background 
Financial fraud poses a significant threat to various sectors, including e-commerce, healthcare, and banking. Despite the advancements in rule-based systems and ML models for fraud detection, the adaptability and cunning nature of fraudsters necessitate more sophisticated solutions. This project introduces a verifiable fraud detection model that integrates the dynamic capabilities of ML with the transparency and security of verifiable computation. 
## Dataset 
The Banksim dataset is used for this project. It is a synthetically generated dataset that simulates banking transactions with various amounts over different periods. The dataset is designed to model typical customer transactions, providing a rich ground for training and evaluating our fraud detection model. For more details, you can visit the [Kaggle page for the Banksim dataset](https://www.kaggle.com/ntnu-testimon/banksim1).


## Getting Started 
To set up this project locally, follow these steps: 
1. Clone the repository:
2. Install the required dependencies: 
```bash
pip install -r requirements.txt
```
3. Play with notebook file.

## Technologies

-   Python: For model development and data processing.
-   Machine Learning Libraries: Pytorch, Scikit-learn for building and training the ML models.
-   Verifiable Computation Frameworks: Giza Actions SDK.

## Contributing

We welcome contributions from the community, whether it's improving the model, extending the dataset, or enhancing the verifiability aspects of the project. Please see `CONTRIBUTING.md` for more details on how to contribute.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

-   The project is done for Gizathon Hackathon. 
