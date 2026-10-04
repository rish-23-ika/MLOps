# P04 - From Notebook to Package

## Module Responsibilities

- `__init__.py` — Defines the delivery package and makes its modules available for import.
- `data.py` — Loads and prepares the delivery dataset for model training and testing.
- `features.py` — Provides feature-related calculations used for delivery-time prediction.
- `model.py` — Handles training, evaluation, saving, and loading of the prediction model.
- `validate.py` — Validates delivery-order inputs and rejects invalid values.
- `train.py` — Provides the command-line entry point for training and saving the model.
- `predict.py` — Loads the trained model and generates a delivery-time prediction for a given order.

## AI Assistance Disclosure

AI assistance was used to clarify the practical instructions and review/debug parts of the implementation. I executed and reviewed the submitted work and can explain and modify the code submitted.