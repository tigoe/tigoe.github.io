# tigoe.github.io

Hi there. Welcome to my code repositories.

I write code mainly for my classes at [ITP/IMA](https://itp.nyu.edu) at New York University, where I teach (it's [on gitHub](https://github.com/itpnyu) too).  I'm also a co-founder of [Arduino](https://www.arduino.cc) (also [on gitHub](https://github.com/arduino)). Mostly I've written example sketches for some of the core functions and libraries. I also have a number of personal repositories of Arduino sketches. There are a few personal projects here too.

My personal site is at [tigoe.com](https://tigoe.com). My work profile is [on the ITP/IMA site](https://tisch.nyu.edu/about/directory/itp/3558397). 

 -----

## News

 _24 Feb 2022_

I've been using GitHub Pages as a place to build mini-tutorial sites out of my repos for a few years now. It was getting out of hand, so I finally set up this page as a place to access the ones I refer people to most frequently. 

----
 Search my gitHub account:
  <input type="text" id="searchbox" onchange="search();">
  <a href="https://google.com"  id="searcher" class="button">search</a>

----
## Repositories:

Connectivity:<br /> 
  <a href="{{site.baseurl}}/html-for-conndev">HTML For Connected Devices</a> <br /> 
  <a href="{{site.baseurl}}/mqtt-examples">MQTT Client examples</a> <br /> 
  <a href="{{site.baseurl}}/websocket-examples">WebSocket Client examples</a> <br /> 
  <a href="{{site.baseurl}}/Wifi101_examples">Arduino WiFi examples</a> <br /> 
  <a href="{{site.baseurl}}/DataloggingExamples">Arduino Datalogging Examples</a> <br /> 
  <a href="{{site.baseurl}}/PiRecipes">Raspberry Pi Recipes</a> <br /> 
  <a href="{{site.baseurl}}/NodeExamples">Node.js Server and Client Examples</a> <br /> 
  <a href="{{site.baseurl}}/BluetoothLE-Examples">Bluetooth LE Examples</a> <br /> 
  <br /> 
Arduino:<br /> 
  <a href="{{site.baseurl}}/ArduinoGeneralExamples">Arduino General Examples</a> <br /> 
  <a href="{{site.baseurl}}/SoundExamples">Arduino Sound and MIDI Examples</a> <br /> 
  <a href="{{site.baseurl}}/SensorExamples">Arduino Sensor Examples</a> <br /> 
  <a href="{{site.baseurl}}/display-examples">Arduino Display Examples</a> <br /> 
  <br /> 
Light:<br /> 
  <a href="{{site.baseurl}}/LightProjects">Light Projects</a> <br /> 
  <a href="{{site.baseurl}}/hue-control">Philips Hue Control</a> <br /> 
  <a href="{{site.baseurl}}/DMX-Examples">DMX-512 Examples</a> <br /> 
  <a href="{{site.baseurl}}/ArduinoLifx">LIFX Light Bulb Control (Arduino library)</a> <br /> 
  <a href="{{site.baseurl}}/HolidayLights">Holiday Lights</a> <br /> 
  <a href="{{site.baseurl}}/CandleProject">Candle Project</a> <br /> 
  <br /> 
Raspberry Pi:<br /> 
  <a href="https://itpnyu.github.io/clock-club">Clock Club</a> <br /> 


  
  <script>

    function search() {
      let url = 'https://github.com/search?q=user%3Atigoe+';
      let term = document.getElementById('searchbox').value;
      url += term;
      url += "&type=code";
      let mySearchLink = document.getElementById("searcher");
      mySearchLink.href = url;
      mySearchLink.target = "_blank";
      mySearchLink.click();
     
    }
  </script>