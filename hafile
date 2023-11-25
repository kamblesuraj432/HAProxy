FROM haproxy:latest

# Set the HAProxy configuration file
COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg

# Expose port 80 for HAProxy
EXPOSE 80

# Start the HAProxy service
CMD ["haproxy", "-f", "/usr/local/etc/haproxy/haproxy.cfg"]
