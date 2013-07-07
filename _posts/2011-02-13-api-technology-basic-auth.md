---
layout: post
title: 'API Technology Basic Auth'
url: 'http://apievangelist.com2011/02/13/api-technology-basic-auth/'
image: ''
---
{% include JB/setup %}
<img src="http://kinlane-productions.s3.amazonaws.com/basic-auth.png"  width="250" align="right" />Basic Auth is a way for a web browser or application to provide credentials in the form of a username and password.
Because Basic Auth is integrated into <a  title="Hypertext Transfer Protocol"  href="http://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol">HTTP protocol</a> it is the easiest way for users to authenticate with a <a  title="Representational State Transfer"  href="http://en.wikipedia.org/wiki/Representational_State_Transfer">RESTful API</a>.
Basic Auth is easily integrated, however if <a  title="Transport Layer Security"  href="http://en.wikipedia.org/wiki/Transport_Layer_Security">SSL</a> is not used, the username and password are passed in plain text and can be easily intercepted on the open Internet.
OAuth is a much better choice for RESTful API authentication, but Basic Auth is perfectly suited for APIs that are intended for a wider audience and do not give access to sensitive information.
<h6 >
     Related articles
</h6>
<ul >
     <li >
          <a href="http://blog.apievangelist.com/2011/02/10/instapaper-launches-full-api/">Instapaper Launches Full API</a> (apievangelist.com)
     </li>
     <li >
          <a href="http://blog.programmableweb.com/2011/01/11/google-adds-api-for-url-shortener-and-link-analytics/">Google Adds API For URL Shortener and Link Analytics</a> (programmableweb.com)
     </li>
     <li >
          <a href="http://blog.apievangelist.com/2011/02/12/api-status-dashboard-with-pingdom/">API Status Dashboard with Pingdom</a> (apievangelist.com)
     </li>
</ul>
