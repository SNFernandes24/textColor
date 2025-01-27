# textColor

This is an easy to use Python library which allows you to make your terminal outputs more colorful and therefore easier to read and understand.

It currently only works with Python3

The creator and maintainer is Jannik Ramrath (jramrath)

GitHub: https://github.com/jramrath/textColor

PiPy: https://pypi.org/project/textColor/


# Installation

This library is hosted on [pypi.org](https://pypi.org/project/textColor/). You can install it with **pip**:

`pip install textColor`


# Usage

To use this library, you first have to import it:
```
from textColor import tc
```

To print colored text do the following:
```
print(tc.green("GREEN"))           # 'GREEN' will be green
print(tc.green("RED"))             # 'RED' will be red
print(tc.green("BLUE"))            # 'BLUE' will be blue
print(tc.green("YELLOW"))          # 'YELLOW' will be yellow
```

You can also use special 'pre-fixes':
```
print(tc.input("Name: "))          # will output '[?] Name: '  while '[?]' is yellow
print(tc.info("Info"))             # will output '[-] Info'    while '[-]' is blue
print(tc.error("ERROR"))           # will output '[!] ERROR'   while '[!]' is red
print(tc.output("Success"))        # will output '[>] Success' while '[>]' is green
```



# License

This library was published under the **GNU General Public License**. For more information take a look at the **LICENSE** file.


# Contributing

If you've found a bug or a typo, feel free to open an Issue on GitHub. Already have a solution? Make a Pull request and I'll take a look at your changes.