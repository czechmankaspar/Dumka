FROM debian
 
RUN apt-get update && apt-get install lighttpd -y
 
EXPOSE 80
 
ADD lighttpd.conf .
ADD index.html .
 
CMD lighttpd -D -f lighttpd.conf
