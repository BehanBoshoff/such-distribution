#probability_distributions package

This is a package which does many wonderful things that normal people have no interest in whatsoever, such as adding Gaussian and Binomial Distributions together.
If you count yourself amongst them, then all you need to know is:

'Python code big good.'

Alternatively, here's a description of the code:

Distribution()

- Attributes:

- mean
- standard deviation
- list of data

- Methods:

- read_data_file(file_name): given a file of numbers, reads in data to create list of numbers

Binomial(Distribution)

- Attributes:

- Distribution attributions
- probability
- size

- Methods:

- calculate_mean(): assigns and returns the mean
- calculate_stdev(): assigns and returns the mean
- replace_stats_with_data(): assign prob, size, mean, stdev
- plot_bar(): plot bar graph of data
- pdf(k): Calculate the probability density
- plot_bar_pdf(): Plot bar graph of the pdf
- add(other): override +
- repr(): override print()

Gaussian(Distribution)

- Attributes:

- Distribution attributes

- Methods:

- calculate_mean(): assigns and returns the mean
- calculate_stdev(): assigns and returns the mean
- replace_stats_with_data(): assign prob, size, mean, stdev
- plot_bar(): plot bar graph of data
- pdf(k): Calculate the probability density
- plot_bar_pdf(): Plot bar graph of the pdf
- add(other): override +
- repr(): override print()


You can install this package from PyPI using the command 'pip install suchdistribution'.
Enjoy!
