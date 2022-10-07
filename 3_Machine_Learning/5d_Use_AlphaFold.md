# USE AlphaFold for Protein Folding Prediction

### Why do this
 - USE AlphaFold and GCP Vertex AI for efficient protein folding prediction. Once a protein’s structure is determined and its role within the cell is understood, scientists can develop drugs that can modulate the protein function based on its role in the cell

### What is this
 - AlphaFold is a machine learning model (uses TensorFlow) created by Google DeepMind. Here's a 7 minute video on AlphaFold concepts, including running it on GCP Vertex AI - [link](https://www.youtube.com/watch?v=CX0BTkimL7A)

### Key considerations
- Use Colabs or Vertex AI Notebook to test w/Example Notebook (output shown below)
- Use Vertex AI (batch) Pipeline to scale - [link](https://cloud.google.com/blog/products/ai-machine-learning/alphafold-batch-inference-with-vertex-ai-pipelines)

### How to do this
 - Run the example notebook linked below in Google Colabs 

- AlphaFold BigQuery public dataset → https://goo.gle/3Em79pd
- AlphaFold notebook on Vertex AI Workbench → https://goo.gle/3ryXbcp
- AlphaFold batch inferencing solution on Vertex AI Pipelines → https://goo.gle/3V7OJhI
- Deepmind Youtube channel → https://goo.gle/3EeHr66

### How to verify you've done it
 - Run the example Colabs Notebook linked above

### Other Things to Know
 - BigQuery AlphFold public database (214M AlphaFold protein structure predictions from DeepMind) at [link](https://console.cloud.google.com/marketplace/product/bigquery-public-data/deepmind-alphafold)

### How to learn more
- 📘 FAQ for AlphaFold - [link](https://alphafold.ebi.ac.uk/faq)
- :paper: From Nature: "Highly Accurate Protein Structure Prediction w/AlphaFold" - [link](https://www.nature.com/articles/s41586-021-03819-2)
 