
# Model Export - Project Classification

Repository ini berisi model dalam tiga format:
| Format | Kegunaan |
|-------|----------|
| SavedModel | Standar TensorFlow (Training + Deployment) |
| TFLite | Mobile / Edge TPU Deployment |
| TFJS | Web Deployment (Browser/NodeJS) |

Referensi file:
- saved_model/ → format asli untuk inferensi
- tflite/model.tflite + label.txt untuk mobile
- tfjs_model/ untuk web

