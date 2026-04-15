# httpd-agent
Agent to monitor Apache httpd

Copy this to /ust/local/bin and make it executable. Create a cron job
which will run the agent at an interval you want. For demo purposes, I 
will be running it once a minute.

*/1 * * * * /usr/local/bin/httpd_agent

When the service fails, it will send an event to AAP EDA.
