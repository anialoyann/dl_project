# Armenian ASR with NVIDIA QuartzNet

This project demonstrates the implementation and training of an Automatic Speech Recognition (ASR) model for Armenian using NVIDIA QuartzNet. The model utilizes Mozilla's Common Voice dataset for training and evaluation and is optimized with various configurations for improved performance.

---

## Project Contents

This repository contains the following resources:

1. **Jupyter Notebook**: A step-by-step guide for preprocessing, training, validation, and evaluation.
2. **Pretrained Models**: Checkpoints and `.nemo` files for trained models.
3. **Logs and Results**: Training and validation metrics 

---

## Dataset

The Armenian dataset used in this project is from the [Common Voice project by Mozilla](https://commonvoice.mozilla.org/hy-AM/datasets). Version 19.0 of the dataset is used, which includes approximately 30,000 audio clips in `.mp3` format. Half of it is not used in the project as they are still under status **unvalidated**, the rest is split between train, developmen,and test sets. These files were converted to `.wav` format for compatibility with the preprocessing pipeline. The dataset can be downloaded from the same link. Still, the file is very heavy and it has to be converted to .wav by the user. Even though the codes for conversion is left in the notebook too, I highly recommend using the drive folder to avoid these steps as they take too much time.


---




### Drive Link
Access the project resources here: [Google Drive Link](https://drive.google.com/drive/folders/1-0H2O_2IwMNCJAQfgolBoxSgLMnvNX6n?usp=sharing)

All preprocessed data, trained models, configuration files, and the Jupyter Notebook used for this project are available in a shared Google Drive folder. You can simply create a shortcut in your Drive, and with the notebook mount in your Drive and easily use all the resources.

More explicitly, here you can find:
- **Notebook**: `Armenian_ASR.ipynb`
- **Configuration Files**: Custom YAML configurations for QuartzNet.
- **Preprocessed Data**: Converted `.wav` audio files.
- **Trained Models**: Checkpoints (`.ckpt`) and `.nemo` files for easy restoration.
- **Logs** for training and validation.
- **Manifest Files** : The configuration files for train/validation/test datasets that are passed to the model.
- **Additional metadata** that is inside the dataset zip from MCV that is being used throughout the project (ex. the tsv files for creating the manifest files, and many more).

**Should you encounter any problems accessing the Drive folder, please contact me asap**