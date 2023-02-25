# pycounts_ma

Calculate word counts in a text file!

_Note: This is a toy package developed as part of DSCI 524 coursework. It follows the instructions described in the [Python packages textbook](https://py-pkgs.org/03-how-to-package-a-python)._

## Installation

```bash
$ pip install pycounts_ma
```

## Usage

`pycounts` can be used to count words in a text file and plot results
as follows:

```python
from pycounts.pycounts import count_words
from pycounts.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_ma` was created by Marian Agyby. It is licensed under the terms of the MIT license.

## Credits

`pycounts_ma` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
