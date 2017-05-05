# pypassport-2.0
Taken from epassportviewer and added support for Dutch ECDSA Active Authentication

## pyPassport Installation Instructions

Until pyPassport reach a stable state the installation has to be done from source. Later binary packages will be released for the following platforms:

Windows (.exe)
Linux (.deb/.rmp)
Mac OSX (if possible, mpkg/dmg?)
Sources

## Supported platforms

Any platform capable of running Python 2.5/2.6 (and C based module). pyPassport has been successfully installed from sources on Windows, Linux (Ubuntu) and Mac OSX.

## Dependencies

pyPassport is build on top of some other open-sources libraries. All of them are mandatory to use pyPassport.

pyPassport also uses other open-source tools to perform specific processing, installing those tools is not mandatory. However, if those optional tools are not installed pyPassport functionalities are reduce.

## Mandatory

The following packages are required to run the application.

List of other dependencies: python 2.5 or 2.6.
List of python dependencies: pyasn1, pyscard, pycrypto, setuptools.
Python dependencies can be installed using the code sharing python platform PyPI using the following command:
```
Python/scripts$ easy_install package_name
```
To install pyscard on MAC OSX you can use this mpkg file

## Optional

To complete the installation, two additional packages should be installed:

OpenSSL for certificate verification; (already included in Mac OSX)
geoJasper to manipulate images in JPEG2000 format;
Offline installation

Please use the python installer script to install pypassport with the following command:
```
$ python setup.py install
```
All files will be installed in the $PythonDir/sites-packages/pypassport directory, ready to be imported in your project.

## Online installation

Once the software reach a stable state, code will be posted on the code sharing python platform PyPI.
