# TinyTales-GenAI-
TinyTales: A GenAI-Based Children's Story Generator using GPT-2 and Hugging Face Transformers


# TinyTales 🧒📚  
### A GenAI-Based Children's Story Generator using GPT-2 and Hugging Face Transformers

TinyTales is a Generative AI (GenAI) project designed to create imaginative and age-appropriate children's stories from a simple prompt. Built using the GPT-2 language model and Hugging Face Transformers, the tool generates complete short stories tailored to early readers. It provides a fun and educational experience for parents, teachers, and young learners.

---

## 🛠️ Tech Stack

- **Language Model**: GPT-2 (via Hugging Face Transformers)
- **Backend**: PyTorch
- **Libraries**: `transformers`, `torch`, `ipywidgets`
- **Interface**: Jupyter Notebook (with widgets for interaction)

---

## 🚀 Features

- Prompt-based children's story generation
- Uses locally loaded GPT-2 model (no external API needed)
- Configurable story length and creativity (temperature, top_k, top_p)
- Easy-to-use function for generating and displaying stories
- Educational and creative output suitable for kids aged 3–10

---

## 🎯 How It Works

1. User provides a **short prompt** (e.g., _"A rabbit who wanted to fly"_).
2. The input is tokenized using GPT-2's tokenizer.
3. The pre-trained GPT-2 model generates text based on the prompt.
4. Output is decoded and presented as a full short story.
5. Optional controls: max length, temperature, repetition penalty, etc.

---

## 🧪 Sample Prompt & Output

**Prompt:**  
A tiny penguin who dreamed of becoming an astronaut


**Generated Story (sample):**  
Once upon a time, in the icy lands of Antarctica, there lived a little penguin named Pip. While all his friends loved to swim and slide on the snow, Pip spent his time staring at the stars...



---

## 📁 Project Structure

TinyTales/
│
├── Genai.ipynb # Main notebook with code and widgets
├── requirements.txt # Required libraries
└── README.md # This file


---

## 📦 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/tinytales.git
   cd tinytales
Install the required libraries:


pip install torch transformers ipywidgets
Enable Jupyter widgets (if needed):


jupyter nbextension enable --py widgetsnbextension
Run the notebook:


jupyter notebook Genai.ipynb
📚 Future Improvements
Add UI with Streamlit or Gradio for web-based access

Integrate text-to-speech for audio storytelling

Age-level vocabulary control

Image generation to accompany stories (via DALL·E or Stable Diffusion)

🙋‍♂️ Author
Gouthum Kharvi
Data Scientist | AI & ML Enthusiast
