# codeclause_pdf_to_word_converter
The PDF to Docs Converter is a Python Flask project that allows users to convert PDF files to Microsoft Word document files (Docs). The project's main file is `app.py`, which serves as the entry point for the Flask web application.

The application is built using Python Flask and uses the `pdfminer` and `docx` libraries to convert the PDF files to Docs files. When a user uploads a PDF file, the application processes the file and converts it to a Docx file, which is then available for download.

The project includes a user-friendly interface that allows users to upload PDF files, track the progress of the conversion, and download the converted Docs file once the conversion is complete.

To run the Flask project, follow these steps:

1. Clone the project from GitHub or download the ZIP file and extract it to a directory.
2. Open a terminal or command prompt and navigate to the directory containing the project files.
3. Create a virtual environment by running the following command: `python3 -m venv env`
4. Activate the virtual environment by running the command based on your OS:
   - Windows: `env\Scripts\activate.bat`
   - Linux/MacOS: `source env/bin/activate`
5. Install the project requirements by running the following command: `pip install -r requirements.txt`
6. Set the Flask app environment variable by running the command based on your OS:
   - Windows: `set FLASK_APP=app.py`
   - Linux/MacOS: `export FLASK_APP=app.py`
7. Run the Flask app by running the following command: `flask run`
8. Open a web browser and navigate to `http://localhost:5000` to access the PDF to Docs Converter.

With these steps, you should be able to run the Flask project and convert your PDF files to Docs files
