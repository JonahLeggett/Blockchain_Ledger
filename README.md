# Blockchain Based Ledger Application

## Overview of the project and project goals

I assumed the role of a fintech engineer for a bank, who’s working as the lead developer on the decentralized finance team. The goal was to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger. 


### Libraries 

```
# Import the required libraries and dependencies

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib

```
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* Streamlit- is an open-source app framework for Machine Learning and Data Science teams.
* Dataclasses-a utility tool to make structured classes specially for storing data. These classes hold certain properties and functions to deal specifically with the data and its representation.
* Typing-provides runtime support for type hints. The most fundamental support consists of the types Any, Union, Tuple, Callable, TypeVar, and Generic.
* Datetime-supplies classes for manipulating dates and times.
* Hashlib-Python hashlib hashing function takes variable length of bytes and converts it into a fixed length sequence. This is a one way function. 


### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
git clone https://github.com/JonahLeggett/Blockchain_Ledger.git
```


* Open [ pychain.py ] in VS Code.


### Run streamlit

1. Navigate to Blochain_Ledger folder in terminal.

2. Run the following command in terminal:

```
streamlit run pychain.py

```


## License

[MIT]



📔 Contact me: 
📩 jonah.leggett@gmail.com