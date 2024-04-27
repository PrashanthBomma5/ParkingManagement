# ParkingManagement
This is a Django-based web application for managing parking lots. It provides functionalities to track parked vehicles, manage parking slots, categorize vehicles, and generate reports.
Features
User Authentication: Secure login and logout functionality for authorized access to the system.
Dashboard: Overview of key statistics such as total parked vehicles, available categories, earnings, etc.
Vehicle Management: Add, edit, and delete vehicles with details like vehicle number, type, parking area, and charge.
Category Management: Manage parking categories including types, limits, and charges.
Parking Status: View the current status of parked vehicles including arrival time, vehicle type, and parking charge.
Reset Password: Ability for users to securely reset their passwords.
Search Functionality: Search vehicles and categories by various parameters.
Reports: Generate reports based on vehicle types, available slots, and other relevant metrics.
Usage
Installation: Clone the repository and install dependencies using pip.
bash
Copy code
git clone https://github.com/PrashanthBomma5/ParkingManagement.git
cd  ParkingManagement
pip install -r requirements.txt
Database Setup: Configure your database settings in settings.py and run migrations.
bash
Copy code
python manage.py makemigrations
python manage.py migrate
Run Server: Start the Django development server.
bash
Copy code
python manage.py runserver
Access: Open your web browser and navigate to http://localhost:8000 to access the application.
Contributors
Bomma Prashnath
