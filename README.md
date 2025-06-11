# wtBRMon
![wtBRMon](https://github.com/lin2yatou/wtBRMon/blob/eecc98eeb51ac5ebebeaa9dcfff29888e6785a7b/public_html/screenshot.jpg "wtBRMon")
A OpenWRT realtime per-IP bandwidth Monitor

## Installation
 - Clone Git repository

 - Copy public_html/cgi-bin/wtBRMon in /[Web Root]/cgi-bin/ i.e. /www/cgi-bin/
 - Copy public_html/www in your web server root folder i.e. /www/wtBRMon/

 - chmod +x /[Web Root]/cgi-bin/wtBRMon

## Launch
 - **Edit /[Web Root]/cgi-bin/wtBRMon and check configuration vars**
 - Open web browser on http://[ROUTER-IP]/cgi-bin/wtBRMon and check if json file is correct (ex: with http://jsonlint.com)
 - Open web browser on http://[ROUTER-IP]/wtBRMon

**Need QOS Uplink and Downlink configured**


Tested on : LinkSys WRT1200AC with OpenWrt Chaos Calmer r46584
