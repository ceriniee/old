# Development Notes: Dec. 2021 ~ June 2022

Start Date: December 2021

## December 2021 
* I set up the development environment. 
* There were many trials and errors. 
  * First, I tried to work with my local computer (Mac). 
    * My Mac does not have a vram. 
  * So I also tried to work with a Windows computer that has a GPU (RTX 2070 SUPER) and set up a virtual machine (VM). 
    * The Windows desktop had 6 gigabytes of GPU vram, while we needed at least 8-10 gigabytes of GPU vram. 
  * Then, finally, I decided to work with Google Colab as it provided 12+ gigabytes of GPU vram.


## January 2022
* I read through and studied the paper written on [Tri-graph Information Propagation for Polypharmacy Side Effect Prediction (TIP)](https://grlearning.github.io/papers/94.pdf) by Xu, Sang, and Lu. 

## February ~ March 2022
* I read through and studied the code of the TIP project. 
* There were a couple of problems: 
  * Problem 1: The type did not match. 
    * Solution 1: I had to complete type matching. 
    * Problem 2: There were version errors. 
      * Our version and the code’s version was different. 
        * Solution 2: We downgraded, but it still did not work. 
  * Problem 3: There was no saved model. 
    * We added a saved model. 
* We chose TIP-cat mode. 
  * Problem 4: Inefficient code, when called tip-cat, brought another unnecessary one
    * We adjusted the code to be more efficient. This increased the running speed. 
* We made edits to some parts of the code so that the program is easier to use. 

## April 4, 2022
* We installed the Python module Selenium. 
  * This was because we needed the online database. 
  * Selenium is a fast and easy method for data crawling. 
* I introduced myself to web scrpping through Google searching and research. 
  * I learned web scraping through various websites. 
    * [https://www.scrapingbee.com/blog/selenium-python/](https://www.scrapingbee.com/blog/selenium-python/)
    * [https://www.analyticsvidhya.com/blog/2020/08/web-scraping-selenium-with-python/](https://www.analyticsvidhya.com/blog/2020/08/web-scraping-selenium-with-python/)
* I tested what I learnt through web scraping on [Google](www.google.com) and [PubChem](https://pubchem.ncbi.nlm.nih.gov/)
