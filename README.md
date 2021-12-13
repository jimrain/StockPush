# Django Stock push application using Pushpin 


This applicaiton is to test and learn about websockets, pushpin and eventally fanout.  
For most of the set up a followed this [Fanout Blog Post][fblog] for Rust-based Compute@Edge projects. 
This also uses the Django [Event Stream][fstream] package.
## Usage
To run locally
- Start pushpin:  pushpin --route="* localhost:8000"
- Start Django runserver: ./manage runserver
- Opent the page: http://localhost:7999/stockpusher/


[fblog]: https://blog.fanout.io/2014/11/06/building-a-realtime-api-in-django/
[fstream]: https://github.com/fanout/django-eventstream


