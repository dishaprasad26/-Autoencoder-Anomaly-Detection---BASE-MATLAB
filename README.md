# -Autoencoder-Anomaly-Detection---BASE-MATLAB
This MATLAB project detects faulty motor vibration without needing any fault examples for training. A small autoencoder (a neural network that compresses and rebuilds its input) learns only what normal vibration looks like. When a faulty signal is fed in, the network rebuilds it badly, and the large reconstruction error raises an alarm.
