This project is a modular, prompt-driven AI system that transforms public-domain narratives into new settings while preserving their thematic essence and core structure.

The selected story is The Ramayana, reimagined as a far-future interplanetary cyberpunk rebellion.
The system demonstrates:

Narrative transformation using prompt chaining

Structured reasoning & output consistency

System and framework thinking

Extensibility to new stories and settings

Secure + modular code design


Project Structure
.
├── Task.ipynb                 # Core runnable pipeline (works with or without API)

├── Reimagined_Story.md    # Full written output (story + mapping + analysis)


└── System_Design.pdf      # Architecture & engineering documentation


└── README.md



How It Works
Pipeline:
User selects story + target world
        ↓
Metadata extraction (themes, characters, core scenes)
        ↓
Worldbuilding prompt
        ↓
Character mapping prompt
        ↓
Plot outline prompt
        ↓
Dramatic reinterpretation prompt
        ↓
Creative rationale prompt
        ↓
Output assembly → Final formatted document


Each step is independent, reproducible, and can be swapped out for alternative models or settings.



Running the Project (Colab)
1. Open run.ipynb in Google Colab
2. (Optional) Add your API key
import os
os.environ["OPENAI_API_KEY"] = "your_api_key_here"


Keys are NOT included in this repo for security reasons.

3. Run all cells

You will get:

Generated worldbuilding

Character mapping table

Plot structure

Reinterpretation & rationale

Final assembled document saved as .md
