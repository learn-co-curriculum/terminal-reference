Use this as a reference when you run into unexpected errors in your terminal.


## Error: Unable to run shotgun & bundle excec not working
1. Gem uninstall rack
2. Follow prompt to remove version of rack that doesn’t work with sinatra

## Error: Localhost not working
1. In terminal try `ping localhost` and check the IP address
2. Try clearing cache and cookies
3. In the terminal try `cat /etc/hosts` to see if localhost is correctly mapped.

## Error: 2.3.0 Ruby Virtual Machine Crash
1. install ruby version 2.3.4 using rvm
2. `rvm use 2.3.4 --default`  
<p class='util--hide'>View <a href='https://learn.co/lessons/terminal-reference'>Terminal Reference</a> on Learn.co and start learning to code for free.</p>
