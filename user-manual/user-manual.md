Smart WiFi Tag (ESP32-C3) - User Instructions
IMPORTANT: READ ALL SAFETY WARNINGS BEFORE USE
This is a DIY/hobbyist product. No warranty. Use at your own risk.
WHAT'S IN THE BOX
Smart WiFi Tag (ESP32-C3) with vibration motor and buzzer
Rechargeable battery with JST connector
Type-C charging module (detachable)
Quick Reference Card (contains WiFi SSID and password)
NOT INCLUDED: USB cable or charging brick. You will need your own Type-C to Type-C/A cable and a standard 5V USB charging brick.
CRITICAL BATTERY SAFETY - READ FIRST
NEVER plug the battery directly into a charging brick
NEVER use a third-party charging module
ALWAYS match polarity: Red wire to Red terminal, Black wire to Black terminal
Incorrect connection may cause battery puffing, fire, or explosion
STEP 1: INITIAL POWER SETUP (DO THIS FIRST)
Pre-charge the charging module
Connect the Type-C charging module to a 5V USB brick using your own Type-C cable
Charge for approximately 2 minutes until the module indicator shows full
Disconnect from power
Open the tag
Gently pry off the front cover using your fingernail or a plastic tool
Connect the battery
Locate the red JST connector inside the tag
Align Red wire to Red terminal, Black wire to Black terminal
Press firmly until it clicks into place
A solid red LED will light up to confirm the tag is powered on
Close the tag
Snap the front cover back on securely
STEP 2: CONTROL VIA ANDROID APP (RECOMMENDED)
Note: The app is not on the Play Store. You must build it from source.
Install the App:
Visit our website and go to our GitHub page
Open the App Repository
Download the source code for the latest release
Build the app using Android Studio or your preferred development environment
On your Android device, enable "Install from Unknown Sources" in Settings
Install the generated .apk file
Connect and Control:
Open the app and tap "Go to App" then "Tag List"
Find the tag named "Inconnu" and tap to open its controls
BEFORE using any controls, connect your phone to the tag's WiFi:
Go to Settings > WiFi on your phone
Select the SSID printed on your Quick Reference Card
Enter the password from the same card
Return to the app and use the buttons to:
Buzz the tag
Vibrate the tag
Adjust intensity or duration if options are available
Tip: Walk around while triggering buzz or vibrate to help locate a lost tag.
STEP 3: CONTROL VIA WEB UI (FOR NON-ANDROID DEVICES OR FALLBACK)
Connect your device (phone, tablet, or laptop) to the tag's WiFi access point
(SSID and password are on your Quick Reference Card)
Open any web browser and type in the address bar:
http://192.168.4.1
The Control Panel will load. Use the on-screen buttons to:
Trigger vibration or buzz in real-time
Monitor connection status
Access additional features depending on firmware version
Note: The Web UI works on any device with a browser: iOS, Windows, macOS, Linux.
QUICK TROUBLESHOOTING
Problem: Red LED not lighting up
Solution: Re-check battery polarity. Ensure the JST connector is fully seated.
Problem: Cannot find "Inconnu" tag in the app
Solution: Ensure you are connected to the tag's WiFi access point first. Refresh the tag list.
Problem: Web UI will not load at 192.168.4.1
Solution: Confirm your WiFi connection. Try incognito mode or clear your browser cache.
Problem: Buzz or vibrate not responding
Solution: Check battery level. Move closer to the tag. Reconnect to the access point.
Problem: Tag not appearing after reset
Solution: Hold the tag button for 10 seconds to factory reset. Then re-follow the setup steps.
CRITICAL SAFETY WARNINGS
Fire and Heat Hazards:
DO NOT expose to temperatures above 55 degrees Celsius (131 degrees Fahrenheit)
KEEP AWAY from open flame, sparks, or flammable materials
NEVER puncture, crush, bend, or short-circuit the battery
STOP USE IMMEDIATELY if the battery swells, leaks, or overheats
Water and Environment:
NOT WATERPROOF - This product has no IP rating
DO NOT SUBMERGE or expose to rain, humidity, or any liquids
Wipe only with a dry, soft cloth
Child Safety:
CHOKING HAZARD - Small parts. Keep away from children under 3 years old
Swallowing electronic components may cause serious injury or death
Store out of reach of children when not in use
Power and Charging:
USE ONLY the provided Type-C charging module for the initial charge
NEVER connect the battery directly to any power source
DO NOT use third-party charging modules or modified cables
Charge only with a standard 5V USB brick (1 amp or less recommended)
Compatibility:
DO NOT use third-party or homemade tags with this system
Clones may have incompatible electronics and cause malfunction
Service centers will not repair homemade or modified units
SUPPORT, REPAIRS, AND LEGAL
Warranty and Liability:
This product is sold AS-IS with NO WARRANTY. You accept all risks associated with use, modification, or failure.
Support Options:
Instant mobile support: Call [Your Support Number]
Authorized service centers: Available across the country for low-cost repairs
(Bring original proof of purchase. Clones and homemade units are not accepted.)
Feedback and Community:
Report bugs or suggest features via GitHub Issues in the app repository
Join our community forum: [Your Forum/Discord Link]
Document Info:
Version: 1.0
Last Updated: [Date]
For latest documentation: Visit [Your Website]/docs
Pro Tip: Keep the Quick Reference Card with your tag. It contains the unique WiFi credentials needed for setup. Take a photo of it as a backup.
Ready to use?
Charge the module
Connect the battery (Red to Red, Black to Black)
Connect to the tag's WiFi access point
Use the app or web UI to buzz or vibrate the tag
End of Instructions