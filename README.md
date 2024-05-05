# passwordevolution
This project aims to predict and optimize a given 9-digit random password using evolutionary algorithms.

How It Works
The project performs the password prediction and optimization process using evolutionary algorithms. First, a 9-digit random password is generated. Then, in each generation, a population is created for password prediction, crossover and mutation operations are applied, and the penalty coefficient is calculated. The closest predictions are selected, and the process is repeated in each generation. Our goal is to bring the penalty coefficient closer to 0 in each generation until it reaches 0 or as close as possible to 0.

Installation
To run the project on your local machine, follow these steps:

1-Clone this repository:
git clone https://github.com/OguzAyd1n/passwordevolution.git

2-Navigate to the project directory:
cd passwordevolution

3-Install the required dependencies:
pip install -r requirements.txt

Usage
You can start the project by running the main.py file in the project directory:

python main.py

Contributions
If you would like to contribute, please open a pull request. For major changes, please open an issue first to discuss.

License
This project is licensed under the MIT License. See the LICENSE file for more information.

