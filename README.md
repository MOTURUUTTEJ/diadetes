# Diabetes Project (diadetes)

A notebook-first machine learning project for health-risk experimentation, focused on diabetes prediction with an additional pregnancy-status modeling workflow.

## Features

- Hybrid ML workflow inside `Welcome_To_Colab.ipynb`
- Diabetes prediction pipeline with preprocessing and classification
- Pregnancy-status model for clinical feature experimentation
- Optional quantum-kernel experimentation through Qiskit ML
- Gradio-ready structure in notebook cells for interactive demos

## Use Cases

- Learning end-to-end ML workflows in Google Colab
- Rapid prototyping for health-data classification tasks
- Comparing classical and quantum-inspired model approaches
- Demonstrating notebook-based AI projects in academic portfolios

## Tech Stack

- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook
- **Core Libraries:** pandas, numpy, scikit-learn, xgboost, gradio
- **Optional/Advanced:** qiskit, qiskit-machine-learning

## Project Structure

- `Welcome_To_Colab.ipynb` – main notebook with data prep, model training, and inference workflow
- `README.md` – project documentation
- `CONTRIBUTING.md` – collaboration guidelines
- `LICENSE` – MIT License

## Setup

### Option 1: Run in Google Colab (recommended)
1. Open `Welcome_To_Colab.ipynb` in Colab.
2. Run all setup/import cells.
3. Ensure required packages install successfully in the runtime.

### Option 2: Run locally
1. Create a Python virtual environment.
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn xgboost gradio qiskit qiskit-machine-learning
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open and run `Welcome_To_Colab.ipynb`.

## Usage Example

Typical notebook flow:
1. Load or generate required datasets (`diabetes.csv`, `pregnancy_data.csv`).
2. Run preprocessing and model-training cells.
3. Evaluate model accuracy outputs.
4. Launch demo/interactive prediction cells (Gradio blocks if enabled).

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](./CONTRIBUTING.md) before opening issues or pull requests.

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE).
