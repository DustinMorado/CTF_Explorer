# CTF_EXPLORER

A smallish application for exploring CTF aliasing effects due to data collection
parameters as discussed
[here](https://forum.scilifelab.se/t/thinking-about-ctf/114).

## Requirements

It should be consistent across older versions of Python, but this was what I
tested it using:

 * Python (_Version >= 3.7.6_)
 * numpy (_Version >= 1.18.1_)
 * IPython (_Version >= 7.12.0_)
 * ipywidgets (_Version >= 7.5.1_)
 * plotly (_Version >= 4.8.1_)
 * appmode (_Version >= 0.8.0_)

## Usage

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DustinMorado/CTF_Explorer/master?urlpath=%2Fapps%2FCTF_Explorer.ipynb)

Just click the badge above to run a Binder instance of the application or you
can install and run it locally on your system:

1. `git clone https://github.com/DustinMorado/CTF_Explorer.git`
2. `cd CTF_Explorer`
3. `conda env create -f environment.yml`
4. `conda activate ctf-explorer`
5. `jupyter notebook --no-browser`
6. Browse to `http://localhost:8888/apps/CTF_Explorer.py`

## Licensing

Distributed under the MIT License please see LICENSE.txt for more information.
