# Chatbot Using Python
Create a chatbot using deep learning techniques. The chatbot will be trained on a dataset containing categories (intents), patterns, and responses. Utilize a special recurrent neural network (LSTM) to classify the user's message into a category and provide a random response from a predefined list.

Getting Started
Download Files:

Download all the necessary files for the chatbot.
Open Command Prompt:

Open the command prompt on your system.
Navigate to the Folder:

Use the cd command to navigate to the folder where your chatbot files are located.
Check Module Installation:

Ensure that the required modules (tensorflow, keras, nltk, pickle) are installed. If not, install them using pip install module_name. If already installed, it will show "Requirement already satisfied."
Train the Model:

Execute the "train_chatbot.py" file with the command python train_chatbot.py. If the training is successful, it will display "Model created."
Open GUI Window:

To start a conversation with the chatbot, execute the "chatgui.py" file using python chatgui.py. This will open the GUI window.
Initiate Conversation:

Type your text in the section on the right of the send button, then click "Send" to receive responses.
ERROR GUIDE:

If you encounter an error like "ImportError: cannot import name 'tf_utils'" during the execution of "train_chatbot.py," follow these steps:

Uninstall Keras: pip uninstall keras
Reinstall Keras (specific version): pip install keras==2.2.0
Try executing the file again, and it should work properly.
