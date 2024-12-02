CNN-based model meticulously designed to detect and classify eye diseases from intricate fundus images. Leveraging a sophisticated ensemble learning approach, this model combines the strengths of Inception V3, EfficientB3, and Resnet121 pretrained models, expertly fine-tuning and enhancing them with additional layers to extract more intricate features for precise classification. The crowning achievement lies in the incorporation of a weighted average ensemble learning technique, harmoniously merging these refined models to deliver unparalleled accuracy. Complementing this groundbreaking technology is a responsive Flask-based website, intuitively crafted to facilitate seamless user interaction and efficient diagnosis, ultimately revolutionizing eye disease detection and patient care.

deployment

http://127.0.0.1:8000/

Installation

Clone the project

  git clone https://github.com/sharma-bhavya/EYE-DISEASE-CLASSIFICATION-AI-IN-HEALTHCARE-PROJECT/tree/main
  
Go to the project directory

  cd Eye-Disease-Classigication-and-Detection
  
Install virtual Environment

  python install virtualenv
  
Create virtual Environment

  virtualenv flask
  
Enter in virtual Environment

  cd flask
  
  Scripts/activate
  
Install require modules

  pip install pandas tensorflow numpy flask pillow

Run Locally
Runs the app in the development mode

python app.py








