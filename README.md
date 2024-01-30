### This script is intended to automatically shut down the system if the user unintentionally falls asleep. ###

### Step by step : ###
  1. Import the 'Anti-Keturon Shutdown System.xml' File to the Task Scheduler, That's it!
  (Optional) import the 'Anti-Keturon Shutdown System Warning.xml' , u'll gonna need to re-adjust the file location for this.
  2. Try to Run the script for testing purpose.
  3. If the test suceed, there'll be a logging out notification 
  4. To cancel the Shutdown countdown, use 'shutdown -a' command in the Command Prompt
  5. Happy Living~



### About : ###

As I said above, this script is intended to automatically shut down the system After a configured Time (after 15min idle, a 10min shutdown countdown will be executed by default) if the user(You) unintentionally falls asleep.
This script is made and intended AS IS, and nothing else. This hopes to extend your machine life by shutting it down when you aren't using it, also. Reducing the bills (hopefully)


This was just a simple script made by me, cuz I was unintenionally falls asleep a lot.


### Changing the Trigger Time ### 
Task Scheduler > Double click at my Script 'Anti-Keturon Shutdown System' > Conditions, there you can change the idle trigger by your own

(Also change the Warning Task if you using it)


### Changing the Shutdown Time ###
Task Scheduler > Double click at my Script 'Anti-Keturon Shutdown System' > Actions, edit the action and change the arguments as long as you like.

0 is an option


### Configuring the Warning Script ###
Task Scheduler > Double click at my Script 'Anti-Keturon Shutdown System Warning' > Actions, edit the action and Browse. Find the 'Warning.vbs' File and then OK



