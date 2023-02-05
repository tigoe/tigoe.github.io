## Hi there

I write code mainly for my classes at [ITP/IMA](https://itp.nyu.edu) at New York University, where I teach (it's [on gitHub](https://github.com/itpnyu) too).  I'm also a co-founder of [Arduino](https://www.arduino.cc) (also [on gitHub](https://github.com/arduino)). Mostly I've written example sketches for some of the core functions and libraries. I also have a number of personal repositories of Arduino sketches. There are a few personal projects here too.

My personal site is at [tigoe.com](https://tigoe.com). My work profile is [on the ITP/IMA site](https://tisch.nyu.edu/about/directory/itp/3558397). 

 Search my gitHub account:
  <input type="text" id="searchbox" onchange="search();">
  <a href=""  id="searcher" class="button">search</a>

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