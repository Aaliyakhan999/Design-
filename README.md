# Laptop_Price_Prediction  

This project aims to provide a comprehensive machine learning-based web application to predict laptop prices based on various features like brand, processor, RAM, storage, and other technical specifications. The application is designed to assist users in understanding and comparing laptop prices effectively, enabling informed purchasing decisions.  

## Features  

- **Custom Dataset**: The dataset was compiled from publicly available laptop listings and cleaned for optimal machine learning model training. It includes key features such as brand, processor type, RAM, storage capacity, screen size, and more.  
- **Machine Learning Model**: A regression model is used to predict the price of laptops based on their specifications.  
- **User-Friendly Interface**: Frontend developed using HTML, CSS, and JavaScript for a responsive and interactive user experience.  
- **Backend**: Built with Django to handle data processing, model integration, and secure handling of user inputs.  
- **SQLite Database**: Efficiently stores user data and prediction results for seamless operation.  
- **Data Visualization**: Insights from the dataset and model predictions are presented through visualizations to improve usability.  
- **Dynamic Prediction Form**: Users can input laptop specifications, and the application predicts the approximate price.  

## How It Works  

1. Users input laptop specifications through an intuitive form on the web application.  
2. The data is passed to a trained regression model for prediction.  
3. The application displays the predicted price of the laptop in a clear and concise format.  
4. Users can explore insights from the dataset through integrated visualizations.  

## Technology Stack  

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Django  
- **Database**: SQLite  
- **Machine Learning**: Regression Model (trained on laptop dataset)  

## Requirements for the Project  

### Software Requirements  

- **Django Framework**:  
  - Version: 4.x or higher  
  - Reason: Utilizes modern Django features for improved backend functionality.  
- **Python**:  
  - Version: 3.10 or higher  
  - Reason: Ensures compatibility with advanced libraries and type hints.  

### Libraries  

- **NumPy**: >=1.21.0  
  - For numerical computations required in the regression model.  
- **Pandas**: >=1.3.0  
  - For dataset handling and preprocessing.  
- **Scikit-learn**: >=0.24.0  
  - For training and implementing the regression model.  
- **Matplotlib/Seaborn**: >=3.4.0 / >=0.11.0  
  - For data visualization.  
- **joblib**: >=1.2.0  
  - For saving and loading the trained machine learning model.  

### Frontend  

- **HTML/CSS**: For building user-friendly templates.  
- **Optional**: Bootstrap 5.x for responsive design.  

  

## Steps to Run the Project  

1. Download the project ZIP and extract it.  
2. Open the extracted folder in VSCode.  
3. Open the VSCode terminal.  
4. Run the following commands sequentially:  
   - Navigate to the project folder:  
     ```bash  
     cd laptop_price_prediction
     cd laptop 
     ```
     
   - Run the development server:  
     ```bash  
     python manage.py runserver  
     ```  
5. Open the web application in your browser by visiting `http://127.0.0.1:8000/`.  

## Future Enhancements  

- Integration of advanced machine learning algorithms like XGBoost for better price prediction accuracy.  
- Addition of features like battery life to the prediction model.  
- Deployment of the project on a cloud platform like AWS or Heroku for global accessibility.  
- Enhanced data visualization using tools like Plotly or D3.js.  

---  

Feel free to customize it further based on additional features or technologies in your project. Let me know if you'd like any refinements!
