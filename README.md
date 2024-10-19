
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>🌟 AvaCreations: AI Image Generator</h1>
    <p>
        AvaCreations is a simple Python application that uses the power of <strong>Stable Diffusion</strong> to generate stunning images from text prompts. 
        It provides an easy-to-use graphical interface built with <code>tkinter</code> and <code>customtkinter</code>.
    </p>
    <h2>🖼️ Features</h2>
    <ul>
        <li>AI-powered Image Generation: Harness the state-of-the-art <strong>Stable Diffusion</strong> model.</li>
        <li>User-friendly GUI: Simple interface for entering text prompts and generating images.</li>
        <li>CUDA-accelerated: Optimized to run on GPU for faster image generation.</li>
        <li>Real-time display: See the generated image right inside the app window.</li>
    </ul>
    <h2>🚀 Installation</h2>
    <h3>Prerequisites</h3>
    <ul>
        <li>Python 3.8+</li>
        <li>GPU with CUDA support (for fast generation)</li>
        <li>The following Python libraries:</li>
        <pre><code>pip install torch diffusers transformers pillow customtkinter</code></pre>
    </ul>
    <h3>Clone the Repository</h3>
    <pre><code>git clone https://github.com/100rabhhh/avacreations.git
cd avacreations</code></pre>
    <h3>Add Authentication Token</h3>
    <p>To run the Stable Diffusion model, you need an <strong>authentication token</strong> from Hugging Face. Add your token in the <code>authtoken.py</code> file like so:</p>
    <pre><code>auth_token = "your_huggingface_token"</code></pre>
    <h2>💻 Running the Application</h2>
    <p>To start the application, simply run:</p>
    <pre><code>python app.py</code></pre>
    <ul>
        <li>Enter your desired prompt in the text box.</li>
        <li>Click the <strong>"Generate"</strong> button.</li>
        <li>Watch your unique image appear in the app window!</li>
    </ul>
    <h2>🛠️ Technology Stack</h2>
    <ul>
        <li>Backend: Stable Diffusion powered by Hugging Face <code>diffusers</code>.</li>
        <li>Frontend: <code>tkinter</code> and <code>customtkinter</code> for GUI.</li>
        <li>Image Processing: <code>Pillow</code> (PIL).</li>
    </ul>
    <h2>🤖 Model Information</h2>
    <p>This app uses the <code>CompVis/stable-diffusion-v1-4</code> model, which is designed to generate high-quality images from text prompts.</p>
    <h2>⚡ How It Works</h2>
    <ol>
        <li>The user enters a prompt in the text field.</li>
        <li>When the "Generate" button is pressed, the <strong>Stable Diffusion</strong> model processes the input and generates an image.</li>
        <li>The generated image is saved as <code>generatedimage.png</code> and displayed in the GUI.</li>
    </ol>
   <h2>📸 Screenshot 1</h2>
<img src="https://drive.google.com/uc?export=view&id=11m3QxKQMPVs7hASs2RLAUWwo2jZgpJhV" alt="AvaCreations App Screenshot 1" width="600">

<h2>📸 Screenshot 2</h2>
<img src="https://drive.google.com/uc?export=view&id=1dpIhT1xIDAy8rSYzOgXgu5I0uOOEOzr7" alt="AvaCreations App Screenshot 2" width="600">
    <h2>👥 Credits</h2>
    <p>Built by <a href="https://github.com/100rabhhh">Sourabh Jha</a></p>
    <h2>📄 License</h2>
    <p>This project is licensed under the MIT License.</p>

</body>
</html>
