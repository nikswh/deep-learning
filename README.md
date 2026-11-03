# Flower Image Classification

Progetto di deep learning per classificare immagini di fiori in cinque categorie:
**daisy, dandelion, roses, sunflowers e tulips**.

Il progetto include l'esplorazione e la pulizia del dataset, la data augmentation,
l'addestramento con cross-validation e il confronto tra diversi modelli:

- CNN addestrata da zero
- Vision Transformer (ViT)
- MobileNetV2 con transfer learning e fine-tuning

## Struttura del progetto

- `notebooks/`: caricamento dei dati, EDA, preprocessing, training e valutazione
- `report/`: report finale del progetto in formato PDF

## Tecnologie principali

Python, TensorFlow, Keras, pandas, NumPy, scikit-learn e Matplotlib.

## Workflow

1. Caricamento ed esplorazione del dataset
2. Pulizia e suddivisione stratificata dei dati
3. Data augmentation e preprocessing
4. Addestramento e fine-tuning dei modelli
5. Valutazione e confronto delle prestazioni
