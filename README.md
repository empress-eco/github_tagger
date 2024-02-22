<p align="center">
  <a href="https://github.com/empress-eco/github_tagger">
    <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">
  </a>

  <p align="center">
    A user-friendly Flask app that automatically labels your GitHub Pull Requests.
    <br />
    <a href="https://empress.eco/"><strong>Explore the Website »</strong></a>
    <br />
    <br />
    <a href="https://github.com/empress-eco/github_tagger/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/github_tagger/issues">Request Feature</a>
  </p>
</p>

## About The Project

**Github Tagger** is a lightweight and efficient Flask application designed to automate the labeling of your GitHub Pull Requests (PRs). This intuitive tool is perfect for developers handling multiple GitHub repositories who need an efficient, automated system to categorize their PRs.

### Key Features
- Automatic PR labeling
- Easy integration with GitHub via Webhooks
- Configurable via a local environment or server

### Built With
Github Tagger is built using the Flask framework, known for its lightweight, user-friendly structure, and high efficiency.

## Technical Stack and Setup Instructions

### Prerequisites
Ensure you have Python 3 installed on your system to set up a local environment or server for Github Tagger.

### Installation
Use the following steps to clone the repository, set up a virtual environment, install requirements, create a config.json file, and run Flask to listen for webhook calls.

```sh
# Clone the repository
git clone https://github.com/empress-eco/github_tagger.git

# Change working directory
cd github_tagger

# Create a virtual environment using Python 3
python3 -m venv .venv

# Activate virtual environment
source .venv/bin/activate

# Install requirements
pip install -r requirements.txt

# Run flask to listen for webhook calls
export FLASK_APP=tagger
flask run -h 0.0.0.0 -p 8000 --reload --debugger
```

## Usage
After setting up a local environment or server, create a GitHub Webhook that triggers on Status events and sends data to your server. Github Tagger will then automatically label your PRs based on the received data, providing a streamlined and automated labeling process.

## Contribution Guidelines
We welcome and appreciate contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

### License
This project is under the MIT License. All contributions are also licensed under the MIT License.

### Acknowledgements
Special thanks to the Empress Community for their foundational contributions to the essential tools that power this project. Their innovation and dedication have been instrumental in building the functionalities we rely on. We deeply appreciate their pioneering work and ongoing support.