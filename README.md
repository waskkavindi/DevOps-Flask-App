# DevOps Flask Application

## Project Description
This project is a simple web application developed using Python and Flask. It demonstrates basic DevOps practices, including automated testing and Continuous Integration (CI) using GitHub Actions.

## Technologies Used
- Python
- Flask
- PyTest
- Git & GitHub
- GitHub Actions
- YAML

## Project Structure

```text
devops-practical/
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── app.py
├── test_app.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/waskkavindi/DevOps-Flask-App.git
```

2. Navigate to the project folder:

```bash
cd DevOps-Flask-App
```

3. Install the dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

```bash
python app.py
```

## Run Automated Tests

Run the following command to execute the tests using PyTest:

```bash
pytest
```

## Continuous Integration (CI)

This project uses GitHub Actions to automate the testing process.

The CI pipeline performs the following steps:

1. Checks out the source code.
2. Sets up Python.
3. Installs project dependencies.
4. Runs automated tests using PyTest.

## Author

**Sachini Kaveesha**

GitHub: [waskkavindi](https://github.com/waskkavindi)

## License

This project is created for educational purposes.