# Godot Python MMO
This is a fork of a project from Tristan Batchler for which he has a series of awesome blog posts and YouTube videoes. Find more about that here: https://tbat.me/2022/11/20/godot-python-mmo-part-1.html

![Screenshot from 2023-07-07 07-08-22](https://github.com/wsankey/Godot-Python-MMO/assets/3376159/efd718f6-fb14-4592-b27e-2650ead7befc)

## Getting started
This project uses Poetry as its dependency manager, and the code is written in Python 3. Here's a guide to help you set up your local development environment.

### Prerequisites
Ensure you have Python 3 installed. Install Poetry if you haven't already. Instructions can be found ![here](https://python-poetry.org/docs/#installing-with-the-official-installer)
Setup

1. Clone the Repository
2. Create a Virtual Environment: `python3 -m venv env`
3. Activate the Virtual Environment: `source env/bin/activate`
4. Run `poetry install` This will install all of the dependencies defined in pyproject.toml.


### Running the client
Download Godot 4.0+ and load the client into it.

### Running the server
After installing and activating your local environment, you can run the server with `python server/` or by navigating into the `server/` directory and running `python .`
