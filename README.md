# ProcessMiningTool
ProcessMiningTool - DPE from Kyongi University
Installation Guide for the Process Mining Tool - DPE


# 1. Introduction
This project aims to provide a web process miner using Django that anyone can use. This tool is up and running right out of the box and has a basic setup you can extend.
The research group developed this tool from the Data and Process Engineering Laboratory at KYONGGI UNIVERSITY. Our laboratory has been established since 1998.

The member of this group deploys this tool includes:
- Professor Kwanghoon Pio Kim. Email: kwang@kgu.ac.kr.
- Ph.D. Candidate ThanhHai Nguyen, Email: nguyenthanhhai@kgu.ac.kr.

We welcome all contributions, so please feel free to fix bugs, improve things, and provide documentation. Just contact us to exchange ideas or send a pull request.

Learn more about us at http://ctrl.kyonggi.ac.kr.

# 2. Installation and using the tool

SYSTEMREQUIREMENT: Gaphiviz and add in to PATH

## For Windows
Step 1: Install Python
First, you need to install Python 3.9 or higher. You can download the latest version of Python from the official website (https://www.python.org/downloads/windows/).

Step 2 Install the Required Packages
The tool has several dependencies that you need to install. Navigate to the root directory of the project and run the following command:
```
pip install -r requirements.txt
```
Step 3: Start the Server
After installing the required packages, start the Django development server by running the following command in the root directory of the project:
```
python manage.py runserver
```
This should start the server at http://localhost:8000.

## For Ubuntu
Step 1: Install Python
First, you need to install Python 3.9 or higher. Open a terminal and run the following commands:
```
sudo apt update
sudo apt install python3
```
Step 2: Install Pip
Next, you need to install Pip, the package installer for Python. Run the following command in the terminal:
```
sudo apt install python3-pip
```
Step 3: Install Required Packages
The tool has several dependencies that you need to install. Navigate to the root directory of the project and run the following command:
```
pip3 install -r requirements.txt
```
Step 44: Start the Server
After installing the required packages, start the Django development server by running the following command in the root directory of the project:
```
python3 manage.py runserver
```
This should start the server at http://localhost:8000.

## For macOS
Step 1: Install Python
First, you need to install Python 3.9 or higher. You can download the latest version of Python from the official website https://www.python.org/downloads/mac-osx/.

Step 2: Install Pip
Next, you need to install Pip, the package installer for Python. Open a terminal and run the following command:
```
sudo easy_install pip
```
Step 3: Install Required Packages
The tool has several dependencies that you need to install. Navigate to the root directory of the project and run the following command:
```
pip install -r requirements.txt
```
Step 4: Start the Server
After installing the required packages, start the Django development server by running the following command in the root directory of the project:
```
python manage.py runserver
```
This should start the server at http://localhost:8000.


##  Congratulations! You have successfully installed the tool on your system.
Now, you can now use the tool with the event log datasets provided in the tool, or download other log sets at https://data.4tu.nl   

If you encounter any issues during installation, please refer to the documentation for Django and Python, or contact us at nguyenthanhhai@kgu.ac.kr.

