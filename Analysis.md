- [Setup](#org4c073f0)
  - [Import Packages](#orgb079058)
  - [Load data](#org9be6e9e)
- [Trend Analysis](#org09d51a2)
- [Geographical Analysis](#org5e25c28)
- [Financial Impact Analysis](#org5c14cbb)
- [Industry Analysis](#orgd1e526f)
- [Vulnerability Analysis](#org8f5cf6b)
- [User Impact Analysis](#org9901bae)
- [Response Time Analysis](#orga0e4e42)
- [Defensive Mechanism Effectiveness](#org393575d)



<a id="org4c073f0"></a>

# Setup


<a id="orgb079058"></a>

## Import Packages

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```


<a id="org9be6e9e"></a>

## Load data

```python
df = pd.read_csv('data/Global_Cybersecurity_Threats_2015-2024.csv')
df.head()
```

|   | Country | Year | Attack Type       | Target Industry    | Financial Loss (in Million $) | Number of Affected Users | Attack Source | Security Vulnerability Type | Defense Mechanism Used | Incident Resolution Time (in Hours) |
|--- |------- |---- |----------------- |------------------ |----------------------------- |------------------------ |------------- |--------------------------- |---------------------- |----------------------------------- |
| 0 | China   | 2019 | Phishing          | Education          | 80.53                         | 773169                   | Hacker Group  | Unpatched Software          | VPN                    | 63                                  |
| 1 | China   | 2019 | Ransomware        | Retail             | 62.19                         | 295961                   | Hacker Group  | Unpatched Software          | Firewall               | 71                                  |
| 2 | India   | 2017 | Man-in-the-Middle | IT                 | 38.65                         | 605895                   | Hacker Group  | Weak Passwords              | VPN                    | 20                                  |
| 3 | UK      | 2024 | Ransomware        | Telecommunications | 41.44                         | 659320                   | Nation-state  | Social Engineering          | AI-based Detection     | 7                                   |
| 4 | Germany | 2018 | Man-in-the-Middle | IT                 | 74.41                         | 810682                   | Insider       | Social Engineering          | VPN                    | 68                                  |


<a id="org09d51a2"></a>

# Trend Analysis

-   Analyze trends in the frequency and types of cyberattacks over the years.
-   Identify changes in attack sources and vulnerabilities over time.


<a id="org5e25c28"></a>

# Geographical Analysis

-   Compare the frequency and impact of cyberattacks across different countries.
-   Identify which countries are most affected by specific attack types.


<a id="org5c14cbb"></a>

# Financial Impact Analysis

-   Assess the total financial losses caused by cyberattacks per year or country.
-   Analyze the correlation between attack types and financial losses.


<a id="orgd1e526f"></a>

# Industry Analysis

-   Determine which industries are most frequently targeted by cyberattacks.
-   Assess the impact of attacks on different sectors, such as healthcare, finance, and education.


<a id="org8f5cf6b"></a>

# Vulnerability Analysis

-   Identify common security vulnerabilities exploited in attacks.
-   Analyze the effectiveness of various defense mechanisms used against attacks.


<a id="org9901bae"></a>

# User Impact Analysis

-   Assess how many users are affected by different attack types or in different countries.
-   Explore the relationship between the number of affected users and financial losses.


<a id="orga0e4e42"></a>

# Response Time Analysis

-   Analyze the incident resolution times based on attack types or countries.
-   Identify any patterns in response effectiveness.


<a id="org393575d"></a>

# Defensive Mechanism Effectiveness

-   Evaluate the success rates of different defense mechanisms against various attack types.
