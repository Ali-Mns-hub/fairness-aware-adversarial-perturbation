# Data Setup

This project uses the **CelebA dataset** to evaluate the fairness of the classifier.

*   **Source:** The dataset is automatically downloaded via the `datasets` library from the Hugging Face Hub (`huggan/celeba-faces` or equivalent)[cite: 76, 104].
*   **Target Attribute:** `Smiling`[cite: 76, 104]
*   **Sensitive Attribute:** `Male` (Gender)[cite: 76, 104]

No manual download is required if you run the notebook. Ensure you have internet access and the `datasets` package installed.
