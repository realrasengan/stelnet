# stelnet
### Make a SSL secured telnet connection to a host/port

## Background
I like to use telnet to login to IRC servers and check various outputs, but it's insecure.

## Enter stelnet
This is just a simple nodeJS stdin script that uses the tls default module with nodejs and makes a connection to a remote host and port.  It's very basic, but get's the job done.

## Installation
Make sure you have nodejs/npm installed on your system, and then, copy stelnet to a bin folder of somekind in your path.

## Usage
```
stelnet example.com 6697
```

Add an additional parameter to connect to an insecure host

```
stelnet insecure.com 6697 insecure
```


## Copyright

MIT


