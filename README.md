# Machine Learning Decision Support Tool for Trauma Activation Level

## Overview

The Machine Learning Decision Support Tool for Trauma Activation Level is designed to assist healthcare professionals in determining the appropriate level of trauma activation required for patient care. This tool leverages machine learning algorithms to predict trauma activation levels based on patient data, enabling more efficient and accurate triage decisions.

## Project Goals

- **Improve Trauma Triage Accuracy:** Use machine learning to enhance the precision of trauma activation level predictions.
- **Optimize Resource Allocation:** Assist in the effective allocation of medical resources by accurately assessing trauma severity.
- **Support Healthcare Professionals:** Provide a decision support system to aid in the rapid and informed triage of trauma patients.

## Features

- **Predictive Modeling:** Utilizes machine learning algorithms to predict trauma activation levels based on patient data.
- **Interactive Dashboard:** Offers an easy-to-use interface for healthcare professionals to input patient information and receive activation level predictions.
- **Data Visualization:** Provides visual representations of predictions and model performance metrics.

## Data

The tool uses patient data, which includes various features relevant to trauma cases. The dataset may include information such as:
- Patient demographics
- Injury specifics
- Vital signs
- Medical history

(Note: Ensure to adhere to all privacy and confidentiality regulations when handling patient data.)

## Installation

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/your-username/trauma-activation-tool.git
   \`\`\`

2. Navigate to the project directory:
   \`\`\`bash
   cd trauma-activation-tool
   \`\`\`

3. Create and activate a virtual environment:
   \`\`\`bash
   python -m venv venv
   source venv/bin/activate   # On Windows use \`venv\\Scripts\\activate\`
   \`\`\`

4. Install the required dependencies:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

## Usage

1. Prepare your data according to the specified format.
2. Run the prediction script:
   \`\`\`bash
   python predict_activation.py --input data/input.csv --output results/output.csv
   \`\`\`

3. Access the interactive dashboard by running:
   \`\`\`bash
   python app.py
   \`\`\`
   and navigate to \`http://127.0.0.1:5000\` in your web browser.

## Contributing

Contributions to the project are welcome! Please follow these guidelines:
- Fork the repository and create a new branch for your changes.
- Make your modifications and ensure tests pass.
- Submit a pull request with a detailed description of your changes.


## Contact

For any inquiries or feedback, please contact:
- **Email:** sjaferia@ur.rochester.edu
- **GitHub:** sohrabjaferian (https://github.com/sohrabjaferian)

## Acknowledgments

- **Project Team:** Sohrab Jaferian, Stephen Drury, Ozlem Gunes, Rishabh Kandoi
- **Advisors:** Ajay Anand
- **Institution:** University of Rochester, Hajim School of Engineering & Applied Sciences" > README.md
