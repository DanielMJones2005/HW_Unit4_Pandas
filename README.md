# HW_Unit4_Pandas
Homework Unit 3 | Assignment -  Pandas, Pandas, Pandas

# Option 1: Heroes of Pymoli
Source File: purchase_data

# Player Count
Total Number of Players
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Total Players</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>576</td>
    </tr>
  </tbody>
</table>

# Purchasing Analysis (Total)
Number of Unique Items
Average Purchase Price
Total Number of Purchases
Total Revenue

# Gender Demographics
Percentage and Count of Male Players
Percentage and Count of Female Players 
Percentage and Count of Other / Non-Disclosed

# Purchasing Analysis (Gender)
The below each broken by gender:
- Purchase Count
- Average Purchase Price
- Total Purchase Value
- Average Purchase Total per Person by Gender

# Age Demographics
The below each broken into bins of 4 years (i.e. <10, 10-14, 15-19, etc.)
- Purchase Count
- Average Purchase Price
- Total Purchase Value
- Average Purchase Total per Person by Age Group

# Purchasing Analysis (Age)
The below each broken into bins of 4 years (i.e. <10, 10-14, 15-19, etc.)
- Purchase Count
- Average Purchase Price
- Total Purchase Value
- Average Purchase Total per Person etc. in the table below
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Purchase Count</th>
      <th>Average Purchase Price</th>
      <th>Total Purchase Value</th>
      <th>Avg Total Purchase per Person</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>10-14</th>
      <td>28</td>
      <td>$2.96</td>
      <td>$82.78</td>
      <td>$3.76</td>
    </tr>
    <tr>
      <th>15-19</th>
      <td>136</td>
      <td>$3.04</td>
      <td>$412.89</td>
      <td>$3.86</td>
    </tr>
    <tr>
      <th>20-24</th>
      <td>365</td>
      <td>$3.05</td>
      <td>$1,114.06</td>
      <td>$4.32</td>
    </tr>
    <tr>
      <th>25-29</th>
      <td>101</td>
      <td>$2.90</td>
      <td>$293.00</td>
      <td>$3.81</td>
    </tr>
    <tr>
      <th>30-34</th>
      <td>73</td>
      <td>$2.93</td>
      <td>$214.00</td>
      <td>$4.12</td>
    </tr>
    <tr>
      <th>35-39</th>
      <td>41</td>
      <td>$3.60</td>
      <td>$147.67</td>
      <td>$4.76</td>
    </tr>
    <tr>
      <th>40+</th>
      <td>13</td>
      <td>$2.94</td>
      <td>$38.24</td>
      <td>$3.19</td>
    </tr>
    <tr>
      <th>&lt;10</th>
      <td>23</td>
      <td>$3.35</td>
      <td>$77.13</td>
      <td>$4.54</td>
    </tr>
  </tbody>
</table>

# Top Spenders
Identify the the top 5 spenders in the game by total purchase value, then list (in a table): 
- SN
- Purchase Count
- Average Purchase Price
- Total Purchase Value
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Purchase Count</th>
      <th>Average Purchase Price</th>
      <th>Total Purchase Value</th>
    </tr>
    <tr>
      <th>SN</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Lisosia93</th>
      <td>5</td>
      <td>$3.79</td>
      <td>$18.96</td>
    </tr>
    <tr>
      <th>Idastidru52</th>
      <td>4</td>
      <td>$3.86</td>
      <td>$15.45</td>
    </tr>
    <tr>
      <th>Chamjask73</th>
      <td>3</td>
      <td>$4.61</td>
      <td>$13.83</td>
    </tr>
    <tr>
      <th>Iral74</th>
      <td>4</td>
      <td>$3.40</td>
      <td>$13.62</td>
    </tr>
    <tr>
      <th>Iskadarya95</th>
      <td>3</td>
      <td>$4.37</td>
      <td>$13.10</td>
    </tr>
  </tbody>
</table>

# Most Popular Items
Identify the 5 most popular items by purchase count, then list (in a table): 
- Item ID
- Item Name
- Purchase Count
- Item Price
- Total Purchase Value
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>Purchase Count</th>
      <th>Item Price</th>
      <th>Total Purchase Value</th>
    </tr>
    <tr>
      <th>Item ID</th>
      <th>Item Name</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>178</th>
      <th>Oathbreaker, Last Hope of the Breaking Storm</th>
      <td>12</td>
      <td>$4.23</td>
      <td>$50.76</td>
    </tr>
    <tr>
      <th>145</th>
      <th>Fiery Glass Crusader</th>
      <td>9</td>
      <td>$4.58</td>
      <td>$41.22</td>
    </tr>
    <tr>
      <th>108</th>
      <th>Extraction, Quickblade Of Trembling Hands</th>
      <td>9</td>
      <td>$3.53</td>
      <td>$31.77</td>
    </tr>
    <tr>
      <th>82</th>
      <th>Nirvana</th>
      <td>9</td>
      <td>$4.90</td>
      <td>$44.10</td>
    </tr>
    <tr>
      <th>19</th>
      <th>Pursuit, Cudgel of Necromancy</th>
      <td>8</td>
      <td>$1.02</td>
      <td>$8.16</td>
    </tr>
  </tbody>
</table>

# Most Profitable Items
Identify the 5 most profitable items by total purchase value, then list (in a table):
- Item ID
- Item Name
- Purchase Count
- Item Price
- Total Purchase Value
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>Purchase Count</th>
      <th>Item Price</th>
      <th>Total Purchase Value</th>
    </tr>
    <tr>
      <th>Item ID</th>
      <th>Item Name</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>178</th>
      <th>Oathbreaker, Last Hope of the Breaking Storm</th>
      <td>12</td>
      <td>$4.23</td>
      <td>$50.76</td>
    </tr>
    <tr>
      <th>82</th>
      <th>Nirvana</th>
      <td>9</td>
      <td>$4.90</td>
      <td>$44.10</td>
    </tr>
    <tr>
      <th>145</th>
      <th>Fiery Glass Crusader</th>
      <td>9</td>
      <td>$4.58</td>
      <td>$41.22</td>
    </tr>
    <tr>
      <th>92</th>
      <th>Final Critic</th>
      <td>8</td>
      <td>$4.88</td>
      <td>$39.04</td>
    </tr>
    <tr>
      <th>103</th>
      <th>Singed Scalpel</th>
      <td>8</td>
      <td>$4.35</td>
      <td>$34.80</td>
    </tr>
  </tbody>
</table>

# You must include a written description of three observable trends based on the data.
- 1. Males make up the majority of players at 84.03%, out of 576 total unique players
    - a.	Females make up the second largest group of unique players at 14.06%, and Other/Non-Disclosed are 1.91% of total unique players
    - b.	Males are the core market demographic
- 2. While Males make up the majority of unique players, the average total purchase per person is actually greatest for Other/Non-Disclosed at $4.56 compared to Males, who spent an average $4.56 total purchase per person, followed by Females who spent an average $4.47 total purchase per person
    - a.	This would suggest increased marketing to Other/Non-Disclosed and Females could increase revenue
- 3. While the largest age demographic of unique players was the 20-24 age group at 44.79% of the total 576 unique players,
    - a.	The largest average total purchase per person came from the 35-39 age group, which had an average total purchase per person of $4.76
    - b.	The 20-24 age group actually ranked 3rd for average total purchase per person with $4.32 average total purchase per person
          - i.	The <10 age group was second with an average total purchase per person of $4.50
              - 1.	Although based on reason/logic, the <10 age group most likely does not have a revenue stream, and much less disposable income,
              - 2.	These purchases are most likely coming from individuals/parents with disposable income
