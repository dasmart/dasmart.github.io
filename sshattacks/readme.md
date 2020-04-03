# Monitoring Off-Port SSH Attacks
I run an ssh small computer that I use for home projects, and I've opened a port on my router so I can ssh into the server when I am traveling. I set up SSH on a high port, because my ISP won't pass incoming traffic on port 22 –not that the port makes a difference from a security standpoint.
I was surprised that it only took about 3 days before my IP got port-scanned and the login attempts started. All the usual suspects. 
  1. root
  2. pi
  3. admin
  4. lots more...
  
I decided it would be fun to see where they're coming from. 

[This is a map of the IP's that found my high port ssh server, and have tried in vain to log in.](https://dasmart.github.io/sshattacks)  I am using http://ipinfo.io for the lookups, and I followed the [Mapbox store locator tutorial](https://docs.mapbox.com/help/tutorials/building-a-store-locator/) for the maps.

It's interesting to see the IP's from China and Moscow. It makes me wonder what they are up to. I suspect they'd like to have US based locations to signup for social media account, and stage disinformation attacks. Ugg. 
