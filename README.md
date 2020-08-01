# Web Quality Assessment
## Project Description
### Description: 
Site-level classification for the genre of the web sites (editorial, news, commercial, educational, deep Web, or Web spam and more) as well as their readability, authoritativeness, trustworthiness and neutrality. The data set consists of sample Web hosts from Europe. The training and testing samples are biased towards the interesting aspects and cleansed manually from mixed sites, Web hosting, and adult content. Features similar to those used to filter Web spam based on content and linkage information are be provided on the host level, along with natural language processing annotations of a large set of sample pages.
### Size
4019 total examples; 1522 labeled (for English subset) <br>
multiple web based and NLP based variables <br>
2GB compressed text
## Environment
~~~
python3.7 -m venv venv
~~~
~~~
source venv/bin/activate
~~~
~~~
pip install -r requirements
~~~
~~~
jupyter notebook
~~~