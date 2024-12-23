# UPTIME-Kuma-monitoring-port
With Uptime Kuma, we can monitor container ports and send notifications to the client whenever a container port goes up or down


**SITE link: https://betterstack.com/community/guides/monitoring/uptime-kuma-guide/**


    My Uptime Kuma containers are running on the server, and it is configured to monitor the ports of both the remote server and the localhost where my container is running. If the port goes down, it sends a notification to a specific notification channel. I am sending notifications to Snappy, but we can also send notifications to email (SMTP) and multiple other destinations.

I have also attach configuration sereenshots. If you want to monitor localhost container then use  **http://other-container-ip:other-container-port**(because my uptime kuma is also running as container, if a container wants to communicate with other container then it should use other other container ip and other container port. container apny under communication k lye **localhost:port use kerta ha, jesy host-pc na apny under container sa communication kerni hoti ha tu wo localhost:container-port use krta ha**)) or If your want to monitor remote container port. then use  like this **http://remote-instance-ip:container-port** 
