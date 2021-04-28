import xlsxwriter
import openpyxl
import matplotlib.pyplot as plt
import matplotlib as mpl
import numpy as np
import matplotlib as mpl
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go
%matplotlib inline
%config linelineBacked.figure_format = {'png', 'retina'}
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import sklearn
from sklearn.linear_model import LinearRegression
import numpy as np
import sklearn.linear_model
import FinanceDataReader as fdr
from datetime import datetime, timedelta
import xlsxwriter
import openpyxl
import matplotlib.pyplot as plt
import pandas as pd
import plotly.express as px
import plotly.graph_objects as go
#pip install plotly==3.8.1
import cufflinks as cf
import pandas as pd
from matplotlib import rc
rc('font', family='Malgun Gothic')

plt.rcParams['axes.unicode_minus'] = False
%matplotlib inline

from matplotlib import rc
rc('font', family='Malgun Gothic')

plt.rcParams['axes.unicode_minus'] = False

df_final = pd.read_excel("./datas/final_X.xls",'final_X')
df_final = df_final.drop(["Unnamed: 0"], axis=1)
df_final.head()
