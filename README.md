# API Watch House
A web app designed to secure credentials in scripts.

## Description
Instead of placing API credentials directly in scripts, API Watch House is designed to be an intermediary between a script and an API endpoint.
By adding an additional layer of security controls and logging, API Watch House helps to secure scripting.

## Features
* API Watch House allows filtering connections by IP, country, and time window. 
* All API requests are routed through API Watch House, allowing precise IP restrictions on the source application.
* Logging to an external log source for further accountability.
* API credentials are not stored in API Watch House, only the encryption key for each API credential.
