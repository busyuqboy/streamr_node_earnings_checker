# streamr_node_earnings_checker
Simple Python script that shows basic statistics of your node earnings.

<b>Only things to change:</b>
- Add your node addresses in the variable list ```addresses```.
- Add your mining start date in the ```datetime``` (year, month, day, hour, minute). 
- Add in which interval you would like to loop the script by chaning the variable ```script_frequency``` (default = 3600, once per hour).

<b>Requires the following imports to be installed:</b>
- requests
- json
- apscheduler
- datetime (installed by default on most systems).


<b>Sample output:</b> <br><br>
![image](https://user-images.githubusercontent.com/38588045/156255338-29e2fd5a-8d32-462d-bb7b-56ff736d2ac4.png)

<b>How to run:</b>
```
git clone https://github.com/zertyn/streamr_node_earnings_checker.git
cd streamr_node_earnings_checker/
python3 data_earnings_checker.py
```
