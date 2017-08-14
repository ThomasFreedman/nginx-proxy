# nginx-proxy

This repo holds configuration files and scripts for an Nginx web server to proxy websocket requests.

**Files:**<br>
**add-auth** -- script to add passwords to basic authentication file<br>
**load_balancer.conf** -- config file for non-SSL websocket load balancing proxy<br>
**nginx.conf** -- global Nginx server config with ws zone definition<br>
**server_node.conf** -- config file a for non-SSL websocket server used by load balancer<br>
**ssl_server_lb.conf** -- config file, multiple virtual servers w/SSL websockets, bts_tools, acme certs & load balancer.<br>
**ssl_server_node.conf** -- config file provides virtual server nodes for wss websockets, bts_tools and a local server proxy.<br>
