# gremlin
Web traffic generator for form filling test load generation.

Written for a simple Django web form, this script creates a random user profile and then fills out the form.

To use:

Create a virtual environment (or not)

Install requirements
  pip install -f requirements.txt
  
Usage: python traffic.py -u1 "http://1.1.1.1/signup/" -u2 "http://2.2.2.2/signup/"

Only one url needed

