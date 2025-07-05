🚀 About the Project

Dresscode.ai is a deep learning-based system that generates 3D garment patterns and realistic textures from natural language prompts. It combines a GPT-style model (SewingGPT) for sewing pattern token generation and a fine-tuned Stable Diffusion model for producing high-quality, tileable PBR textures. The system enables end-to-end virtual clothing design, offering outputs compatible with 3D rendering and simulation tools like Blender.

╠══════════════════════════════════════════════════════════════╣

✨ Features



👗 Prompt-to-Pattern Generation
Generate sewing patterns directly from natural language prompts using SewingGPT.

🧵 Pattern Visualization
Preview generated patterns visually in 2D/3D before exporting.

🎨 Stable Diffusion-Powered Designs
Generate realistic garment images from patterns and textual descriptions.

🧠 Smart Sewing Assistant
Suggests fabric type, stitching method, and customizations based on user input.

📦 Exportable Patterns
Download patterns in formats like SVG, DXF, or PDF for real-world stitching.

🧪 Interactive Model Playground
Experiment with different prompts and tune model parameters in a live demo.

🧑‍🎓 Learning Mode (Optional)
Educational mode for learning sewing concepts and construction methods.

📱 Responsive UI
Clean and intuitive user interface, responsive across desktop and mobile.

📊 Admin & Experiment Dashboard (if built)
Track prompt usage, model performance, and export metrics.

╠══════════════════════════════════════════════════════════════╣


🛠️ Tech Stack

1)Machine Learning & Deep Learning:

.Python

.PyTorch

.Hugging Face Transformers

.Stable Diffusion

.Custom GPT Model (SewingGPT)


2)Computer Vision & Graphics:
.OpenCV

.Blender

.PBR Texture Generation


3)Prompt-to-Pattern Pipeline:

.Tokenizer

.Custom Decoder

4)Dev Tools & Notebooks:

.Jupyter Notebook / Google Colab

.Git & GitHub

.Weights & Biases (optional)

.Matplotlib / NumPy / SciPy


╠══════════════════════════════════════════════════════════════╣

📦 Installation

##Clone the repository

git clone https://github.com/yashidubey/Dresscode.ai.git

cd Dresscode.ai

##Create a virtual environment

python -m venv venv

source venv/bin/activate  # On Windows use: venv\Scripts\activate


##Install Python Dependencies

pip install -r requirements.txt


##If using Jupyter Notebooks (highly recommended)

pip install notebook

jupyter notebook

