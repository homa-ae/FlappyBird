## Python environment instructions:   

#### Directory where the contents will be extracted:
import zipfile   
zip_file_path = '/content/Lec2_DeepQ-Learning.zip'    
extract_dir = '/content/Lec2_DeepQ-Learning'  
    
#### Change directory to the extracted folder:
import os   
os.chdir('/content/Lec2_ Deep Q-Learning/0_Exercise_env/')  

!pip install tensorboardX

%run train.py

