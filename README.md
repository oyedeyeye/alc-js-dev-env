# alc-js-dev-env
JavaScript Development Environment from Andela ALC 4.0 Grow with Google and Pluralsight

# My Notes
 install local tunnel to share live preview of work in progress

# npm install localtunnel -g

 After Installation Run it with

# lt --port 3000 or add --subdomain oyedeyeye

 Output a link to your local server 

stop the LT running
 # CTRL C 

With Browser Sync and LocalTunnel, you can test your app across devices.

To run your Server and what you are bulding locally

# node buildScripts/srcServer.js 


#* Automation using npm scripts
add your app starting point to package.json instead of running it from commandline all the time
# "start": "node buildScripts/srcServer.js"
Add the above to "script": {}

Start message use "prestart" runs before start.
#  "prestart": "node buildScripts/startMessage.js", //I got an error here when I Used the package.json recommended by the course
