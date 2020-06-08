#!/usr/bin/env python
# coding: utf-8

# ## 군집데이터

# ### boolean

# In[1]:


True == False


# In[2]:


True != 0


# In[3]:


False == 0


# In[4]:


True or False


# In[61]:


1 == '1'


# In[125]:


True == 1


# ### 문자열

# In[55]:


eng = 'Korea COVID 19'
eng


# In[54]:


eng.lower()


# In[63]:


eng.upper()


# In[128]:


a='Hello'
a


# In[65]:


a.lower()


# In[129]:


a.upper()


# ### List [ ]

# In[74]:


data = []
data


# In[75]:


data.append('java')
data.append('c')
data


# In[76]:


data[0]


# In[77]:


data[-1]


# In[78]:


data[1:]


# In[79]:


data[:2]


# In[80]:


data.sort()
data


# In[83]:


data.reverse()
data


# In[85]:


d=[]
d.append('Hello')
d.append('World')
d.reverse()
d


# ### Tuple()

# In[57]:


b=(1,2,3, '사','오')
b


# In[58]:


c=1,2,3
c


# In[21]:


type(b), type(c)


# In[22]:


b[3]=4


# In[23]:


b[3:], b[1:4]


# In[117]:


b[:2], b[0:3]


# ### Dictionay{}

# In[59]:


dic = {'name1' :'경민', '학번1':20103, 'name2' : '경민2', '학번2':20104}
dic


# In[60]:


dic.get('name1')


# In[26]:


dic.keys()


# In[27]:


dic.values()


# ### set{}

# In[130]:


lunch = {'햄버거', '치킨', '라면', '콜라', 10000}
dinner = {'피자', '족발', '라면', '콜라', 10000}


# In[29]:


lunch & dinner


# In[30]:


lunch | dinner


# ### Pandas

# In[131]:


import pandas as pd


# In[87]:


li = [1,2,3]
li


# In[88]:


type(li)


# In[89]:


s1=pd.core.series.Series(li)
s1


# In[90]:


s2=pd.core.series.Series(['일','이','삼'])
s2


# In[93]:


data=dict(num=s1, word=s2)
data


# In[95]:


pd.DataFrame(data)


# In[103]:


data=pd.DataFrame([['a', 100],['b', 200], ['c', 300]])
data.info


# In[106]:


data.head(2)


# In[108]:


data.tail(2)


# In[109]:


col=['1군','2군']


# In[113]:


pd.DataFrame([['a', 100],['b', 200], ['c', 300]],columns=col)


# In[118]:


man = [{'Name':'은주', 'age':20, 'job':'j1'},
       {'Name':'민서', 'age':30, 'job':'j2'},
       {'Name':'경민', 'age':15, 'job':'j3'}]
pd.DataFrame(man,index=[1,2,3])


# In[124]:


a=[1,2,3]
b=[4,5,6]
df=[a,b]
dd=pd.DataFrame(df, index=[1,2],columns=['A','B','C'])
dd

