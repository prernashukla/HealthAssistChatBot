# Health Issue Identification Chatbot

## Objective
To design a chatbot using OpenAI that helps identify the health issue the user is facing. The chatbot will engage in a conversation to understand the user's symptoms and categorize them into predefined health issues. Once identified, the chatbot will provide appropriate advice from certified doctors or direct the user to seek further medical assistance.

## System Design
The chatbot is designed to take user input by welcoming the user with greetings and asking if they are facing any problems. Upon receiving the problem, if the issue is clear, it categorizes the problem into predefined health issues. If not, it asks more questions to get a better understanding. Once the health issue is found and categorized, it will provide appropriate advice or direct the user to seek further assistance. The chatbot will terminate the conversation when the user types "exit".

![System Design](path_to_system_design_image)

## In Action
The chatbot starts with a welcome message and encourages the user to share their health issues. It then asks relevant questions to understand the user's symptoms and categorizes the issue accordingly. Here is an example conversation:

**Assistant**: Hello! I'm here to help you with your health issues. Please feel free to share any symptoms or discomfort you are experiencing so I can assist you better. What seems to be the problem?
**User**: Hi, I am facing health issues.  
**Assistant**: I'm sorry to hear that. Can you describe your symptoms a bit more? Do you have a runny nose or a cough? Please tell me more so I can assist you better.  
**User**: I think I have a cough, but I'm not sure.  
**Assistant**: Thank you for the information. Let me help you further.

## Steps to Run the Project
1. **Ensure OpenAI Account and API Keys**:
   - Create an account on OpenAI if you don't have one.
   - Make sure you have enough credits to use the 'gpt-3.5-turbo' model.
   - Obtain your API keys and save them in a file named `Open_AI_Key.txt`.

2. **Open the Project in Visual Studio Code**:
   - Launch Microsoft Visual Studio Code on your computer.
   - Open the project folder in Visual Studio Code.

3. **Run the Main Application File**:
   - Locate the `app.py` file in the project directory.
   - Execute the `app.py` file to start the chatbot. This file contains the initial flow of the code and will set everything in motion.

4. **Interact with the Chatbot**:
   - You can open the webpage at `http://127.0.0.1:5000/` to converse with the chatbot.

**Note**:
- Installation: Run `pip install -r requirements.txt` to install all the dependencies.
- Since we are using online LLM models, sometimes responses might not be as expected, so try again by clicking on the ‘End Conversation’ button or restarting the application.

## Dataset
The dataset used in this project is a refined list of health issues and their solutions. The dataset includes categories such as 'Cuts', 'Abrasions', 'Stings', 'Splinter', 'Sprains', 'Strains', 'Fever', 'Nasal Congestion', 'Cough', 'Sore Throat', 'Gastrointestinal problems', 'Skin problems', 'Abdominal Pain', 'Bruises', 'Broken Toe', 'Choking', 'Wound', 'Diarrhea', 'Frostbite', 'Heat Exhaustion', 'Heat Stroke', 'Insect Bites', 'Nose Bleed', 'Pulled Muscle', 'Rectal Bleeding', 'Sun Burn', 'Testicle Pain', 'Vertigo', 'Normal Bleeding', 'Eye Injury', 'Chemical Burn', 'Poison', 'Teeth Issues', 'Seizure', 'Head Injury', 'Fainting', 'Headache', 'Cold', 'Rash', 'Snake Bite', 'Animal Bite', 'Drowning', 'CPR', 'Fracture'.

## System Design
![System Design](path_to_system_design_image)

## Flow Chart
![Flow Chart](path_to_flow_chart_image)

## Conclusion
With this health issue identification chatbot, users can interact with the bot to understand their health issues better. The bot categorizes the health issue based on predefined categories and provides appropriate advice or directs the user to seek further assistance.

### Key Points
- Developed an end-to-end system from user input to health issue identification.
- Implemented function calling for expanding the chatbot's capabilities.
- Improved user interaction by asking relevant questions to understand the health issues better.
- Provided a clear and structured approach for categorizing health issues.

### Areas of Improvement
- Expanding the dataset to include more health issues and their solutions.
- Improving the chatbot's ability to understand and categorize complex health issues.
- Enhancing the feedback mechanism to better understand user satisfaction.

### Contact
Created by [Your Name] - feel free to contact me!