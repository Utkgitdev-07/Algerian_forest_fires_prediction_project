# Algerian Forest Fire Prediction

Predict forest fires in Algeria using machine learning. The project uses meteorological data to build models for early fire detection, helping mitigate environmental and economic damage. Includes data preprocessing, model training, evaluation scripts, and result analysis. Contributions welcome!

## Project Overview

Forest fires are a significant environmental concern, causing severe ecological damage and economic loss. This project leverages historical data on forest fires in Algeria to build a predictive model that can forecast the occurrence and severity of fires. Accurate predictions can help authorities take preventive measures.

## Dataset

The dataset used in this project is derived from the Algerian Forest Fires dataset and includes:

- **Date**: The date of the observation.
- **Temperature**: The temperature in degrees Celsius.
- **RH**: Relative Humidity in percentage.
- **Ws**: Wind speed in km/h.
- **Rain**: Rainfall in mm.
- **FFMC**: Fine Fuel Moisture Code.
- **DMC**: Duff Moisture Code.
- **DC**: Drought Code.
- **ISI**: Initial Spread Index.
- **BUI**: Buildup Index.
- **FWI**: Fire Weather Index.
- **Classes**: Fire occurrence (1 for fire, 0 for no fire).

## Project Structure

The repository is structured as follows:

- `dataset/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model building.
- `models/`: Saved machine learning models.
- `results/`: Results and evaluation metrics of the models.
- `README.md`: Project overview and setup instructions.

## Getting Started

To get started with the project, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Utkgitdev-07/algerian-forest-fire-prediction.git
   cd algerian-forest-fire-prediction

2.**Install the required dependencies:**
pip install -r requirements.txt

3. **To Run:**

python application.py
Open your browser and navigate to:

http://127.0.0.1:5000/predictdata
The application will prompt for data input and display the predicted fwi prediction.

## Train the model:
Use the notebooks in the notebooks/ directory to preprocess the data and train the machine learning models.

## Evaluate the model:
Evaluate the model's performance using the evaluation metrics and visualizations provided in the results/ directory.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Special thanks to the contributors of the Algerian Forest Fires dataset. This project was inspired by the need to address the environmental impact of forest fires and improve predictive analytics in ecological data.
