# BERTLatentReplay

## Overview
This project investigates the use of Latent Replay, a technique proposed by Pellegrini et al. (2020), to mitigate this issue in the context of continual language learning. Three methods are evaluated: Baseline (Fine-tuning), Full Replay, and Latent Replay, across a series of tasks from the GLUE dataset, which encompasses a variety of natural language understanding challenges. Latent Replay involves storing and replaying the activations from an intermediate layer of BERT, rather than raw input examples.

## Data
The GLUE datasets can be downloaded with `download_glue_data.py` script.

## Files and Descriptions

### `bert-base.ipynb`
This is the implementation of the Baseline method of fine-tuning BERT on each task sequentially.

### `bert-full.ipynb`
This is the implementation of the Full Replay method.

### `bert-lr.ipynb`
This is the implementation of the Latent Replay method.

### `lr_layertest.ipynb`
Testing different layers to use for Latent Replay within the BERT model.


