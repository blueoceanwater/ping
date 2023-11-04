# ping

Original "ping" C Program from https://nsrc.org/wrc/materials/source.html 


 			P I N G . C
 
  Using the InterNet Control Message Protocol (ICMP) "ECHO" facility,
  measure round-trip-delays and packet loss across network paths.
 
  Author -
 	Mike Muuss
 	U. S. Army Ballistic Research Laboratory
 	December, 1983
  Modified at Uc Berkeley
 
  Changed argument to inet_ntoa() to be struct in_addr instead of u_long
  DFM BRL 1992
 
  Status -
 	Public Domain.  Distribution Unlimited.
 
  Bugs -
 	More statistics could always be gathered.
 	This program has to run SUID to ROOT to access the ICMP socket.
