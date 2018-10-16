# Demo_WSN
Demo Wireless Sensor Network

*** Folder:
	+ border-router_CC2530: border router for cc2530dk
	+ border-router_CC2538_sky: border router for cc2538dk and cooja
	+ cli_node: code for demo, upload 1 node.
	+ command-line: command line interface

*** USER GUIDE:
	- For using cc2530, move Demo_WSN-master to contiki-sensinode/examples
	- cli_node/Makefile: edit TARGET_CC2530=1 and compile.

	- For using cc2538 and cooja, move Demo_WSN-master to contiki/examples
	- cli_node/Makefile: edit TARGET_CC2530=0 and compile.

	- compile and load code border + node to your target.
	- compile command-line: gcc cli.c -o cli
	- connect target and tunslip6.
	- ping6 to check node.
	- open terminal: 
				cd $(CONTIKI)/examples/Demo_WSN-master/cli
				./cli <ipv6> 3000 <cmd>

	whereby, <ipv6> is node's ipv6 address you want to control
			 <cmd> led_on, led_off, get_rssi
				

