VISUAL STUDIO CODE INSTALLATION
1. I updated the package list
sudo apt update

2. Installed the necessary dependencies
sudo apt install software-properties-common apt-transport-https wget

3. Imported the Microsoft GPG key
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -

4. Enabled the VSCode repository
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"

5. Updated the package list again
sudo apt update


6. Installed Visual Studio Code
sudo apt install code

7. Launched Visual Studio Code
code


PYTHON INSTALLATION
1. Updated the package list
sudo apt update

2. Installed Python 3
sudo apt install python3

3. Verified Python installation
python3 --version

4. Installed pip for Python 3
sudo apt install python3-pip

5. Verified pip installation
pip3 --version


MYSQL INSTALLATION
1. Updated the package list
sudo apt update

2. Installed MySQL server
sudo apt install mysql-server

3. Run the security script
sudo mysql_secure_installation

4. Start and enable MySQL service
sudo systemctl start mysql
sudo systemctl enable mysql

5. Verified MySQL service status
sudo systemctl status mysql

6. Logged in to MySQL
sudo mysql -u root -p

VIRTUAL ENVIRONMENT INSTALLATION

1. Created a virtual environment
python3 -m venv myenv

2. Activated the virtual environment
source myenv/bin/activate

3. Installed django within the virtual environment
pip install django


EXTENSIONS
1. Django-Intellisense

Django IntelliSense is a well-received VS Code extension created to enhance your Django development process

2. Python

The Python extension is an essential tool for Python development, including Django. It delivers extensive support for Python, offering functionalities like code completion, debugging, linting, and code formatting
