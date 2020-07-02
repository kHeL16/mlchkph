# ml-chk-ph
Moonton Checker by JemPH Proxy Support.

Guide:
Type The Commands in Termux:
  pkg update && pkg upgrade
  pkg install python git
  pip install --upgrade pip

  cd ml-chk-ph
  pip install -r requirements.txt

  python run.py

How the Checker Works?
You Need Combolist to check accounts.
1. Locate your list of combo/accounts make sure the directory is correct.
2. You will Choose which type of method you want:
  [1.] Manual Proxy (Make sure you make a text file for proxies (ex. proxies.txt)
  [2.] Proxyless (No need to locate your proxies it will directly use without proxy import) (No Ban IP)
3. Number of Threads. The higher the thread the faster it checks. The lower the thread the slower in checks.
  - The Higher Thread: Consume more RAM, CPU Usage risky.
  - The Lower Thread: Less Consume of RAM & CPU Usage + safe.
4. You can recheck the errors if have. These accounts are not check because its banned in logging in but it doesn't ban your IP.
5. Enjoy!
