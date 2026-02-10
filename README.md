# Media Renamer

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>

This program is intended to rename media files with proper titles and custom delimiters between words and information about the movie or tv show. This is using the OMDb API. This is a heavy work in progress as it works for the majority of Movies. It struggles with some series, I think this is both an issue from OMDb and my Regular Expression work.

## Getting Started <a name = "getting_started"></a>

### Prerequisites

An OMDb API key will be needed for this program to function properly. The key is not provided. Visit https://www.omdbapi.com/apikey.aspx for a free key.

Create a .env file and add the following code with your key

```
API_KEY=YourKeyHere
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Clone repo and change directories

```
git clone https://github.com/broken-space/mediaRenamer mediaRenamer; cd mediaRenamer
```

Create and activate a virtual environment

```
python3 -m venv env; source env/bin/activate
```

Install requirements

```
pip install requirements.txt
```


## Usage <a name = "usage"></a>

Add notes about how to use the system.
