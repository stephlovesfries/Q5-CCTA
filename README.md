# Q5-CCTA
## Module
The assigned specifications for the CCTA module are as folllows:
  - Inputs A, B and C are 4-bit vector inputs.
  - Output q is 5-bit wide.
  - rst is active high, when activated q is set to 0;
  - When ctrl input is ‘0’, output q is the sum of A and B.
  - When ctrl input is ‘1’, output q is the difference of A and C.

I utilized two if-else functions to ensure that the rst and ctrl functions control the output accordingly.   
![photo1710203851](https://github.com/stephlovesfries/Q5-CCTA/assets/115708694/02d71078-8c40-4be2-8e33-30e4b7c89919)

## Testbench & Simulation 
Values were assigned to A, B, C, rst, and ctrl, to check the function of the CCTA module.  

![photo1710203851 (1)](https://github.com/stephlovesfries/Q5-CCTA/assets/115708694/06d74bd8-df8b-4bab-bbcd-311aaa434849)
![photo1710204227](https://github.com/stephlovesfries/Q5-CCTA/assets/115708694/84cc9cb3-0f48-4d45-b897-53255fbc4bcb)
