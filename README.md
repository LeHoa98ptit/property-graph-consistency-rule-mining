# Graph Consistency Rule Mining with LLMs: an Exploratory Study

This repository contains code and data for mining consistency rules in property graphs. It includes various methods applied to datasets from different domains.

## Repository Structure

- **/data**: Contains property graph data.
- **/mode**: Contains the model file "all-MiniLM-L6-v2-f16.gguf" used for the project.
- **/CyberSecurity**: Includes two notebooks showcasing different methods applied to cybersecurity data.
- **/WWC-2019**: Includes two notebooks with methods applied to the WWC-2019 dataset.


## Requirements
You can install these dependencies by running:

```bash
pip install -r requirements.txt
```

## Running the Notebooks

To run the notebooks, follow these steps:

1. **Model Requirement**: To run the notebooks for the RAG method, you need to have the model file "all-MiniLM-L6-v2-f16.gguf" in the "/mode" directory.

2. Navigate to the folder containing the notebook you wish to run (e.g., "/CyberSecurity/Cyber_Window" or "/WWC-2019/RAG_WWC").

3. Launch the Jupyter notebook server by running:

   ```bash
   jupyter notebook
    ```

4. Open the notebook of your choice and run the cells to execute the methods.

Each notebook explores different techniques for consistency rule mining applied to property graphs in its respective domain.

