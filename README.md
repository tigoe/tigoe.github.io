# tigoe.github.io

Hi there. Welcome to my code repositories.

I write code mostly for my classes at [ITP/IMA](https://itp.nyu.edu) at New York University, where I teach (it's [on gitHub](https://github.com/itpnyu) too).  I'm also a co-founder of [Arduino](https://www.arduino.cc) (also [on gitHub](https://github.com/arduino) ). Mostly have written example sketches for some of the core functions and libraries. I also have a number of personal repositories of Arduino sketches. There are a few personal projects here too.

My personal site is at [tigoe.com](https://tigoe.com). My work profile is [on the ITP/IMA site](https://tisch.nyu.edu/about/directory/itp/3558397). 

 -----
 
## News

 _24 Feb 2022_

I've been using GitHub Pages as a place to build mini-tutorial sites out of my repos for a few years now. It was getting out of hand, so I finally set up this page as a place to access the ones I refer people to most frequently. 

----
 Search my gitHub account:
  <input type="text" id="searchbox" onchange="search();">
  <a href="https://google.com"  id="searcher" class="button">search</a>

  
  <script>

    function search() {
      let url = 'https://github.com/search?q=user%3Atigoe+';
      let term = document.getElementById('searchbox').value;
      url += term;
      let mySearchLink = document.getElementById("searcher");
      mySearchLink.href = url;
      mySearchLink.target = "_blank";
      mySearchLink.click();
     
    }
  </script>