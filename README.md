# Blocklists

## Details:

A set of hosts files for the UA (Ukraine) region's domain blocking. These lists ought to be used in addition to others.

All urls are listed in the host files as follows:

**0.0.0.0 example.com**

## Lists

| List                                                                       | Description                                                                                          |
| -------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| [18+](https://github.com/basilalex/blocklists/blob/main/18+.txt)           | Filters for 18+ websites.                                                                            |
| [Abuse](https://github.com/basilalex/blocklists/blob/main/abuse.txt)       | Filters for abusive websites.                                                                        |
| [Ads](https://github.com/basilalex/blocklists/blob/main/ads.txt)           | Ads, tracking, privacy, and redirection filters.                                                     |
| [Dating](https://github.com/basilalex/blocklists/blob/main/dating.txt)     | Online dating site filters.                                                                          |
| [Drugs](https://github.com/basilalex/blocklists/blob/main/drugs.txt)       | Websites that sells illegal medicines.                                                               |
| [Fraud](https://github.com/basilalex/blocklists/blob/main/fraud.txt)       | The fraud websites filters.                                                                          |
| [Gambling](https://github.com/basilalex/blocklists/blob/main/gambling.txt) | Filters for legal and illegal gambling sites.                                                        |
| [Malware](https://github.com/basilalex/blocklists/blob/main/malware.txt)   | Websites that host or contain malware, ransomware, or piracy.                                        |
| [Phishing](https://github.com/basilalex/blocklists/blob/main/phishing.txt) | Phishing site filters                                                                                |
| [Smoking](https://github.com/basilalex/blocklists/blob/main/phishing.txt)  | Filters out websites that promote smoking and vaping, as well as online stores that offer equipment. |

## <a href="https://pi-hole.net" target="_blank">Pi-Hole</a> instructions:

1. Copy the link to the desired list.
2. Add the URL to your Pi-hole's block lists (**Login** > **Group Management** > **Adlists** > **Paste list URL in "Address" field** > **Click "Add"**)
3. Update Gravity (**Tools** > **Update Gravity** > **Click "Update"** )

## <a href="https://docs.netgate.com/pfsense/en/latest/packages/pfblocker.html" target="_blank">pfBlockerNG</a> instructions:

1. Copy the link to the desired list.
2. Add the URL to your pfBlockerNG's block lists (**Login** > **Firewall** > **pfBlockerNG** > **DNSBL** > **DNSBL Groups** > **Click 2 times on the group** > **Click "Add"** > **Paste list URL in "Source" field** > **Write description in the "Header/Label" field** > **Select ON in the "State" selector** > **Click "Save DNSBL Settings"** )
3. Update pfBlockerNG (**pfBlockerNG** > **Click "Update"** > **Select "Reload" in the "Select 'Force' option" field** > **Click "Run"** )

## Credits

Thank you to the following list maintainers of the sources that were partially used:
<a href="https://github.com/blocklistproject/Lists" target="_blank">blocklistproject</a>,
<a href="https://www.ema.com.ua/citizens/blacklist" target="_blank">EMA</a>,
<a href="https://github.com/StevenBlack/hosts" target="_blank">StevenBlack</a>,
<a href="https://phishing.army/download/phishing_army_blocklist.txt" target="_blank">phishing.army</a>.

## License:

For more details, see the [LICENSE](https://github.com/basilalex/ua-hosts/blob/main/LICENSE) file.

<!-- tracking blocklist filterlist malware pi-hole phishing ads domains hosts adblock ua adblock-list pi-hole-blocklists pi-hole-lists -->
