# Name

 EASY_HTTP_Tokenizer
 
 *This script is provided by [Aculearn Pte Ltd](http://www.aculearn.com/).*
 
 
# Table of Contents
 - [Name](#name)
 - [Description](#description)
 - [Prerequisites](#prerequisites)
 - [Licence](#licence)
 - [See Also](#see-also)

# Description

### Abtract
This script is [SimpleHTTPServer]() in Python3 and some tokenizer such as [Cutkum]() which is used for Thai language. The mechanism is sending word in [POST method]() to defined URL, then get tokenized word from responding.

(picture)

In additional, you can add/edit/modify following [MIT licence](#lience). This open-source is in the start process of development, many of things need to be improved. we are pleasant for receiving any your comments.
###  TODO

To open the simple HTTP Server use this:
```
$ python3.6 easy_http_tokenizer.py 127.0.0.1 6489

```
##### Note that 127.0.0.1:6489 is the IP and port that you set up, if you have own server so it can be used.
To use word tokenizer, use this
```
$ Curl -X POST 127.0.0.1:6489 -m "some text"
```
So, that the output will be like this
```
|some| |text|
```
# Prerequisites
There are 3 prerequisites:
- [Python 3.6](https://www.python.org/downloads/)
	
- [HTTPServer](https://docs.python.org/3/library/http.server.html)
	```
    pip install HTTPSever
    ```
- [Cutkum](https://github.com/pucktada/cutkum)
	```
    pip install Cutkum
    ```
    ##### Note that when installing Cutkum, it's also including tensorflow, numpy, tensorboad, gast, termcolor, grpcio, six, absl-py, protobuf, wheel, astor, werkzeug, html5lib, bleach, markdown and setuptools already. Don't need to install them after. 

# Licence
This code is licensed under the MIT License - see the [LICENSE]() file for details
# See Also

