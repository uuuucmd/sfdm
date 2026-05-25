**1. Main Environments**
- python 3.8
- The required environment packages are listed in `requirements.txt`.

**2. Prepare the dataset.**

- The PH2, ISIC17, and ISIC18 datasets are divided into a 7:3 ratio.

- Store the datasets in the following directory structure:

- `./data/isic17/`
  - train
    - images
      - .png
    - masks
      - .png
  - val
    - images
      - .png
    - masks
      - .png

**3. Train the SFDM-UNet.**
```
python train.py
```

**4. Obtain the outputs.**
- After training, you can find the outputs in `./results/`.