# Restaurant Reviews

## Project Overview: Stage 1

For the **Restaurant Reviews** project, I incrementally converted a static webpage to a mobile-ready web application. In **Stage One**, I took a static design that lacks accessibility and converted the design to be responsive on different sized displays and accessible for screen reader use. I also added a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

The initial code had a lot of issues: barely usable on a desktop browser, much less a mobile device. It also didn’t include any standard accessibility features, and it didn’t work offline at all. The aim of the project was to update the code to resolve these issues while still maintaining the included functionality. 

### How to set up the application? 

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`.





