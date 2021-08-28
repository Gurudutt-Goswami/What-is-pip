# What is pip ? (Ref: Python)

Python pip is the package manager for Python packages. We can use pip to install packages that do not come with Python. The basic syntax of pip commands in command prompt is: 
```
pip install flask
```
##### Specifying Package Version
We can also install the package of a specific version by using the below command.
```
pip install package_name==version
```
##### List installed packages with pip
The Python pip list command displays a list of packages installed in the system. 
```
pip list
```
##### Uninstall packages with pip
The Python pip uninstall command uninstalls a particular existing package. 
```
pip uninstall numpy
```
##### Listing additional packages with pip
The Python pip freeze command is used to list packages that don’t come pre-installed with Python. 
```
pip freeze
```
##### Listing Outdated Packages with pip
Python pip list –outdated command is used to list all the packages that are outdated. This command cross-checks the installed package information with the pip repository.
```
pip list --outdated
```
##### Upgrading packages with pip
Python pip install –user –upgrade is used to update a package.
```
pip install --user --upgrade package_name
We can also upgrade any package to a specific version using the below command.
pip install --user --upgrade package_name==version
```
##### Downgrading packages with pip
The Python pip install –user command is used to downgrade a package to the specific version.
```
pip install --user package_name==version
```
