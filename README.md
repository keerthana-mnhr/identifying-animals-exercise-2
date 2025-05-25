# Install dependent packages
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
# Make the venv Available as a Jupyter Kernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
# Setup Kernel 
- Open your Identify-animals.ipynb notebook in VS Code.
- Click the kernel name in the top-right (it might say "Python 3" or Python).
- Select the one called Python (venv) which we created now