# Computational Biology & Machine Learning Project

### Predictive Drug-Target Interaction (DTI) Model

This is a classic problem with huge commercial relevance; using advanced deep learning techniques is needed. A predictive Drug-Target Interaction (DTI) model uses computational methods to determine or estimate the binding likelihood or affinity between potential drug molecules and biological target proteins (e.g., receptors, enzymes, ion channels). This approach significantly accelerates drug discovery by filtering out compounds with low potential early in the process, thus reducing the time and cost associated with experimental methods.

- **The Biological Goal**:
Predict whether a given small molecule (drug candidate) will bind to a specific protein (target) using only their molecular and sequence information.

- **Key Techniques**:
Data Representation (Encoding): This is the core challenge. You would represent the drug molecule using a method like SMILES string encoding or molecular graphs. The target protein is represented by its amino acid sequence.

- **Model Architecture**:
Use a Graph Neural Network (GNN) for the drug molecule and/or a Convolutional Neural Network (CNN) or Recurrent Neural Network (RNN) for the protein sequence.

- **Prediction**:
Combine the feature vectors from the drug and protein modules (often using an attention mechanism or concatenation) and feed them into a final classifier (e.g., a simple feed-forward network) to predict the binding probability.

- **Data Sources**:
Public databases like ChEMBL or BindingDB are excellent starting points for training data

- **What it Showcases**:
Advanced deep learning, graph-based modeling, feature engineering for heterogeneous biological data, and a clear application in drug discovery.
