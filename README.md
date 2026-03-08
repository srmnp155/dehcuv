# Flask To-Do List

This is a simple Flask To-Do List application ready for deployment on Azure App Service.

## Running Locally

1. Create a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:

   ```bash
   python app.py
   ```

4. Open your browser at `http://localhost:5000`

## Deploying to Azure App Service

1. Create an Azure App Service for Python.
2. Push this repository to your Azure remote.
3. Set the startup command to `python app.py`.
4. Ensure the `requirements.txt` is present for dependency installation.

The app will be available at your Azure App Service URL.
