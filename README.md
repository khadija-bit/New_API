# NEWS_API

#  Author
Khadija Hassan

# Description
This is a website  application that display news source all around the world.it enable a user to catch up news around the world and also the can view a specific articles on the website.

# Live Link
* https://newsbroadcasts.herokuapp.com/

# Setup instruction/ Installation
* git clone https://github.com/khadija-bit/New_API.git

Creating a Virtual Environment
```bash
$ python3.6 -m venv --without-pip virtual

$ curl https://bootstrap.pypa.io/get-pip.py | python

$ source virtual/bin/activate
```
Deactivating a virtual environment
```bash
$ deactivate
```
Installing Flask
```bash
pip3 install Flask
pip install flask-bootstrap
pip install flask-script

```

# Contact Information
Any feedback contact this email  sumeyahassan34@gmail.com

# Technology used
* python3.6
* Flask 
* Bootstrap
* Heroku


# Running the Application
 * Run the application in terminal
  ```bash
       chmod a+x start.sh
       ./start.sh
   ```     
 * Exporting the configuration
 ```bash
      export NEWS_API_KEY=< your apikey >
  ```      
  * Testing the application
  ```bash
   python3.6 manage.py test
   ``` 
    
 # Known bugs   
   they are no bugs 

# LICENSE

MIT License

Copyright (c) [2020] [khadija hassan]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
