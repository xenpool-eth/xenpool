## Overview

Introduction:  

Inspired by Jack Levin

This proof of work pool-miner is based on Argon2ID algorithm which is both GPU and ASIC resistant.
The difficulty is reduced. XEN11 -> XEN1 XUNI[0-9] -> XUNI.
Each valid hash gives you a share.
In the future, the reward will be distributed depending on the number of shares.

## Installation

Install all the required modules by executing the command below.  Make sure you have at least python3 and pip3 installed in order to proceed.

```bash
pip install -U -r requirements.txt
```
## 

To start your miner just execute this command.  Note you should adjust account at the top of the file to be your ethereum address if you want to claim your blocks and superblocks later

```bash
python3 pool-miner.py
```
