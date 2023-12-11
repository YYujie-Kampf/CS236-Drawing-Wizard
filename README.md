# Stanford CS 236 Final Project - Drawing Wizard
## Colab Notebook
- `CS236_DrawingWizard.ipynb`: image-to-image translation
- `Evaluation_StyleCNN.ipynb`: evaluation using StyleCNN

## Datasets
Download the original and entire dataset from [How Do Humans Sketch Objects?](https://cybertron.cg.tu-berlin.de/eitz/projects/classifysketch/).
All the sketches in the datasets below are randomly selected from the original dataset.

- `sketches_6.zip`: small dataset containing 6 sketches
- `sketches_50.zip`: large dataset containing 50 sketches

## Checkpoints
Please see all the checkpoints in this [google drive folder](https://drive.google.com/drive/u/1/folders/13-9DLR9yscVa59N3sJoeCtF2Cvy4Ry4I).

## StyleCNN (test mode)
Modified from [Content and Style CNNs](https://github.com/giddyyupp/style-content-cnn).
- **Input:** images after translation
- **Output:** classification accuracy (10 classes)

## Results
Please see the results in this [google drive folder](https://drive.google.com/drive/u/1/folders/1bsZde3Dn_5uQObi713JTVqeNFkk6_wCO).

## Acknowledgments
This project is built on the work and with the help of [pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix), [CycleGAN](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix), [GANILLA](https://github.com/giddyyupp/ganilla) and [Style CNN](https://github.com/giddyyupp/style-content-cnn).
