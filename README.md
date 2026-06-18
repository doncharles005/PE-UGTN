**Instructions for the PE-UGTN**

Run the basic PE-UGTN first.
Next, run the Ablation study to determine which of the signals for anomaly detection (reconstruction, residual, and latent deviation) to use. 
Next, run the PE-UGTN on the reconstruction + residual configuration, use the 95th percentile.
Next, perform the diagnostics (Precision, Recall, F1-Score, and Accuracy) for each Threshold.
Next, run the PE-UGTN on the reconstruction + residual configuration, but using the threshold τ = 3.5.
