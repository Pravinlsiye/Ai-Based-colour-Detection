# Build a Site Connectivity Checker in Python

RP Checker is a site connectivity checker utility. It takes one or more website URLs and checks if those sites are online. It can perform the connectivity checks either synchronously or asynchronously.

## Installation

1. Create a Python virtual environment

```sh
 python -m venv ./venv
 source venv/bin/activate
```

2. Install the requirements

``` python -m pip install -r requirements.txt
```

## Run the Project

```sh
 python -m rpchecker -u python.org
```

## Output
```sh
The status of "https://pravinlsimpleportfolio.netlify.app/" is: "Online!" 👍
```

## Features

RP Checker provides the following options:

- `-u` or `--urls` takes one or more URLs and checks if they're online.
- `-f` or `--input-file` takes a file containing a list of URLs to check.
- `-a` or `--asynchronous` runs the check asynchronously.


