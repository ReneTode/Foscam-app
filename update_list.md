2.0 (2017/9/1)
  - complete rewrite from version 1

2.0.1 (2018/1/1)
  - split cams into 3 groups
  - added 2 dashboards for cams without PTZ and without infrared
  - changed the motion detect on/off switch handling
  - added automatic install for untangle
  
2.0.2 (2018/1/2)
  - changed from untangle to xml.etree
  - moved flip and mirror check to initialize
  - changed from urllib to requests for performance reason
  
2.0.3 (2018/1/24)
  - changed the logging to intercept timeout exceptions.
  - changed timeout logging level from warning to info

3.0 (2018/2/19)
  - updated for appdaemon 3.0
  - added dashboard dir to yaml