# x-ray-transmission
Author: Niels Vanderloo with inspiration from a MATLAB script by Jacob Pearcy

This notebook is used to plot and fit transmission data taken from the [Proto XRD system](https://leia.psfc.mit.edu/wiki/index.php/PROTO-XRD
).
It requires two uncommon python packages
- `pip install mcareader`
- `pip install xraydb`

To create MCA files from spectrometer readings you will need the appropriate [driver](https://www.amptek.com/software/dp5-digital-pulse-processor-software/dpp-installation-instructions) installed on your laptop as well as the [DPPMCA software](https://www.amptek.com/software/dp5-digital-pulse-processor-software/dppmca-display-acquisition-software).

# `x-ray-transmission-V2.ipynb`

Author: Niels Vanderloo with inspiration from a MATLAB script by Jacob Pearcy

This notebook is used to plot and fit transmission data taken from the [Proto XRD system](https://leia.psfc.mit.edu/wiki/index.php/PROTO-XRD).

## Prerequisites
- MATLAB
  - [PhotonAttenuation](https://www.mathworks.com/matlabcentral/fileexchange/12092-photonattenuation) MATLAB module
- Uncommon Python packages:
  - `pip install mcareader`
  - `python -m pip install matlabengine`
  - `pip install xraydb` (optional, only used in last cell)
