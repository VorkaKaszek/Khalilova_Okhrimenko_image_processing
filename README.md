# Image Processing Project

This repository contains the code and image data used for an image processing project focused on preparing and transforming PNG image files for further analysis and modelling.

The project includes a collection of image files organized into subfolders and a Jupyter Notebook containing the main image processing workflow. Git Large File Storage (Git LFS) is used to store PNG image files because the dataset contains many image files and should not be stored directly in regular Git history.

## Authors

- Kostiantyn Okhrimenko, student ID: 473494
- Zarina Khalilova, student ID: 476692

## Repository Contents

The repository contains:

- `image_processing.ipynb` — main Jupyter Notebook with the image processing workflow;
- image subfolders — folders containing PNG image files used in the project;
- `.gitattributes` — Git LFS configuration file for tracking PNG files;
- `.gitignore` — file specifying files and folders that should not be tracked by Git.

## Project Description

The aim of this project is to perform image processing operations on a collection of PNG images. The workflow includes loading image files, applying selected transformations, and preparing processed images for further use.

The repository is organized so that the original image structure is preserved. This makes it easier to reproduce the workflow and understand how the input images are processed.

## Git LFS

This repository uses Git Large File Storage for PNG files. The following pattern is tracked by Git LFS:

```text
*.png
```

Because of this, users who clone the repository should have Git LFS installed.

To install Git LFS, run:

```bash
git lfs install
```

Then clone the repository normally:

```bash
git clone https://github.com/VorkaKaszek/Khalilova_Okhrimenko_image_processing.git
```

After cloning, Git LFS should automatically download the image files. If needed, they can also be downloaded manually using:

```bash
git lfs pull
```

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/VorkaKaszek/Khalilova_Okhrimenko_image_processing.git
```

2. Enter the project folder:

```bash
cd Khalilova_Okhrimenko_image_processing
```

3. Install Git LFS and download the image files:

```bash
git lfs install
git lfs pull
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook image_processing.ipynb
```

5. Run the notebook cells in order.


## Notes

The PNG files are stored using Git LFS due to their number and size. This keeps the repository manageable while still allowing the full image dataset to be versioned and shared through GitHub.

The project was prepared as part of an academic image processing assignment.