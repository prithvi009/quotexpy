<div align="center">
<img src="https://static.scarf.sh/a.png?x-pxid=cf317fe7-2188-4721-bc01-124bb5d5dbb2" />

## <img src="https://github.com/SantiiRepair/quotexpy/blob/main/.github/images/quotex-logo.png?raw=true" height="56"/>


**📈 QuotexPy is a library for interact with qxbroker easily.**

______________________________________________________________________

[![License](https://img.shields.io/badge/License-GPL--3.0-magenta.svg)](https://www.gnu.org/licenses/gpl-3.0.txt)
[![PyPI version](https://badge.fury.io/py/quotexpy.svg)](https://badge.fury.io/py/quotexpy)
![GithubActions](https://github.com/SantiiRepair/quotexpy/actions/workflows/pylint.yml/badge.svg)

</div>

______________________________________________________________________

## Installing

📈 QuotexPy is tested on Ubuntu 18.04 and Windows 10 with **Python >= 3.10, <= 3.12.**
```bash
pip install quotexpy
```

If you plan to code and make changes, clone and install it locally.

```bash
git clone https://github.com/SantiiRepair/quotexpy.git
pip install -e .
```

### Import
```python
from quotexpy.stable_api import Quotex
```

### Examples
For examples check out [some](https://github.com/SantiiRepair/quotexpy/blob/main/example/main.py) found in the `example` directory.

## Atention
- Because cloudfare blocks requests you should enable browser=True to avoid HTTP 403 errors.

- If the Quotex broker understands that the operation is being carried out by a trading bot, it will apply the rules of use and block the account at the broker. We are not responsible for the use of this lib, use at your own risk. According to the broker’s message:
"... The use of automated bots for trading is prohibited according to account rules.
If you use them, your account will be blocked without the possibility of withdrawing funds and re-registration.
Respectfully,
Quotex"

### Donations
If you feel like showing your love and/or appreciation for this project, then how about shouting me a coffee, beer or something more interesting ;)

<a href="https://www.buymeacoffee.com/SantiiRepair"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a whore&emoji=👯‍♀️&slug=SantiiRepair&button_colour=980028&font_colour=ffffff&font_family=Poppins&outline_colour=ffffff&coffee_colour=FFDD00" /></a>
<br>

### Acknowledgements
Thanks to [@ricardospinoza](https://github.com/ricardospinoza) for solving the `trade` error in the code 🚀
