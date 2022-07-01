# Python-V-rep-remoteAPI
To connect Python and V-rep

## Environment:
- Ubuntu: 20.04
- Coppeliasim: CoppeliaSim_Edu_V4_3_0_Ubuntu20_04
- Python: 3.8.10

## First, copy remoteAPI files and past them in your folder
- "sim.py" and "simConst.py", in /Coppeliasim/programming/remoteApibindings/python/python
- "remoteApi.so" , in /Coppeliasim/programming/remoteApibindings/lib/lib/Ubuntu20_04

## Second, Code in Python
<img src="https://raw.githubusercontent.com/ge95net/Python-V-rep-remoteAPI/master/pictures/Python%20code.png"  />
The second term is connection port, the default connection port of Coppeliasim if 19997, if you want to change the connection port in python, you should do the same change in Coppeliasim

## Third, Configuration in Coppeliasim
If you want to change the connection port, then you should do the same change at the main script of your scene
<img src="https://raw.githubusercontent.com/ge95net/Python-V-rep-remoteAPI/master/pictures/V-rep.png"  />
