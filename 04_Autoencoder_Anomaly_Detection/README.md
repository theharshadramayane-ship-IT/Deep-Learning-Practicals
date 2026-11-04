Aim: To detect abnormal images using an Autoencoder neural network.

Short explanation: Autoencoder normal images ko learn karke recreate karta hai. Agar image unusual ho, toh reconstruction error usually high hota hai. Isi error ke basis par hum Normal aur Anomaly identify karte hain.

Dataset: MNIST (automatically TensorFlow se load hoga).
- Digits 0–4 = Normal
- Digits 5–9 = Anomaly

Expected output
1. Autoencoder training and validation loss.
2. Anomaly threshold.
3. Test accuracy.
4. Original and reconstructed images.
5. Reconstruction error graph with threshold.
6. Normal/Anomaly predictions.
Note: Here, digits 5–9 are artificially labelled as anomalies for demonstration. Accuracy can vary because this is a simple experimental setup.
