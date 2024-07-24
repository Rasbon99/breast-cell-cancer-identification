# Breast Cells Classification with Carbon Nanoparticles

This repository contains the code and resources for a project aimed at predicting the class of breast cells (benign/malignant) after exposure to carbon nanoparticles. This project was completed as part of a machine learning contest for the Master’s degree in Computer Engineering at the University of Naples Federico II.

## Overview

The objective of this project is to understand whether exposure to carbon nanoparticles can affect the identification of tumor tissue in breast cells. Participants are required to develop predictive models using data analysis and machine learning techniques to classify each cell as benign or malignant. The primary performance metric for this task is Accuracy.

## Dataset Description

The dataset used in this project is provided by the DICMAPI research group. It includes multichannel images of breast cells obtained using different imaging modalities. Each image is a three-channel composite that combines:

- Brightfield imaging to capture the overall cell morphology.
- Imaging focused on cell membranes to outline cell borders.
- Imaging focused on nuclear membranes to outline nuclear borders and analyze nuclear morphology.

Each acquisition contains multiple cells, and an algorithm is used to extract individual cells, treating each one as a separate image. The training set consists of 40 acquisitions, each represented as a folder containing images in the `.npy` format. The test set includes 10 acquisitions without separate folders.

**Note:** For privacy reasons, the dataset used in this project cannot be shared publicly.

## Project Structure

## Acknowledgements

We would like to thank:
- Prof. Mariano Sirignano
- Prof. Valeria Panzetta
- Prof. Carlo Sansone
- Assistant Michela Gravina

from DICMAPI (Dipartimento di Ingegneria Chimica, dei Materiali e della Produzione Industriale) and DIETI (Dipartimento di Ingegneria Elettrica e delle Tecnologie dell'Informazione) for providing the task and the data.
