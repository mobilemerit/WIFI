WIFI
====
Wifi Android project based on Wi-Fi APIs provide a means by which applications can communicate with the lower-level wireless stack that provides Wi-Fi network access. Almost all information from the device supplicant is available, including the connected network's link speed, IP address, negotiation state, and more, plus information about other networks that are available. 
WifiManager class provides the primary API for managing all aspects of Wi-Fi connectivity. ScanResult Describes information about a detected access point. In addition to the attributes described here, the supplicant keeps track of quality,noise, and maxbitrate attributes, but does not currently report them to external clients. Its contains fields like
public String
BSSID
The address of the access point.
public String
SSID
The network name.
public String
capabilities
Describes the authentication, key management, and encryption schemes supported by the access point.
public int	frequency
The frequency in MHz of the channel over which the client is communicating with the access point.
public int	level
The detected signal level in dBm.
public long	timestamp
Time Synchronization Function (tsf) timestamp in microseconds when this result was last seen.

