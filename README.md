# Disease Diagnoser

This project is an interactive web application that predicts possible disease diagnoses based on user-input symptoms. It utilizes machine learning models trained on a dataset of symptoms and corresponding diseases.

## Features

- Users can input up to 4 symptoms and receive possible diagnoses.
- The application displays the percentage chance of each diagnosis according to the trained model.
- It includes a frontend web page for user interaction and a backend server written using Flask to process symptoms and provide predictions.

## Technologies Used

**Frontend:** HTML, CSS, JavaScript

**Backend:** Flask (Python Web Framework)

**Machine Learning:** Scikit-learn

**Data Analysis:** Pandas, NumPy

## Local Deployment

1. Clone the repository: `git clone https://github.com/your-username/disease-diagnoser.git`

2. Navigate to the project directory: `cd disease-diagnoser`

3. Install the required Python packages using pip: `pip install flask pandas scikit-learn`

4. Run the Flask server: `python app.py`

5. Open your local environment: `http://localhost:5000/` or `http://127.0.0.1:5000/`

6. Click `Learn more` to see what symptoms and diseases the model used to train

7. Enter up to 4 symptoms in the input fields and click the submit button.

8. The application will send an AJAX request to the backend server, process the symptoms, and display the diagnosis results with percentage chances on the page.

## Demo

[Provide a link to a live demo of the project, if available]

## Roadmap

- Add functionality to display the percentage chance of each diagnosis according to the trained model.
- More to come

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and commit them.

4. Push your changes to your forked repository.

5. Submit a pull request with a detailed description of your changes.

## License

MIT License

## Acknowledgements

- Kaggle dataset used for training the machine learning models: [Disease Prediction using Machine Learning(https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning/code)]





