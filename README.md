# crank3000

## Usage
* crank3000 is powered via the ethernet cable, use the provided adapter between the router and the crank
* since it sends out OSC messages, your machine needs to be in the same network. the easiest is to use the provided router (ssid: nantlab-wlan, pw: nantlab-wlan-pw). it broadcasts on port 9010
* there are two patches included, a osc to midi cc converter and a grain player

do not connect your laptop to the ethernet cable, 2 wires are used for supplying power that might damage your computer.


## Trouble shooting
* does the led strip work. no => probably a problem with the power supply
* do you receive osc messages on your machine. no => 
    * check with protokol by hexler if you can receive osc messages
    * try to ping the crank: ping 192.178.2.100
    * restart the crank by unplugging the ethernet cable
* still not working => message me

## wanna get fancy
* there is un untested osc route that can configure the crank, it's increment and decrement steps: https://github.com/thomasgeissl/klanglichtstrom/blob/master/io/crank/crank.ino#L89

## credits
thanks ben wesch for the grain pd patch.