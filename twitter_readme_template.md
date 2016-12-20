<Title of twitter dataset> :
=============================================================

This dataset is being made available using a Creative Commons CC0
Public Domain Dedication. See http://creativecommons.org/publicdomain/zero/1.0/

Data contained within each tweet sample is copyright by the tweet's authors and
is subject to all copyright law. The creator of the dataset makes no assertion
of rights related to the content of each tweet.

The dataset is provided 'as is' without warranty or any representation of
accuracy, timeliness or completeness.

The dataset format is line-oriented JSON in utf8 encoding.


Dataset Overview :
------------------

This dataset contains Twitter JSON data for several Twitter search queries that
were collected the week following the death of Nelson Mandela on December 5, 2013 
using the twarc (https://github.com/edsu/twarc) package that makes use of Twitter's 
search API.  The following searches are included in this dataset.

* `#NelsonMandela`
* `#RIPNelsonMandela`
* `"Nelson Mandela"`

Twitter data making up this dataset was captured between 2013-06-25 and 2013-07-03. 

All Twitter data is stored as line-oriented JSON (each line is a complete JSON
document), and is exactly what was received from the Twitter API.


Files :
-------

* `#NelsonMandela.json.gz`       :    833,273 Tweets for the search #NelsonMandela
* `#RIPNelsonMandela.json.gz`    :  1,475,992 Tweets for the search #RIPNelsonMandela
* `Nelson_Mandela.json.gz`       :  8,369,214 Tweets for the search "Nelson Mandela"


If you find errors or have questions, contact Mark Phillips at
mark.phillips@unt.edu
