# PythonTriCities demo starthere.

This is a simple demo to make sure our users have Python3 set up and working

### Prerequisites

* python3 (Python is an open source general progarmming language https://wiki.python.org/moin/)
* git (Git is a version control system https://en.wikipedia.org/wiki/Git)
* Also an editor of your choice to look at the code https://wiki.python.org/moin/PythonEditors

## Getting Started

1. Make sure you have Python3 installed.  Follow these guides:
  * [Linux Box:](https://docs.python.org/3/using/unix.html)
  * [Windows Box:](https://docs.python.org/3/using/windows.html)
  * [macOS box:](http://docs.python-guide.org/en/latest/starting/install3/osx/)
  
2. Make sure you have git installed.
  * [How to install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  
### Clone this repository

```
git clone https://github.com/PythonTriCities/starthere.git
```
* If you had trouble with the git install or just want to download the files as a zip, click this link [starthere](https://github.com/PythonTriCities/starthere/archive/master.zip)

### The next 2 steps are optional but recommended

3. Create the virtual environment if it doesn\'t exist:
  * [What/'s a virtual environment?](https://docs.python.org/3/library/venv.html)

* On Linux/Mac it is: python3 -m venv /path/to/new/virtual/environment

 * I like to set the path to be in the directory with a folder that shows the  version of Python that I am running, so I include the python version I am using in the path

```
python3 -m venv ./.venv/python3.6
```
* On Windows it is c:\>c:\Python35\python -m venv c:\path\to\myenv

```
c:\>c:\Python35\python -m venv c:\path\to\myenv
```

4. Start your virtual environment.

* Linux/Mac:

```
source ./.venv/bin/activate
```

* Windows:

```
c:\path\to\myenv\Scripts\activate.bat
```

5. Test that it is not legacy Python, ie 2.7

```
python --version
```
* You should see something like this:
```
Python 3.6.4
```

6. Now from the starthere folder run the first.py script
```
python first.py
```
* If all went well you should see:
```
Please type in a name: 
```

## Running the tests

No test for this script, but we will cover that in later examples

## Versioning

Use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/PythonTriCities/starthere.git/tags).

## Authors

* **John M** - *Initial work* - [TechSolX](https://github.com/techsolx)

See also the list of [contributors](https://github.com/PythonTriCities/starthere/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Help from the internets, stackoverflow, users group members, etc...

## Test your git ability by adding your Github link here:

#### [Amy wuz here](https://github.com/akaamy1)

