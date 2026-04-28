How to Run This Project Locally

Follow these steps carefully.

Step 1: Download the Source Code

Clone this repository:

git clone <https://github.com/prashantyadav070/Deep-Learning-and-CNN-Based-Brain-Tumor-Detection-Platform-Repo.git>

Or download the ZIP file from GitHub and extract it.

Step 2: Open Project Folder
cd Brain-Tumor-Detection
Step 3: Create Virtual Environment

For Windows:

python -m venv venv

Activate it:

venv\Scripts\activate

For Linux / Mac:

python3 -m venv venv

Activate it:

source venv/bin/activate
Step 4: Install Required Libraries
pip install -r requirements.txt
Step 5: Download Model File

Download model.h5 from the Google Drive link:

<https://drive.google.com/file/d/1qbnOoa1oeiufnSacw3VUsCInCwrNiTl4/view?usp=sharing>

Place it here:

models/model.h5
Step 6: Run the Flask Application
python main.py
Step 7: Open in Browser

After running the project, open this URL in your browser:

http://127.0.0.1:5000

Now the web application will be ready to use.
