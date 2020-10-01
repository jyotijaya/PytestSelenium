1. Pytest Selenium
This sample project would allow you to understand basic pytest run along with Allure reporting

Please make sure you have Python, Java installed on your machine beforehand

2. How to install pytest
1. pip install pytest

3. How to install allure
1. Download allure commandline from: https://mvnrepository.com/artifact/io.qameta.allure/allure-commandline/2.8.1
2. Unzip the directory and put the path of bin to PATH in environment variables
3. pip install allure-pytest

4. How to install selenium
1. pip install selenium

5. How to configure jenkins
Manage Jenkins -> Manage Plugins -> Python and Allure
Also add Allure commandline path in Global Tools Configuration

6. How to setup PyCharm
Install plugins in Pycharm explicitly for pytest, selenium and allure

7. How to run the code via cmd
pytest -v -s --alluredir=path to your report folder <test_filename.py>
