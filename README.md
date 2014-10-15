This is the Qlik Sense application discussed in the [blog post here](http://blog.qvsource.com/post/2014/10/02/Analysing-Videos-On-YouTube-Using-QVSource-And-Qlik-Sense).

We have placed a copy of the load script in a separate text file so that it can be viewed on GitHub, otherwise you can simply download and open the qvf file in Qlik Sense.

Important Update (15/10/2014)
-----------------------------
This application was written using Qlik Sense Desktop version 0.96.0. Since this release, Qlik have introduced a 'feature' where the default load script behaviour is to prohibit making load requests from arbitrary URLs. This means that a technique that we discuss below using varaibles to build a URL isn't possible unless you make a change to a Qlik Sense configuration file to enable it. We've put together [a page] (http://wiki.qvsource.com/Disabling-Standard-Mode-In-Qlik-Sense.ashx) that explains how to enable this.
