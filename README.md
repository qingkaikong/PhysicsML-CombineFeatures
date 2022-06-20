# PhysicsML-CombineFeatures
This repo contains the code used for the paper - Combining Deep Learning with Physics Based Features in Explosion-Earthquake Discrimination

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6672629.svg)](https://doi.org/10.5281/zenodo.6672629)


***
## [Content](#Content)

* 01_models_and_training.ipynb - notebook contains the models built in the paper and the training of the two branch model.
* 02_visualize_model.ipynb - notebook contains the GradCAM code for visualize the trained deep learning branch.
* demo_data.npz - numpy zipped arrays, contains 200 sample data from earthquake and explosion waveforms as well as the computed P/S ratios. Keys: X_waveform, X_param, y
* requirements.txt - Python packages used to run the code.

***
## [License](#license)

This code is provided under the [MIT License](LICENSE.txt).

```text
 Copyright (c) 2022 Qingkai Kong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

***
## [Disclaimer](#disclaimer)
```text
  This work was performed under the auspices of the U.S. Department of Energy
  by Lawrence Livermore National Laboratory under Contract DE-AC52-07NA27344.
```

``LLNL-CODE-836483``
