# Name

 EASY_HTTP_Tokenizer
 
 *This script is provided by [Aculearn Pte Ltd](http://www.aculearn.com/).*
 
 [Back to TOC](#table-of-contents)
# Table of Contents
 - [Name](#name)
 - [Description](#description)
 - [Prerequisites](#prerequisites)
 - [Licence](#licence)
 - [See Also](#see-also)
[Back to TOC](#table-of-contents)
# Description

### Abtract
This script is [SimpleHTTPServer](https://docs.python.org/2/library/simplehttpserver.html) in [Python3](https://www.python.org) and tokenizer that is[Cutkum](https://github.com/pucktada/cutkum) which is used for Thai language. The mechanism is sending word in [POST method](https://en.wikipedia.org/wiki/POST_(HTTP)) to defined URL, then get tokenized word from responding.

![](https://raw.githubusercontent.com/dobybros/EasyHttpTokenizer/master/ez_http_tokenizer_diagram.jpg#center)

In additional, you can add/edit/modify under [MIT licence](https://github.com/dobybros/EasyHttpTokenizer/blob/master/LICENSE). This open-source is in the starting process of development, many of things need to be improved. we are pleasant for receiving any your comments.
###  TODO

To open the simple HTTP Server, use this:
```
$ python easy_http_tokenizer.py 6489 127.0.0.1

```
##### Note that 127.0.0.1:6489 is the IP and port that you set up, if you have own server so it can be used.
To use word tokenizer, use this:
```
$ curl -X POST 127.0.0.1:6489 -d ผมเป็นคนไทย
```
So, that the output will be like this
```
|ผม|เป็น|คนไทย|
```
[Back to TOC](#table-of-contents)
# Prerequisites
There are 3 prerequisites:
- [Python 3.0+](https://www.python.org/downloads/)
	
- [HTTPServer](https://docs.python.org/3/library/http.server.html)
	```
    pip install HTTPSever
    ```
- [Cutkum](https://github.com/pucktada/cutkum)
	```
    pip install Cutkum
    ```
    ##### Note that when installing Cutkum, it's also including tensorflow, numpy, tensorboad, gast, termcolor, grpcio, six, absl-py, protobuf, wheel, astor, werkzeug, html5lib, bleach, markdown and setuptools already. Don't need to install them after. 

[Back to TOC](#table-of-contents)

# Licence
This code is licensed under the MIT License - see the [LICENSE](https://github.com/dobybros/EasyHttpTokenizer/blob/master/LICENSE) file for details

[Back to TOC](#table-of-contents)
# See Also
- [SimpleHTTPHandler](https://docs.python.org/3.7/library/http.server.html?highlight=simplehttp)

[Back to TOC](#table-of-contents)
