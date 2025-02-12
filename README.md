# Getting Started with the Canvas API with Python

This script will get you started with interfacing with the Canvas API using Python.

## Getting Started
These instructions will get you a copy of the script up and running on your local machine for use with Canvas and your own API tokens. This script makes a request to the Canvas API that displays basic information about your user profile.

### Prerequisites

1. **Install [Python 3.7 or greater](https://www.python.org/downloads/)**.
2. **Install [Git](https://git-scm.com/downloads)**.

### Installation and execution

*Not sure how to clone a repo? Check out this [helpful guide first!](https://codeburst.io/git-and-github-in-a-nutshell-b0a3cc06458f)*

1. Open command prompt on Mac or command line on Windows.
1. Clone this repo. `git clone https://github.com/bellettichloe/getting-started-with-the-canvas-api-with-python.git`
1. Then cd into the repo. `cd getting-started-with-the-canvas-api-with-python`
1. Run the installation script. `pip install -r requirements.txt` (If you see `bash: pip: command not found`, try using `pip3 install -r requirements.txt`)
1. Generate Canvas API token and copy it to clipboard.
1. Rename the `sample.env` file to `.env`, and add your API token to `CANVAS_API_TOKEN={ADD TOKEN HERE}`.
1. Run the script. `python main.py` (If you see `bash: python: command not found`, try using `python3 main.py`). This should log your Canvas info.


