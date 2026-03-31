# Tutorials

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Phmonski/Tutorials/main?urlpath=lab/tree/RooJSONFactoryWSToolTutorial/tutorial.ipynb)

Several tutorials on the usage of HS3 (Harmonized Statistics Serialization Standard).

## Binder demo

Launch the RooJSONFactoryWSTool tutorial directly in JupyterLab with the badge above, or use this link:

https://mybinder.org/v2/gh/Phmonski/Tutorials/main?urlpath=lab/tree/RooJSONFactoryWSToolTutorial/tutorial.ipynb

The notebook is configured for the standard `Python 3` kernel and uses PyROOT, so Binder does not need a custom ROOT notebook kernel.

The demo walks through:

- building a small RooFit workspace
- exporting it to HS3 JSON as `tutorial.json`
- writing the workspace to `tutorial.root`
- importing the JSON back into a fresh workspace and refitting it

The Binder environment installs:

- Python 3.11
- CERN ROOT with PyROOT support
- JupyterLab
