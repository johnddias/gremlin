# gremlin
Web traffic generator for form filling test load generation.

Written for a simple Django web form, this script creates a random user profile and then fills out the form.

To use:

Create a virtual environment (or not)

Install requirements
  pip install -f requirements.txt
  
Usage: python traffic.py -u1 "http://52.53.160.113/signup/" -u2 "http://54.219.132.182/signup/"

Only one url needed

