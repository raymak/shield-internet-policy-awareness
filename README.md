# Internet Policy Awareness Study
This repository hosts a [Shield study](https://wiki.mozilla.org/Firefox/Shield/Shield_Studies) that is designed to understand what the best way to raise awareness around policies that govern the way the Internet works.

## Task
When the user visits ceratin websites that are in support of healthy internet policies, they receive a message calling for action to support such policies. The user can take action by clicking a button and filling out a form that eventually will be submitted to FCC as comments on the recently proposed policy changes.

## Data Collection
The `internet-policy-awareness` extension collects a participant's Firefox usage data that is related to her interaction with the messages, as well as metrics that could be correlated with her receptivity to those messages. In particular, it collects:

- when the participant visits one of the designated websites that are in favor of certain policies
- the hostname (e.g. facebook.com, maps.google.com) of the certain designated website that the participant visits
- the participant's interaction with the notification
- Firefox usage metrics that are likely to be correlated with the participant's receptivity to the notifications, including:
	-- profile age
	-- number of open tabs
	-- number of open windows
	-- number of active extensions and themes
	-- if Firefox is the default browser
	-- whether or not the Do Not Track feature is on


NOTE: no data is collected in private browsing mode

The collected data is transferred through Shield [Telemetry](https://wiki.mozilla.org/T\elemetry) pings to Mozilla along with the usual [environment ping](http://gecko.readthedocs.io/en/latest/toolkit/components/telemetry/telemetry/data/environment.html) data from Telemetry. 
