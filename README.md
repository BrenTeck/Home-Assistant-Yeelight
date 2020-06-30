# Home-Assistant-Yeelight
<pre>Home Assistant Yeelight Integration

 1. Make sure all your devices have static IP address 
 2. Go to the Yeelight app.
 3. Go to menu
 4. Go to LAN control and make are each device has LAN Control allowed.
 5. Go to HA configuration.yaml and use code

"#yeelight
 yeelight:
 devices:
 192.168.x.xxx: # enter you yeelight IP Address if you dont know it use Fing app from google play store to find it.
 name: My Light # Give the light a name
 model: color1 # enter you model
#end yeelight"

References:
https://www.home-assistant.io/integrations/Yeelight/
</pre>
