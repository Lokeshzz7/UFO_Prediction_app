# 🛸 UFO Appearance Prediction 

Predict the country where a UFO sighting is likely based on input parameters: seconds, latitude, and longitude.

## Overview

This app uses user inputs to predict which country is most likely to report a UFO sighting. It features a clean, modern UI with smooth animations and a dark, space-themed design to enhance the user experience.

## Features

* **Input form** for seconds, latitude, and longitude.
* **Predictive output** displaying the most likely country for a UFO sighting.
* **Responsive and accessible UI** optimized for desktop and mobile.
* **Floating label inputs** with smooth focus animations.
* Modern dark theme with vibrant highlight colors.

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/Lokeshzz7/UFO_Prediction_app.git
cd ufo-prediction-app
```

2. **Set up a virtual environment**

```bash
python3 -m venv venv
On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the app**

```bash
flask run
```

5. **Open your browser**

Visit `http://127.0.0.1:5000` to access the app.

## Usage

* Enter values for **seconds**, **latitude**, and **longitude**.
* Click the **Predict Country** button.
* The app will display the predicted country likely to report a UFO sighting.

## Technologies Used

* Python
* Flask (backend framework)
* HTML5, CSS3 (frontend)
* Jinja2 templating engine

## Folder Structure

```bash
/static
  /css
    - styles.css
/templates
  - index.html
app.py
requirements.txt
README.md
```

## Customization

* Modify CSS in `/static/css/styles.css` to change the look and feel.
* Update the prediction logic in `ufo.ipynb` to improve prediction accuracy.

## Contributing

Feel free to open issues or submit pull requests for improvements or bug fixes.

## License

This project is open source and available under the MIT License.
