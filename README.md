This project is a Medicine Information System that allows users to interact with a voice-controlled application for querying medicine details. The system uses speech recognition to capture the user's input, identifying the medicine name and dosage. It then matches the name using fuzzy matching to provide the top 5 closest medicine names and their corresponding details, such as price, side effects, and substitutes. The project utilizes a machine learning model to predict the therapeutic class of the medicine.

Key Features:
Voice Recognition: The system listens to the user’s input and transcribes it to text.
Fuzzy Matching: Even partial or misspelled medicine names are matched to the closest possible results.
Medicine Details: For the matched medicines, information like price, side effects, and substitutes is displayed.
Machine Learning Integration: Uses a model to predict the therapeutic class of the medicine based on the input features.


STEPS ON HOW TO RUN THE CODE
Clone the Repository: https://github.com/kaurgunisha7/MedocProject
Extract the zip files wth the same name in the same folder as the project.
Install dependencies: pip install -r requirements.txt
Use the Program:
Speak the medicine name and dosage when prompted.
View the results (matching medicines, side effects, and substitutes).
