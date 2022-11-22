# PyRTT Viewer

[![Lint status](https://github.com/thomasstenersen/pyrtt-viewer/workflows/Lint/badge.svg)](https://github.com/thomasstenersen/pyrtt-viewer)

This is a simple Python 3 script for simple RTT interaction with an nRF5x device.

If you just want to use it directly, you can install using `pip`:

    pip install pyrtt-viewer

Then you can run the script as a normal executable:

    pyrtt-viewer -h

## Usage

	pyrtt-viewer [-h] [-i ID] [-c CHANNEL] -d DEVICE_FAMILY -s SPEED



If you think you'd like to modify the script a bit, install it as a local package:

    pip install -e .

## Requirements

- Python 3.x
- `pynrfjprog` -- `pip install pynrfjprog`
