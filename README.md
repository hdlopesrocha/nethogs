This a version of Nethogs that does not uses ncurses, by other words, it's very easy to parse.

I did this fork because I had to collect network information for my master thesis.

By the way, the man pages are wrong, some functionalities were removed.

Expected result:

<code>
NetHogs version 0.8.2-hdlopesrocha
TIME PID USER PROGRAM DEV SENT RECEIVED
Ethernet link detected
Waiting for first packet to arrive (see sourceforge.net bug 1019381)
2016-02-11.13:44:02	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     0.013	     0.013KB/sec
2016-02-11.13:44:03	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     0.013	     0.013KB/sec
2016-02-11.13:44:04	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     4.563	   398.814KB/sec
2016-02-11.13:44:05	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     4.696	   398.910KB/sec
2016-02-11.13:44:06	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     5.650	   460.069KB/sec
2016-02-11.13:44:07	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     5.650	   460.069KB/sec
2016-02-11.13:44:08	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     5.650	   460.069KB/sec
2016-02-11.13:44:09	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     5.650	   460.069KB/sec
2016-02-11.13:44:10	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     1.011	    61.209KB/sec
2016-02-11.13:44:11	   3170	hdlopesrocha	/usr/lib/firefox/firefox	wlan0	     0.115	     0.101KB/sec
</code>

Enjoy ;-)

