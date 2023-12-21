

## Data exploration tool
This little tool allows you to 'talk' to a specific document using vector databases & LangChain. Use it to explore data you have in an easy and quick way. You can use it for research, business exploration and more. Have fun! 

## how it works
You point it at a the file you want to use, it uploads to a local vector database, then it uses the information to answer questions. 


## setup
Go to the base folder. 

Set up a virtual environment and activate it. 
'''
virtualenv .venv
source .venv/bin/activate
'''

then install all the requirements
'''
pip install -r requirements.txt
'''

For now, it points at one file and uses that. It's the file in the mydocument folder. If you change it, you also need to change the name in chat_workflow.py. If that is all correct, run the app and have fun. 


To run the streamlit app, so this in root:
'''
streamlit run app.py
'''