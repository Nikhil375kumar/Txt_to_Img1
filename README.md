# **Gen AI Text-to-Image Generator using Stable Diffusion**  

## **Overview**  
This is a web-based **text-to-image generator** built using **Stable Diffusion**. Users can input a text prompt, configure various parameters, and generate AI-generated images.  

## **Features**  
- **Stable Diffusion 2.1** for high-quality image generation.  
- **Multiple Scheduler Algorithms**:  
  - Euler Discrete  
  - LMS Discrete  
  - PNDM  
  - DPM Solver Multistep  
  - DDIM  
- **Customizable Parameters**:  
  - Number of inference steps  
  - Guidance scale  
  - Image resolution (height & width)  
  - Seed for reproducibility  
- **Web UI using Gradio** for easy interaction.  

---

## **Installation & Setup**  

### **1. Clone the Repository**  
```bash
git clone <repository_link>
cd <repository_name>
```

### **2. Install Dependencies**  
```bash
pip install torch diffusers gradio pillow
```

### **3. Run the Web App**  
```bash
python app.py
```

Once the server starts, open the provided **Gradio link** in your browser.  

---

## **Deployment**  

### **Option 1: Hugging Face Spaces**  
- The web app can be deployed on **Hugging Face Spaces** for free.  
- **Limitation**: Runs on **CPU**, making image generation slower.  
- **Demo Link:** [Your Hugging Face Space Link](https://huggingface.co/spaces/madavilavkesh/text2image_stable_diffusion) 

### **Option 2: Google Colab (Faster Processing)**  
For faster execution, use **Google Colab** with **GPU**:  
1. Open **Text_to_Image_generator.ipynb** in [Google Colab](https://colab.research.google.com/).  
2. **Change runtime to GPU**:  
   - Click **Runtime** → **Change runtime type** → **Select GPU** → **Save**.  
3. Run all cells and generate images faster than on CPU.  

---

## **Usage Instructions**  
1. Open the web app.  
2. Enter a **text prompt** (e.g., "A futuristic city at sunset").  
3. Adjust **settings** like image resolution, steps, and scheduler.  
4. Click **Generate** to create an AI-generated image.  
5. Download the generated image(s) from the gallery.  

---

## **License**  
This project is open-source and can be modified for learning purposes.  

