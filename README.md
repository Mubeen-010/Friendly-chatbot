Friendly Chat-Bot Project

## Dependencies:

The following Python libraries are required:

- transformers (For the pre-trained BlenderBot model)
- pandas (For handling data)
- datasets (For managing and training datasets)
- evaluate (For evaluating model performance)
- tkinter (For the graphical user interface)

## Installation:

1. Create a virtual environment (optional but recommended):

- Run this in Command Prompt:
    				python3 -m venv venv
    				venv\Scripts\activate  

2. Install dependencies:
   
    pip install transformers pandas datasets evaluate tk


## Configuration:

Some paths are hardcoded in the code. Please update the following paths based on your local setup:

- Model Files: Update the path for any custom models or datasets.
- Data Paths: Set the correct file path for any external data sources.

## Running the Project:

1. For Desktop App Interaction:

- Run the file:  
    		Application.ipynb
    

2. For Training & Fine-Tuning:
 
- Run the file:    
    		Code.ipynb
    

### Path Details:

- The path for the fine-tuned model in `Application.ipynb` is:
    
    		NLP_Project\Implementation_Folder\App\fine_tuned_blenderbot
  

- The path for the dataset in `Code.ipynb` is:
    
   		 NLP_Project\Implementation_Folder\App\data
   

## Notes:

1. The project uses the BlenderBot model from Hugging Face.
2. The GUI is built with Tkinter, displaying the bot's responses in a chat interface.
3. Make sure to update the paths as mentioned.
4.IMPORTANT:
   Fine-tune the model using "Code.ipynb" with the dataset "data.csv" or your custom dataset, then use "Application.ipynb" to interact with the bot through a user-friendly UI.

Thank you!
