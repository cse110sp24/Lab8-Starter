# Lab8-Starter

How are graceful degradation and service workers related? 

Graceful degradation is the ability for a web app to maintian limited functionality when some part of it is inoperative. Service workers help manage the cache and allow requests to resolve without an internet connection. In this case, if the internet is inoperative, the web app can use service workers and the cache in order to fetch data.