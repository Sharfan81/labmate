# LabMate – AI Lab Report Analyzer

LabMate is an AI-powered vision chatbot that analyzes medical lab reports, such as blood tests, CBC, lipid profiles, and thyroid function tests. It explains test results in simple language, highlights values outside reference ranges, and provides general health improvement suggestions.

## Features

* Upload medical lab report images for analysis.
* Identify test values and flag abnormal results.
* Understand results through simple explanations and health suggestions.
* Generate email report summaries.

## Run Locally

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   cd <your-project-folder>
   ```

2. Create and activate a virtual environment (if using Python):

   ```bash
   python -m venv venv
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

   macOS/Linux:

   ```bash
   source venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure your required API keys in a `.toml` file, following the project's environment variable requirements.

5. Start the application using the appropriate command for your framework.

## Disclaimer

LabMate is intended for educational purposes only and does not replace professional medical advice, diagnosis, or treatment. Always consult a qualified healthcare professional regarding your lab results.
