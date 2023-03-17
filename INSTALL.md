# ILF Installation


# Manual Installation

If the installation guide in the original `README.md` does not work, then the
following installation steps may need.

- Install Python dependencies:

  ``` sh
  cd /path/to/ilf

  # Install Python packages
  pip3 install cython
  pip3 install -r requirements-aiohttp.txt --no-cache-dir
  pip3 install aiohttp
  pip3 install -r requirements.txt --no-cache-dir
  pip3 install torch==1.10.2+cpu torchvision==0.11.3+cpu torchaudio==0.10.2+cpu -f https://download.pytorch.org/whl/cpu/torch_stable.html
  ```
