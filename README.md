# UI Analyser

Parse, store and analyse logs, gathered from users interaction with
different user interfaces on a the web.

# Requirements

* [LogStash](http://logstash.net/)
* [ElasticSearch](http://www.elasticsearch.org/)
* [Kibana](http://www.elasticsearch.org/overview/kibana/)

# Logs

These logs are generated for testing performance of **different** user interfaces for pre-defined purposes.
Currently interaction is being tracked for the [simple gallery app](https://github.com/sedovsek/gallery-ui), which comes with two different UIs (tappy and swipey).

[Pixel-tracker](https://github.com/sedovsek/gallery-ui/tree/master/tracker) is being used to track and store the events (clicks, drags, swipes, photography views, etc.) as they occur.  
**UI-Analyser** is here to take care of the analysis.
