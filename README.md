# Boulder's First Snow

Code to analyze the historical date of the "first snow" in Boulder each year.

Data is from the NOAA Earth System Research Lab and was acquired here: https://psl.noaa.gov/boulder/getdata.html.
Note that snow totals do not start until August 1948. Trace values (less than 1/10" for snow) are indicated
by -999.0.

## Installation

1. Install `pixi` if you don't have it already. See [their documentation](https://pixi.sh/latest/) or run:
```shell
curl -fsSL https://pixi.sh/install.sh | sh
```

2. Install the environment:
```shell
pixi install
```

3. Open the notebook:
```shell
pixi run jupyter lab
```
