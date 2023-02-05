## Hi there

I work at NYU's [ITP/IMA](https://itp.nyu.edu), where I teach about physical computing, networks, and light.  I'm also a co-founder of [Arduino](https://www.arduino.cc) (also [on gitHub](https://github.com/arduino)), where I've written many example sketches. This site contains code I've written for both of those, ans some personal work as well.

My personal site is at [tigoe.com](https://tigoe.com). My work profile is [on the ITP/IMA site](https://tisch.nyu.edu/about/directory/itp/3558397). 

----
## Repositories:

### Connectivity:
* [HTML For Connected Devices]({{site.baseurl}}/html-for-conndev)
* [MQTT Client examples]({{site.baseurl}}/mqtt-examples)
* [WebSocket Client examples]({{site.baseurl}}/websocket-examples)
* [Arduino WiFi examples]({{site.baseurl}}/Wifi101_examples)
* [Arduino Datalogging Examples]({{site.baseurl}}/DataloggingExamples)
* [Raspberry Pi Recipes]({{site.baseurl}}/PiRecipes)
* [Node.js Server and Client Examples]({{site.baseurl}}/NodeExamples)
* [Bluetooth LE Examples]({{site.baseurl}}/BluetoothLE-Examples)

### Arduino:<br /> 
* [Arduino General Examples]({{site.baseurl}}/ArduinoGeneralExamples)
* [Arduino Sound and MIDI Examples]({{site.baseurl}}/SoundExamples)
* [Arduino Sensor Examples]({{site.baseurl}}/SensorExamples)
* [Arduino Display Examples]({{site.baseurl}}/display-examples) 
 
### Light:<br /> 
* [Light Projects]({{site.baseurl}}/LightProjects)
* [Philips Hue Control]({{site.baseurl}}/hue-control)
* [DMX-512 Examples]({{site.baseurl}}/DMX-Examples)
* [LIFX Light Bulb Control (Arduino library)]({{site.codeurl}}/ArduinoLifx)
* [Holiday Lights]({{site.codeurl}}/HolidayLights)
* [Candle Project]({{site.codeurl}}/CandleProject)

### Raspberry Pi:<br /> 
* [Clock Club](https://itpnyu.github.io/clock-club) 


  
  <script>

    function search() {
      let url = 'https://github.com/search/advanced?q=user%3Atigoe+';
      let term = document.getElementById('searchbox').value;
      url += term;
      url += '&type=Repositories&ref=advsearch&l=&l=';
      let mySearchLink = document.getElementById("searcher");
      mySearchLink.href = url;
      mySearchLink.target = "_blank";
      mySearchLink.click();
    }
  </script>