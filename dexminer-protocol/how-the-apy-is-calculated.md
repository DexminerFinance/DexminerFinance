---
description: Calculating APY
coverY: 0
---

# 💸 How the APY is Calculated

### Compound Interest Equation

$$
A = P(1 + r)^n
$$

Where:

* A = Total Accrued Amount (principal + interest)
* P = Principal Amount
* r = Rate of Interest for each epoch <mark style="background-color:purple;">(2 seconds)</mark>
* n = # of epochs

We have:\
r = 0.0000596%\
2 second = 1 epoch\
1 year = 10512000 epochs

So:

$$
A = P(1 + 0.000000858)^{10512000}= P(1+8259.92)
$$

So it means,

$$
APY =(A/P -1)*100 = 825992.73 %
$$

Same goes to other time periods.

$$
A_{month}=P(1+0.000000858)^{20*60*24*30}=P(1+1.0986)
$$

$$
A_{week}=P(1+0.000000858)^{20*60*24*7}=P(1+0.1888)
$$

$$
A_{day}=P(1+0.000000858)^{20*60*24}=P(1+0.025)
$$

$$
A_{hour}=P(1+0.000000858)^{20*60}=P(1+0.001)
$$

$$
A_{minute}=P(1+0.000000858)^{20}=P(1+0.0000171)
$$

0.0000596% per block (2 seconds)\
0.00110% per minute \
0.15% per hour \
2.6% per day \
19.58% per week \
110.63% per month \
<mark style="background-color:purple;">422,252.66% per year (APY)</mark>

Example:&#x20;

**P =** <mark style="background-color:purple;">$1,000</mark>

**A = (After 1 year) = **<mark style="background-color:purple;"><mark style="color:blue;">****<mark style="color:blue;"></mark> <mark style="background-color:purple;"></mark><mark style="background-color:purple;">$10,950,695.00</mark>
