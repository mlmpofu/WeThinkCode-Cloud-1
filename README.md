# WeThinkCode-Cloud-1

# 1st Step
--------------------------------------------------------------------------------------------------------------------------------------

# DNS (Domain Name Systems):

The Internet's DNS system works much like a phone book by managing the mapping between names and numbers. ... DNS servers translate requests for names into IP addresses, controlling which server an end user will reach when they type a domain name into their web browser. These requests are called "queries."

# DNS example step 1
Translate:
-> www.domainname.co.za------->>>>TLD which is the top level domain like .com or .co.za****
# Route 53
-> route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.068.1.9
www.domainame.com --->>> 192.068.1.9----->>> www.domainame.com(Web page or website) send it to end user.

# 2nd Step
------------------------------------------------------------------------------------------------------------------------------------
# CDN (Content Delivery Network)

-> A CDN is a way to deliver content from your website or mobile application to people more quickly and efficiently, based on their geographic location
->It is the one responsible for loading website content faster so that it is easily updated across all platforms.
-> By storing all the content in the S3 (Simple storage service) so that it can retrieve things like images or videos faster without a hustle and speed up the loading time on the WEB.

# 3rd Step
------------------------------------------------------------------------------------------------------------------------------------

# LOAD BALANCERS

-> Load balancing is defined as the methodical and efficient distribution of network or application traffic across multiple servers in a server farm. Each load balancer sits between client devices and backend servers, receiving and then distributing incoming requests to any available server capable of fulfilling them.

# 4th Step
------------------------------------------------------------------------------------------------------------------------------------

# Auto Scaling and EC2 instances

->  EC2 Auto Scaling helps you maintain application availability and allows you to automatically add or remove EC2 instances according to conditions you define.
-> It checks hhow many instances are available the distribute the load depending on the traffic.

# Final Step
-----------------------------------------------------------------------------------------------------------------------------------

-> The Remote Desktop Service allows remote users to see and use Windows on a device in another location.