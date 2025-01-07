# startmlproject

`startmlproject` is a command-line tool designed to streamline the setup of machine learning projects. It creates a structured directory layout and default files to kickstart your ML workflows.

## Why Use `startmlproject`?

Setting up a new machine learning project can be time-consuming. This tool automates the process, ensuring a standardized folder structure and necessary files are created instantly. It is perfect for data scientists and ML engineers who want to save time and focus on their core tasks.

## Features

- Creates a well-organized ML project directory.
- Includes subfolders for:
  - **Data**: Organized into `raw`, `cleaned`, `processed`, and `transformed`.
  - **Notebooks**: Includes a default Jupyter notebook for data exploration.
  - **Scripts**: For storing Python scripts.
  - **Artifacts**: Subfolders like `scalers`, `encoders`, `tokenizers`, `logs`, and `evaluation`.
- Default files created:
  - `requirements.txt` for dependencies.
  - `README.md` as a placeholder for project documentation.

## Installation

To install the package globally:

```bash
pip install startmlproject
```

## Usage

Once installed, you can create a new machine learning project from any directory using the following command:

```bash
startmlproject <project_name>
```

Replace `<project_name>` with the desired name of your project. For example:

```bash
startmlproject my_ml_project
```

## Directory Structure

The tool generates the following structure:

```
my_ml_project/
├── data/
│   ├── raw/
│   ├── cleaned/
│   ├── processed/
│   └── transformed/
├── notebooks/
│   └── 01_data_exploration.ipynb
├── scripts/
├── artifacts/
│   ├── scalers/
│   ├── encoders/
│   ├── tokenizers/
│   ├── logs/
│   └── evaluation/
├── requirements.txt
└── README.md
```

## Contributing

Contributions are welcome! If you have suggestions, feature requests, or bug reports, please:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.
