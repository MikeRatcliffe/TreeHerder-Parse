TreeHerder-Parse
================

Demo:
http://htmlpreview.github.io/?https://github.com/MikeRatcliffe/TreeHerder-Parse/master/TreeherderParse.html

A simple HTML page that uses the TreeHerder API to parse all logs for a given revision e.g. 07b73f261b95 and display all consistently failing tests and crashers. This saves lots of time and sanity I generally use for grepping logs.

It is recommended that you perform the following procedure:

1. Push your patch to try.
2. Retrigger the tests you are interested in a number of times.
3. When the test is complete enter your revision number in TreeHerderParse.html

Your logs will be parsed and all consistent failures and any crashers will be displayed.

It is easy to log extra information by adding a new regex to parseLog() and displaying your results via displayResults().

I have made exactly zero effort to make this code pretty as it is purely a sanity saver.
