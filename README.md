# freepbx-grandstream-phonebook
A freepbx dynamic xml phonebook generator for GXP21xx/GXP14xx/GXP116x/GXVxxxx grandstream phones

Place the script in /var/www/html and point your grandstream phones at it to get a phonebook with all the contacts on the pbx. The phone should authenicate with the same login info it uses for SIP. (It's extension as the username and it's sip secret as the password)


xml generated per this guide: http://www.grandstream.com/sites/default/files/Resources/gxp_wp_xml_phonebook.pdf
