solinea/python
---

Python on a minimal Debian base image.

`solinea/python` is a Docker image based on `solinea/debian`. It includes
Python 2.7 from Debian stable, along with pip and virtualenv from PyPI.

# Usage

Create a Dockerfile with the following content:

    FROM solinea/python