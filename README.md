# CoWIN vaccination slot availability using Python

Script to check the available slots for Covid-19 Vaccination Centers from CoWIN API in India. This CANNOT book slots automatically. The Indian Government had blocked the API for crawlers, but we are good to go.

<!---
[Click to view the Website](https://bit.ly/3ob9l94)
-->

The [CoWin API](https://apisetu.gov.in/public/marketplace/api/cowin) currently states : "Further, these APIs are subject to a rate limit of 100 API calls per 5 minutes per IP".
&nbsp;
# Update
I am humbled to see the overwhelming response that this project has received so far. Feel free to create amazing applications on top of this project. Due to my schedule, I won't be able to allot more time to this project. So there won't be any additional commits to this project.

# Installing Python
Python is a programming language that is powerful but easy to learn. It is free, platform-independent, and popular among scientists.

## Recommended Method: Anaconda
The Anaconda Python distribution is an easily-installable bundle of Python and many of the libraries used throughout this class. Unless you have a good reason not to, we recommend that you use Anaconda.

### Mac/Linux users
1. Download the [appropriate version](https://www.anaconda.com/products/individual) of Anaconda
1. Follow the instructions on that page to run the installer
1. Test it out: open a terminal window, and type ``python``, you should see something like
```
Python 3.8.3 (default, Jul  2 2020, 17:30:36) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32
```
If `Anaconda` doesn't appear on the first line, you are using a different version of Python. See the troubleshooting section below.

1. Test out the IPython notebook: open a Terminal window, and type `ipython notebook`. A new browser window should pop up. 
1. Click `New Notebook` to create a new notebook file
1. Update IPython to the newest version by typing `conda update ipython` at the command line

### Windows Users
1. Download the [appropriate version](https://www.anaconda.com/products/individual) of Anaconda
1. Follow the instructions on that page to run the installer. This will create a directory at `C:\Anaconda`
1. Test it out: start the Anaconda launcher, which you can find in `C:\Anaconda` or, in the Start menu. Start the IPython notebook. A new browser window should open. 
1. Click `New Notebook`, which should open a new page.
1. Update IPython to the newest version by opening a command prompt, and typing `conda update ipython`

# Usage
- Clone the repository.
- The tool only works with Indian IP addresses so disconnect your VPN if needed.
- Enter the command - `cd cowin-vaccination-slot-availability-main/`
- Install all the dependencies - `pip3 install -r requirements.txt`
- Run the python application - `streamlit run app.py`
&nbsp;


