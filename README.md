# tigoe.github.io

Hi there. Welcome to my code repositories. 

I write code mostly for my classes at [ITP/IMA](https://itp.nyu.edu) at New York University, where I teach.  I'm also a co-founder of [Arduino](https://www.arduino.cc), and mostly have written example sketches for many of the core functions and libraries. I also have a number of personal repositories of Arduino sketches. There are a few personal projects here too.

 
  <!-- Search my gitHub account::
  <input type="text" id="searchbox">
  <input type="submit" value="search" onclick="search();">
<div id="results"></div> -->
  <script>
    function search() {
      let url = 'https://github.com/search?q=user%3Atigoe+';
      let term = document.getElementById('searchbox').value;
      url += term;
      fetchText(url);
    }

function fetchText(url) {
    // parameters for the HTTP/S call
  let params = {
    mode: 'cors', // if you need to turn off CORS, use no-cors
    headers: {    // any HTTP headers you want can go here
      'accept': 'application/text'
    }
  }
  // make the HTTP/S call:
  fetch(url, params)
    .then(response => response.text())  // convert response to text
    .then(data => getResponse(data))    // get the body of the response
    .catch(error => getResponse(error));// if there is an error
}

// function to call when you've got something to display:
function getResponse(data) {
  document.getElementById('results').innerHTML = data;
}
  </script>