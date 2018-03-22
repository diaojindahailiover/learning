import numpy as np
import pandas as pd


df = pd.DataFrame({"a":[range(10)], "b":list(range(10,20))})
# 实现df的转置
df.T
