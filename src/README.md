# Source Code

The complete implementation is currently in the Jupyter notebook:
[FairnessInHRData.ipynb](../notebook/FairnessInHRData.ipynb)

This folder is structured for future modularization when transitioning 
from research prototype to production deployment.

## Planned Modular Architecture:

### bias_detection.py
- Disparate impact calculations
- Language bias analysis  
- Statistical validation

### rag_system.py
- Document chunking and embedding
- FAISS vector database queries
- Legal context retrieval

### fairness_agent.py
- 4-step agentic workflow
- Self-verification logic
- Automated remediation

### utils.py
- Helper functions
- Configuration management
- Logging and monitoring
