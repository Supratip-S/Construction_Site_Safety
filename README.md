# Construction Site Safety Project

## Overview
The Construction Site Safety project aims to enhance safety measures on construction sites by utilizing computer vision techniques. This project leverages the YOLO (You Only Look Once) framework to detect safety equipment and personnel compliance in images captured from construction sites.

## Project Structure
```
construction-site-safety
├── src
│   └── construction-site-safety.ipynb  # Main code for data processing, model training, and predictions
├── requirements.txt                      # Python dependencies required for the project
├── Dockerfile                             # Instructions to build the Docker image
└── README.md                              # Documentation for the project
```

## Setup Instructions
1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd construction-site-safety
   ```

2. **Build the Docker Image**
   Ensure you have Docker installed and running. Build the Docker image using the following command:
   ```bash
   docker build -t construction-site-safety .
   ```

3. **Run the Docker Container**
   After building the image, run the container with the following command:
   ```bash
   docker run -p 8888:8888 construction-site-safety
   ```

4. **Access Jupyter Notebook**
   Open your web browser and navigate to `http://localhost:8888` to access the Jupyter notebook interface.

## Usage Guidelines
- Open the `src/construction-site-safety.ipynb` notebook to start processing data, training the model, and making predictions.
- Ensure that the necessary datasets are available in the specified directories as outlined in the notebook.

## Dependencies
The project requires the following Python libraries:
- numpy
- pandas
- matplotlib
- seaborn
- ultralytics
- other necessary libraries as specified in `requirements.txt`

## License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.
