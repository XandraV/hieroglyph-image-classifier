# Hieroglyph Image Classifier

Image classifier project that combines React frontend (TypeScript, Material-UI) with a Flask(Python) backend that allows the user to upload and identify a hieroglyph. The predictive model was built byusing Python and TensorFlow.

![app](app/hieroglyph-react/src/assets/readme.png)

Frontend source code can be found [here](https://github.com/XandraV/hieroglyp-image-classifier/tree/master/app/hieroglyph-react).

Backend source code can be found [here](https://github.com/XandraV/hieroglyp-image-classifier/tree/master/app/backend/).

[Data folder](https://github.com/XandraV/hieroglyp-image-classifier/tree/master/data) contains the data that was used in `hieroglyp_identifier.ipynb` to create the model in `saved_model.h5`.

## Installation

Clone the master branch and then run the following scripts in the project directory:

- `npm install` - to install relevant dependencies

- `npm start` - start the react app

You will need to have the latest version of Python 3, pip and Flask on your machine. [Here](https://flask.palletsprojects.com/en/1.1.x/installation/) you can find the official guide on how to set up a flask server.

## Resources

| Description                                                        | Link                                                                      |
| :----------------------------------------------------------------- | :------------------------------------------------------------------------ |
| Material-UI components - a popular React UI framework              | [Material-UI docs](https://material-ui.com/getting-started/installation/) |
| Library that utilises tagged template literals to style components | [styled components](https://styled-components.com/)                       |
| Flask web application framework                                    | [Flask](https://flask.palletsprojects.com/en/1.1.x/)                      |
| React - JavaScript library for building user interfaces            | [create-react-app](https://github.com/facebook/create-react-app)          |
