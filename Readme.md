# FastAPI CRUD Application

This repository contains a simple CRUD (Create, Read, Update, Delete) application developed using FastAPI.

## Getting Started

To run the application locally, clone the repository:

git clone https://github.com/kanav-raina/fastapi.git

## Create and activate virtual environment

python3 -m venv env
source env/bin/activate   # On Unix or MacOS
.\env\Scripts\activate    # On Windows

## Install the required dependencies:

pip3 install -r requirements.txt

## Navigate to the fastapi folder and run the application:

uvicorn src.main:app --reload

## Usage

Once the application is running, access the API at http://127.0.0.1:8000/docs to explore the CRUD operations.