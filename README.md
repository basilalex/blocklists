# Ukraine Region-specific DNS blocklist

## Details:

The blocklist aims to provide a safer and more seamless online experience by detecting and classifying domains connected with phishing, malware, scams, pornographic material, and other issues in Ukraine's online environment. By including this blocklist into your DNS settings, you may successfully stop cyber attacks and harmful web components throughout the domain resolution process.

## Lists

| List                                                                         | Description                          |
| ---------------------------------------------------------------------------- | ------------------------------------ |
| [18+](https://github.com/basilalex/blocklists/blob/main/18+.txt)             | 18+                                  |
| [Abuse](https://github.com/basilalex/blocklists/blob/main/abuse.txt)         | Abuse                                |
| [Dating](https://github.com/basilalex/blocklists/blob/main/dating.txt)       | Dating / Dating agencies             |
| [Drugs](https://github.com/basilalex/blocklists/blob/main/drugs.txt)         | Illegal medicines                    |
| [Fraud](https://github.com/basilalex/blocklists/blob/main/fraud.txt)         | Fraud                                |
| [Gambling](https://github.com/basilalex/blocklists/blob/main/gambling.txt)   | Gambling                             |
| [Malicious](https://github.com/basilalex/blocklists/blob/main/malicious.txt) | Malware / Ransomware / Piracy        |
| [Phishing](https://github.com/basilalex/blocklists/blob/main/phishing.txt)   | Phishing / Scam                      |
| [Privacy](https://github.com/basilalex/blocklists/blob/main/privacy.txt)     | Ads / Tracking / Privacy / Analytics |
| [Smoking](https://github.com/basilalex/blocklists/blob/main/smoking.txt)     | Smoking / Vaping / Hookahs           |

All urls are listed in the host files as follows:

**0.0.0.0 example.com**

## <a href="https://pi-hole.net" target="_blank">Pi-Hole</a> instructions:

1. Copy the link to the desired list.
2. Add the URL to your Pi-hole's block lists (**Login** > **Group Management** > **Adlists** > **Paste list URL in "Address" field** > **Click "Add"**)
3. Update Gravity (**Tools** > **Update Gravity** > **Click "Update"** )

## <a href="https://docs.netgate.com/pfsense/en/latest/packages/pfblocker.html" target="_blank">pfBlockerNG</a> instructions:

1. Copy the link to the desired list.
2. Add the URL to your pfBlockerNG's block lists (**Login** > **Firewall** > **pfBlockerNG** > **DNSBL** > **DNSBL Groups** > **Click 2 times on the group** > **Click "Add"** > **Paste list URL in "Source" field** > **Write description in the "Header/Label" field** > **Select ON in the "State" selector** > **Click "Save DNSBL Settings"** )
3. Update pfBlockerNG (**pfBlockerNG** > **Click "Update"** > **Select "Reload" in the "Select 'Force' option" field** > **Click "Run"** )

## Testing Ad Blocking

Open <a href="https://d3ward.github.io/toolz/adblock.html" target="_blank" rel="noopener noreferrer">Test Ad Block</a>.

## Credits

Thank you to the following list maintainers of the sources that were partially used:
<a href="https://github.com/blocklistproject/Lists" target="_blank">blocklistproject</a>,
<a href="https://www.ema.com.ua/citizens/blacklist" target="_blank">EMA</a>,
<a href="https://github.com/StevenBlack/hosts" target="_blank">StevenBlack</a>,
<a href="https://phishing.army/download/phishing_army_blocklist.txt" target="_blank">phishing.army</a>.

## License:

For more details, see the [LICENSE](https://github.com/basilalex/ua-hosts/blob/main/LICENSE) file.
