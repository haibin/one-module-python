# one-module-python

```
> pipenv shell
> pip​​ ​​install​​ ​​../one-module-python
```

```
> pipenv --venv
/Users/liuhaibin/.local/share/virtualenvs/one-module-python-9mZH2st4
> cat /Users/liuhaibin/.local/share/virtualenvs/one-module-python-9mZH2st4/lib/python3.6/site-packages/hello.py
def hello():
    return 'hello'⏎
```

```
> python
Python 3.6.5 (default, Apr  4 2018, 10:31:24)
[GCC 4.2.1 Compatible Apple LLVM 9.1.0 (clang-902.0.39.1)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> from hello import hello
>>> hello()
'hello'
>>>
```