# AI_Agents
Repo for my different AI Agents. These agents will accomplish different goals based on their folders

## Python notebooks in Cursor

The workspace uses Python 3.12 in `.venv`. Install the notebook and AI dependencies from PowerShell:

```powershell
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

In Cursor, install the **Python** and **Jupyter** extensions, open or create a `.ipynb` notebook, then select the workspace `.venv` Python interpreter as its kernel. The workspace is configured to use that interpreter by default.

To use the OpenAI API, copy `.env.example` to `.env` and add your API key. Load it in a notebook with:

```python
from dotenv import load_dotenv

load_dotenv()
```

The `.env` file is ignored by Git; keep API keys and other secrets there, not in notebooks or source files.


Testing this change