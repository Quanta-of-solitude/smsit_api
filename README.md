# SMS-iT API Wrapper
> SMS-iT API Python wrapper 0.0.2

GitHub at: https://github.com/Quanta-of-solitude/smsit_api/blob/main/README.md
<br/>

## Table of Content 

- [Installation](#installation)
- [Requirements](#requirements)
- [Available Methods](#available-methods)
- [Example](#example)
- [Contribute](#contribute)

<br/>

### Installation
---
Available on [pypi](https://pypi.org/project/smsit-api/)

```
pip install smsit_api
```

<br/>

### Requirements
---
> Used runtime: Python 3.8

```
requests
```

<br/>

### Available methods
---

```
 'addAppointment', 'addContact', 'checkCredits', 'generateOTP', 'getContact', 'getContactByName', 'getGroupsList', 'name', 'sendMessageToContacts', 'sendMessageToGroup', 'token', 'validateOTP'

```

There is no documentation as of now for this package, you can use help() to get information

```python
from smsit_api import smsitpy

h = smsitpy(token="MyToken", version="cloud") #version options : cloud or decentral
```

The official API Reference can be found [here](https://decontrolpanel.smsit.ai/users/api)

<br/>

### Example
---

To get generate OTP:
```python
from smsit_api import smsitpy

h = smsitpy(token="MyToken", version="cloud") #version options : cloud or decentral

print(h.generate(OTP)

OUTPUT:
{'status': 'Success', 'msg': 'Otp Successfully Generated', 'otp': '94b87b'}

```

<br/>

### Contribute
---

Feel Free to contribute and expand the wrapper

<br/>

>To be updated
<br/>
Have Fun!
