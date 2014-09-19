pbNotifier
==========

A MATLAB class to push notifications to mobile devices using the pushbullet API.

Getting Started
---------------
This script uses the pushbullet API. You will need to signup for a pushbullet account - https://www.pushbullet.com/. Once you have the account setup, you will need the access token specific to your account - https://www.pushbullet.com/account

Create an object of the pbNotifer class

```pbO = pbNotifier(accessToken)```

Once you have created the object, you may call the notify method.

```return = pbO.notify(message)```

This sends the message to all devices registered on your account.

Example
-------
```
pbO = pbNotifier('zGtDxXr1EP3euf1R2q5i8GxUb3SpoOjg');
...
...
pbO.notifier('Execution Complete')
```

