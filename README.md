# node-red-contrib-axis-camera
An Axis Camera administration node that simplifies the most common VAPIX and SOAP/ONVIF API requests including
* Get camera info
* Get JPEG image snapshot
* Get/Set properties
* List/Set user accounts
* Manage MQTT client including event publishing
* List/Start/Stop/Install ACAP
* Restart device
* List/Create Certificates & Signing requests
* List device connections
* Enable remote syslog server
* Update Firmware

## Changelog
### Version 1.3.0
* Fixed a bug in action Info that could crash Node-Red
* Action ACAP list will now respond with an array and not an object if only one ACAP is installed.

### Version 1.2.2
* Added action 'Info' that responds with common needed properties of the camera
* Added support for managing the built-in MQTT client.  Requires Axis firmware >= 9.80

### Version 1.0.1
* Fixed HTTP POST flaw

### Version 1.0.0
* Fixed response on Get Property when authentication failed
* Added HTTP POST


