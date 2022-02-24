# tigoe.github.io

Hi there. Welcome to my code repositories. 

I write code mostly for my classes at [ITP/IMA](https://itp.nyu.edu) at New York University, where I teach.  I'm also a co-founder of [Arduino](https://www.arduino.cc), and mostly have written example sketches for many of the core functions and libraries. I also have a number of personal repositories of Arduino sketches. There are a few personal projects here too.

 
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