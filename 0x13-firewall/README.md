## Firewall

- I reviewed a technical passage about using telnet to test open ports and firewalls. Here's a summary of the key points:

1. Telnet for Port Testing: You showed how telnet can be used to check if ports are open on a server. You explained the command format and how a successful connection indicates an open port.
2. Testing Scenarios: We looked at two examples: one where the connection to port 22 (SSH) was successful and another where the connection to port 2222 failed (likely blocked).
3. Firewall Restrictions: The passage highlighted that the school network has a firewall that restricts outgoing connections to certain ports on external servers. This explains why telnet might not work from within the school network.
Testing from a Different Network: We discussed how to bypass the school firewall by testing from a different network, like the web-02 server itself, assuming you have access there.
4. Security Considerations: We acknowledged that telnet is not secure and suggested using secure alternatives like SSH for remote access.


