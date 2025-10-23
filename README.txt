Deeplearning course about
ANN models creation and training 
https://www.linkedin.com/learning/paths/advance-your-skills-in-deep-learning-and-neural-networks?u=26887922

1 Module: Advance Your Skills in Deep Learning and Neural Networks 
Deeplearning course on the top of Python, Tensorflow, Keras, sklearn, pandas.
Anaconda & Jupyter notebook are used as env.

Creating, training of ANN models and usage them in prediction for :
 - Classification by params (Iris types)
 - Program accident-root-cause classification based on input parameters

#To run 
ann-models/incident_root_cause_analysis.ipynb, follow these steps:

Open a terminal.
 - Activate your Anaconda environment (if using Anaconda): 'conda activate <your_env_name>'
Start anaconda platform:   'anaconda-navigator'

Start Jupyter Notebook:
"jupyter notebook"onto command line and hit Enter.
In the Jupyter interface, navigate to the ann-models folder and open incident_root_cause_analysis.ipynb.
Run the notebook cells one by one (Shift+Enter).
Make sure you have all required packages (pandas, tensorflow, scikit-learn, numpy) installed in your environment.

#If Issues with Anaconda Installation Occurs:
 - To resolve issue with certificates:
conda update conda
conda install certifi
conda config --set ssl_verify false
 - To Launch Jupyter Notebook (after installing Anaconda): 'jupyter notebook'
 - To Check If It's Still Processing: 'ps aux | grep conda'



