
# Credity

a web-based credit card rating model that predicts the creditworthiness of applicants based on their submitted information. This project aims to provide a user-friendly interface for users to input their data, receive a credit rating prediction, and view the result conveniently.


## Model architecture

![App Screenshot](https://github.com/anuragsinha03/credity/blob/main/static/images/architecture.jpg?raw=true)



## How to Run

To run the Flask app locally, follow these steps:

1. Install virtualenv:
    ```bash
    pip install virtualenv
    ```

2. Create a Python virtual environment:
    ```bash
    virtualenv venv
    ```

3. Activate the virtual environment:
    - Windows:
        ```bash
        venv\Scripts\activate
        ```
    - Linux:
        ```bash
        source ./venv/bin/activate
        ```

4. Install the required dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```

5. Start the Flask app:
    ```bash
    python app.py
    ```

6. Open your web browser and go to `http://localhost:5000` to view the website.


## Model Training

The `train_model.py` file contains the code for training the machine learning model used in the application.
We have used the RandomForest algorithm for classification

## Referencing Documentation

You can refer to the `documentation.docx` file located in the project directory for additional documentation and information.

## Website Screenshots

![Screenshot 1](screenshots/hero.png)
*MAIN SECTION*

![Screenshot 2](screenshots/why.png)
*WHY SECTION*

![Screenshot 3](screenshots/parameters.png)
*PARAMETERS SECTION*

![Screenshot 4](screenshots/ss.png)
*PREDICTOR SECTION*

![Screenshot 5](screenshots/ss2.png)
*PREDICTOR SECTION*

![Screenshot 6](screenshots/ss3.png)
*PREDICTOR SECTION*

![Screenshot 7](screenshots/help.png)
*HELP SECTION*

## Contributors

- Shubham Sinha (https://www.linkedin.com/in/shubhamsinhaaa/)
- Anurag Sinha (https://www.linkedin.com/in/anuragsinha03/)
- Darshan Balar (https://www.linkedin.com/in/darshan-balar-4302141bb/)

## Additional Notes
- Ensure that you have Python and pip installed on your machine.
- Customize the Flask app according to your specific requirements.

## License
This project is licensed under the [MIT License](LICENSE).


