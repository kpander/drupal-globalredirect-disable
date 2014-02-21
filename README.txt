README.txt
==========
GLOBAL REDIRECT DISABLE allows you to conditionally disable the Global Redirect 
module based on the current path.

At this time (Nov 25, 2013) the functionality to disable Global Redirect for
specific paths does not exist within the Global Redirect module itself. At a 
point in the future when that does become available, this module should no 
longer be necessary.

Disabling the Global Redirect module can be necessary when we have code using 
hook_url_inbound_alter(). This can conflict with Global Redirect.



AUTHOR/MAINTAINER
=================
Kendall Anderson <dailyphotography at gmail DOT com>
http://invisiblethreads.com



CHANGELOG
=========
v1.0, 2013-11-25
- initial development
