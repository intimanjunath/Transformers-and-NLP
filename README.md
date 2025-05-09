# 🧠 Transformers and NLP – Assignment (Deadline: May 4, 11:59 PM)

This repository contains the complete solution to the NLP assignment, implementing:

1. Inference with a pretrained classifier using KerasNLP
2. Fine-tuning a BERT backbone on AG News
3. Building a Transformer model from scratch on IMDb

Each notebook includes a full pipeline, debug trace, and recorded video walkthrough as required.

---

## 📘 Assignment Breakdown

| Part | Notebook | Task | Description |
|------|----------|------|-------------|
| ✅ 1 | `Inference_with_pretrained_classifier.ipynb` | **Inference** | Run inference using a pretrained BERT model on custom factual statements |
| ✅ 2 | `Fine tuning a pretrained BERT classifier.ipynb` | **Fine-tuning** | Fine-tune `bert_tiny` on AG News for 4-class topic classification |
| ✅ 3 | `imdb_transformer_custom_architecture.ipynb` | **From Scratch** | Custom Transformer built from Keras layers, trained on IMDb sentiment |

---

## 📂 Colab Notebooks

> 🔗 Click the links below to open each Colab notebook directly (make sure sharing is set to **Anyone with the link can view**):

- 📘 [Part 1 – Inference with Pretrained BERT](https://colab.research.google.com/drive/1HGBA2gwNaYkctI6n_VTmvUa6-dagFmfk?usp=sharing)
- 📘 [Part 2 – Fine-Tuning BERT on AG News](https://colab.research.google.com/drive/1BHDxQPbPtA_LHh6W2ePJ9C0J1ABgUuas?usp=sharing)
- 📘 [Part 3 – Custom Transformer on IMDb](https://colab.research.google.com/drive/1vuw4So3tNjiDn-xkPD2FTWqmOg3yJLv6?usp=sharing)

---

## 🎥 Walkthrough Videos

- 📽️ [You Tube Link](YOUR_VIDEO_LINK_1)

---

## 🛠 Tools Used

- **KerasNLP** for pretrained BERT (`from_preset`)
- **Hugging Face Datasets** for AG News and IMDb
- **Keras Functional API** for building a transformer from scratch
- `MultiHeadAttention`, `LayerNormalization`, `Dropout`, etc.

---

## 🧠 References & Hints

- [Keras NLP Inference & Fine-Tuning Guide](https://colab.research.google.com/github/keras-team/keras-io/blob/master/guides/ipynb/keras_hub/getting_started.ipynb)
- [Build Transformer from Scratch (Keras Example)](https://keras.io/examples/nlp/text_classification_with_transformer/)
- [Keras Hub – Transformer Pretraining](https://keras.io/keras_hub/guides/transformer_pretraining)
- [Google I/O NLP 2023](https://io.google/2023/program/79e77594-3e72-4df2-a754-916af4f29ba9)
