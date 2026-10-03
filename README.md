# Inferno Studio

Inferno Studio is a fire-toned, game-inspired interface for an AdaIN neural style-transfer demo. Upload a content image and a style reference, adjust the style strength, and download the generated image.

## Run locally

1. Install Python 3.10 or 3.11 to match the pinned PyTorch dependencies.
2. From this folder, install the listed dependencies:

   pip install -r requirements.txt

3. Start the app:
   run-- 
  1-> cd ai-nst-project-main\NST_Code

  2-> python app.py

4. Open http://localhost:5000.

The app loads its encoder and decoder checkpoints from the included NST_Code folders. The style-transfer workflow remains AdaIN; this update changes the website presentation and makes checkpoint paths work relative to the project.


