# Press Event Deduplication

Trains a similarity model on pre-computed article embeddings to identify when articles from different outlets cover the same climate event. Uses analyst merge feedback as positive training pairs and retrains a binary classifier using PyTorch Lightning. Includes data pipeline for generating balanced negative examples, false negative validation against ground truth, and an evaluation loop with per-example confidence scoring.
