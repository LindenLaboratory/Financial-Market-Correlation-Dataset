# What is Market Melody?
This repository contains the Market Melody dataset which tracks CO2 levels and the prices of a range of environmental assets such as Carbon Credits, ESG indexes, Nat. Gas & Oil in order to attempt to find a correlation. In addition, it contains the programs that were used to make it in the [Programs Folder](Programs) and instructions for how to use them in [EXECUTE.md](EXECUTE.md). The program should be run for at least **1-3 months** in order to attempt to form some kind of pattern. Once this has been done, the resulting **dataset.csv** file can be analysed for patterns.

The [**dataset.csv** file already calculated](data.csv) has been trained for **6 months**. See [DATASET.md](DATASET.md) for more detail on the dataset and the patterns found.

---

## How does the program work?
The Market Melody Dataset is calculated using custom software in conjunction with the [Borealis network](https://github.com/LindenLaboratory/Borealis/tree/main). Several computers are put under the control of an instance of the network and a program is sent using the **code:.** prefix. This program will iterate through a list of commands where it will get price data from all 4 assets we are investigating and send the data back to the _Conductor_. The more computers, the more Data Per Unit Time (DPUT), with the network working with as low as one computer running but with a very low DPUT and a maximum of 5 computers connected per Borealis instance (multiple networks can be connected together and run in conjunction - see [EXECUTE.md](EXECUTE.md) for more detail - for even higher DPUT) for very high DPUT. We would recommend a minimum of 4 computers connected together, one for each asset we are tracking, for an optimum price to DPUT ratio.
