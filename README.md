# Hotel-Chain-Network
Network topology  for hotel chain

Hotel Chain Network is a project taken up to understand the networking within multiple branches of a single hotel chain, and how the different departments communicate with each other. Crimson Hotels have their branches in Delhi, Mumbai and Jaipur. Each branch has 5 departments to help with smooth functioning and organisation. The departments are:
Reception
Reservation
Accounts
Food and Beverage
Guest Rooms

There are three main routers for each city,  and they are connected to one central router, which is further connected to the dns and http servers. The main routers are then connected to the switches/wireless access points designated for the departments via a main switch. The department switches are connected to the end devices. There is also a wireless network facility for the rooms and food court for the guests to use. The data related to the hotels and its website is stored on the central web server. The website www.crimsonhotels.in  is the website for our hotel chain.

<h3>Key Properties</h3>
<ul>
<li>Ospf protocol</li>
<li>DHCP </li>
<li>DNS/HTTP</li>
<li>Wireless</li>
</ul>
<img src="https://github.com/gauravragini/Hotel-Chain-Network/blob/master/pdu.gif" alt="topology"/>

<h3>Development Environment </h3>
The project is developed using Cisco Packet Tracer (version 7.3).</br>
