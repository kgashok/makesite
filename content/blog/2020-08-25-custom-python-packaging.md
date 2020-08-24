
# Sandbox to try ThinkPy2 code 

In [https://github.com/kgisl/pythonFDP](https://github.com/kgisl/pythonFDP), in the `/sandbox` directory, in your code, or in IDLE prompt, do this:

```bash 
>> from thinkpy2.has_duplicates import *
>> has_duplicates([1, 2, 3, 1])
True
```

## How it was created 

0. This was created by following the instructions on https://j.mp/stepsPackage

1. After Steps 1-4: 

```
/sandbox
    /thinkpy2
        __init__.py
        # module files
    setup.py
```

2. Added to `setup.py`

```
from setuptools import setup

setup(name='sandbox',
      packages=['thinkpy2'],
      )
```

3. created a sample `some_code.py` with `test_fun` code in it.


Or even better, just skip all the above steps and simply use the script [`make_my_package.py`](https://github.com/kgisl/pythonFDP/blob/6d0f662cdc7c9ac1aaa4a1ef641d74401a4b18b4/code/make_my_package.py) 

    usage: python3 make_my_package.py <your_package_name>

4. At the level of the `/sandbox` directory, type:  

    ```pip3 install -e . ```

That's it! You are all set! 
