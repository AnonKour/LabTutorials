In order to connect to the robot with ethernet in windows we must change the ethernet adapter ip. So for Windows 10 we do the following:

1) Windows key and type ethernet in the search prompt.

2) We select the change ethernet settings.

3) Then under Related settings we click on change adapter settings.

4) In the new window that pops up(Network Connections) we right click on the ethernet adapter and the select properties.

5) In networking tab, we select the Internet Protocol Version 4 (TCP/IPV4) and the properties.

6) We select the option use the following ip address in order to use static ip.

7) On the IP address field we add 192.168.3.20

8) On the subnetmask field we add 255.255.0.0

9) On the default gateway field we add 192.168.3.20.

10) Finaly we can leave the DNS fields empty.

11) Those settings were universal and apply to every ethernet connection so keep that in mind.

Depending on the version the interface may vary.
Also depending on the team the third number, 3 in the above example, may vary as well but it cannot be 0.

For additional help check the images in the screenshots folder.
