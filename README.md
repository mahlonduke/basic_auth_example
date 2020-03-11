# basic_auth_example
This is an example of how to use basic authentication with the Accelo API.

Basic authentication is great for automated apps and services where you can't use OAuth.


--Directions--
- Register an application in your Accelo account (Configuration -> API -> Register Application)
- Copy your new application's Client ID and Client Secret, and insert them into api_config.py
- Edit basic_auth_example.py and change "deployment" to your deployment name.  Do not include ".accelo.com"
- Run basic_auth_example.py
