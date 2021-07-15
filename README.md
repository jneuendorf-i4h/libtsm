# libtsm

A Python toolbox for Time-Scale Modification (TSM) and Pitch-Shifting.

This toolbox is based on a re-implementation of the Matlab TSM toolbox by Jonathan Driedger and Meinard Müller:

https://www.audiolabs-erlangen.de/resources/MIR/TSMtoolbox/


## Installation

With Python >= 3.6, you can install libtsm using the Python package manager pip:

```
pip install libtsm
```

## Citing

If you use `libtsm`, please cite:

```
Sebastian Rosenzweig, Simon Schwär, Jonathan Driedger, and Meinard Müller:
Adaptive Pitch-Shifting with Applications to Intonation Adjustment in A Cappella Recordings
Proceedings of the International Conference on Digital Audio Effects (DAFx), 2021.
```

## Contributing

We are happy for suggestions and contributions. However, to facilitate the synchronization, we would be grateful for either directly contacting us via email (meinard.mueller@audiolabs-erlangen.de) or for creating [an issue](https://github.com/meinardmueller/libtsm/issues) in our GitHub repository. Please do not submit a pull request without prior consultation with us.

If you want to report an issue with libtsm or seek support, please use the same communication channels (email or GitHub issue).

## Tests

Central to our tests is the comparison of `libtsm` with the MATLAB TSM Toolbox.
To this end, please execute `tests/test_matlab.m` in MATLAB to create the MATLAB output.
Then, you can use [pytest](https://pytest.org) for executing our Python test scripts. `pytest` is available when installing libtsm with the extra requirements for testing.

```
pip install 'libtsm[tests]'
pytest
```

## Acknowledgements

This project is supported by the German Research Foundation (DFG MU 2686/12-1, MU 2686/13-1).
The International Audio Laboratories Erlangen are a joint institution of the Friedrich-Alexander Universität Erlangen-Nürnberg (FAU) and Fraunhofer Institute for Integrated Circuits IIS. We thank Edgar Suarez, El Mehdi Lemnaouar and Miguel Gonzales for implementation support.
