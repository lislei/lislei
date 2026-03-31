To get up to speed in a giffy I have some pointers:

 * Dashlane Password Manager
 * [Cloud control](https://nnrimg022.statkart.no:7803/em/)
 * [jit.skip](https://jit.skip.kartverket.no/)
 * [GitHub](https://github.com/kartverket) - link private github account
 * [Confluence](https://kartverket.atlassian.net/wiki/) - sign in with email
 * [JIRA](https://kartverket.atlassian.net/jira) - sign in with email
 * [Innsida](https://kartverket.sharepoint.com/) - SSO/AD
 * [Kartverket.dev](https://kartverket.dev/) - SSO/AD
 * [Kartverket.dev - matrikkel](https://kartverket.dev/catalog/default/component/matrikkel)
 * [Webmail](https://outlook.office.com/mail/) - SSO/AD
 * [Service-portal](https://kartverket.pureservice.com/) - SSO/AD
 * [BookStack](https://dokuhylla.statkart.no/) -  
 * [fellesdata - H:disk](smb://statkart.no/fellesdata)

Ubuntu 24.04 config:
 * [Disable CTRL+SHIFT+U to enter unicode char](https://superuser.com/questions/358749/how-to-disable-ctrlshiftu/1392682#1392682) as this is the shortcut for uppercase in IntelliJ.
   * `gsettings set org.freedesktop.ibus.panel.emoji unicode-hotkey "@as []"`
* Set up VPN
  * `wget https://raw.githubusercontent.com/lislei/lislei/refs/heads/main/kartverket/kv-ovpn.ovpn`
  * `nmcli connection import type openvpn file kv-ovpn.ovpn`
  * `nmcli connection modify "kv-ovpn" +vpn.data username="${USERNAME}"`
* Lokal utvikling Heimdall
  * `nano ~/.bashrc`
```shell 
#
# Heimdall local dev
#
export GITHUB_USER="$(printf 'protocol=https\nhost=github.com\n' | git credential fill | grep '^username=' | cut -d= -f2)"
export PACKAGES_TOKEN="$(printf 'protocol=https\nhost=github.com\n' | git credential fill | grep '^password=' | cut -d= -f2)"
```

