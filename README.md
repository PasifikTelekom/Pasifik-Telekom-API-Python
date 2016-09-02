# Pasifik Panel API Python

This library package provides a variety systems, the simplest way to integrate Pasifik services with your system.

## Requirements
`Python>=2.7` version.

Download and install [https://python.org/downloads/](https://python.org/downloads/).

## Installation
Download source code.

Unzip package and enter to `lib/` directory.

Copy `pasifik.py` file to your directory.

## Usage
```python
#-*- coding: utf-8 -*-
from pasifik import PasifikAPI
username = "YOUR_USERNAME"
password = "YOUR_PASSWORD"
header = "YOUR_COMPANY"
lang = "tr" # 'tr': Turkish response, 'en': English response, 'ar': Arabic response.
DEBUG = True
obj = PasifikAPI(username, password, lang, DEBUG)
```
## Test Case

Follow `test.py` TestCase class and replace it with requirement parameters, for test just uncomment the following methods in `main.py`.

```python
#-*- coding: utf-8 -*-
from lib.test import TestCase
if __name__ == '__main__':
    test = TestCase()
    #test.send_one_message_to_many_receipients()
    #test.send_one_message_to_many_receipients_schedule_delivery()
    #test.send_one_message_to_many_receipients_schedule_delivery_with_validity_period()
    #test.send_one_message_to_many_receipients_turkish_language()
    #test.send_one_message_to_many_receipients_flash_sms()
    #test.send_one_message_to_many_receipients_unicode()
    #test.send_one_message_to_many_receipients_outside_turkey()
    #test.send_many_message_to_many_receipients()
    #test.query_multi_general_report()
    #test.query_multi_general_report_with_id()
    #test.query_detailed_report_with_id()
    #test.get_account_settings()
    #test.get_authority()
    #test.get_cdr_report()
    #test.get_cdr_report_range_datetime()
    #test.get_cdr_report_with_type()
    #test.get_active_calls()
    #test.get_disconnect_active_call()
```

Go to downloaded file directory and run python code on local server

    cd /path/to/code/Pasifik-Panel-API-Python-master/
    python main.py
    
Then you will see the result on Terminal.
