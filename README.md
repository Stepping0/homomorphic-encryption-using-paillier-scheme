System requirements
We need bt onprem and server side. 
1.	Download jupyter notebook on your vscode
2.	For onprem side it is preferred to use virtual environment or you can use anaconda
    >python -m venv ./venv
    
    >.\venv\Scripts\activate 
After this step you can activate your kernal for onprem side  
3.	For Cloud side we run this command to run a server. 
    >jupyter notebook --no--browser --port=8888
    
Nexstep is catching the link has given 
We copy the link and paste it to Kernel preferences
4.	Download the Lightphe library
    pip install lightphe
