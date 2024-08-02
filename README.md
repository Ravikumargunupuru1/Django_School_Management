# Django School Management

## Instructions: How to Run

### Prerequisites
Before you begin, ensure you have the following installed:
- Python (version 3.12.4(current version))
- pip (Python package installer)

### Setup Instructions

1. **Download the Project**
   - Download and unzip the project file.

2. **Navigate to Project Folder**
   - Open your terminal or command prompt.
   - Change directory to the root folder of the project using:
     
     cd /path/to/project/root
     

3. **Create a Virtual Environment (Optional but Recommended)**
   - Create a virtual environment by running:
     
     python -m venv 'Here give your environment name'env
     
   - Activate the virtual environment:
     - **On Windows:**

       venv\Scripts\activate

     - **On macOS/Linux:**

       source venv/bin/activate
    

4. **Install the Requirements**
   - Install the required packages using:

     pip install -r requirements.txt


5. **Apply Database Migrations**
   - Make the necessary migrations by running:
    
     python manage.py makemigrations

   - Apply the migrations with:
    
     python manage.py migrate
    

6. **Run the Application**
   - Start the Django development server by executing:
    
     python manage.py runserver


7. **Access the Application**
   - Open your web browser and go to the following URL:

     http://127.0.0.1:[PORT_NUMBER]/

     Replace `[PORT_NUMBER]` with the port number specified by the Django server (default is 8000).

8. **Admin Login**
   - To access the admin panel, you need to create a superuser.
   - Run the following command to create a superuser:

     python manage.py createsuperuser

   - Follow the prompts to set up your admin credentials.

### Additional Information
- **Documentation:** For more details about the project and its features, refer to the project documentation included in the `docs` folder.
