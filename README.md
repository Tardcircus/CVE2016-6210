# CVE2016-6210
CVE 2016-6210 OpenSSH 7.2p2 Time response vulnerability to enumerate usernames


Description
A covert timing channel flaw was found in the way OpenSSH handled authentication of non-existent users. A remote unauthenticated attacker could possibly use this flaw to determine valid user names by measuring the timing of server responses.


This tool was created to take advantage of CVE2016-6210 to enumerate username on OpenSSH 7.2p2.
I updated the deprecated modules to keep it going.
