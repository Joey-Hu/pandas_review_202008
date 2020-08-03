## Pandas note 1

### resample +++

重采样

### pd.idxmax(axis=0, skipna=True)

当axis==0时，返回第一次最大值出现的index;
当axis==1时，返回第一次最大值出现的column;

### DataFrame.loc()

### np.random.randint()

产生随机数数组 

### 数据表连接

pd.concat(\[ df1, df2, ...\], , axis)

当axis==0时，按行连接
当axis==1时，按列连接

df1.append(df2)

### pd.merge()

### DataFrame.isnull()

检测df中的空值，空值赋True；非空值赋False

### DataFrame.notna()

非缺省值判断

### 数据可视化

### pandas.Index.is_unique

Return if the index has unique values.

### df.drop()

### df.loc() & df.iloc()



