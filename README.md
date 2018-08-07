# Send-SMS-through-NodeMCU-using-IFTTT

This simple program send a text message using Webhooks and Android SMS from IFTTT.
Initially make an applet on IFTTT using webhooks as the trigger and Android SMS as action. You may leave phone number field blank in applet but here we have filled the field.

This particular program sends an sms once from setup loop only when the program is run.

All you need is an NodeMCU, WiFi connection too. IFTTT app on phone is also required.

You can edit the text message to be sent in the program. The best part is that the block can be used in loop() and can be used to notify someone whenever required. 
