# Home-Assistant-Yeelight
Home Assistant Yeelight Integration

 1. Go to the Yeelight app.
 2. Go to menu
 3. Go to LAN control and make are each device has LAN Control allowed.
 4. Go to HA configuration.yaml and use code

#yeelight
 yeelight:
 devices:
 192.168.x.xxx: # enter you yeelight IP Address if you dont know it use Fing app from google play store to find it.
 name: My Light # Give the light a name
 model: color1 # enter you model
#end yeelight
