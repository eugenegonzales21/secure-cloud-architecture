# Secure Cloud Architecture Plan
Users
  ↓
CDN
  ↓
Load Balancer
  ↓
Application Servers
  ↓
Private Database
## CDN
The CDN stores cached copies of static content closer to users to improve loading speed.
## Load Balancer
The load balancer distributes incoming requests across multiple application servers.

## Application Servers
Application servers process requests from users. These servers should be placed in a private subnet.

## Database
The database stores student records. The database should remain private and should not be directly accessible from the Internet.
# Public and Private Resources

