# SaaS Startup Checklist

- [ ] [YSlow! Web Performance Best Practices and Rules](#yslow!-web-performance-best-practices-and-rules)
- [ ] [Application Performance Monitoring](#application-performance-monitoring)
- [ ] [Error Tracking](#error-tracking)


## Resources

### YSlow! Web Performance Best Practices and Rules

Yahoo!'s Exceptional Performance team has identified a number of [best practices for making web pages fast](http://developer.yahoo.com/performance/rules.html).

1. [Minimize HTTP Requests](http://developer.yahoo.com/performance/rules.html#num_http)
2. [Use a Content Delivery Network](http://developer.yahoo.com/performance/rules.html#cdn)
3. [Avoid empty src or href](http://developer.yahoo.com/performance/rules.html#emptysrc)
4. [Add an Expires or a Cache-Control Header](http://developer.yahoo.com/performance/rules.html#expires)
5. [Gzip Components](http://developer.yahoo.com/performance/rules.html#gzip)
6. [Put StyleSheets at the Top](http://developer.yahoo.com/performance/rules.html#css_top)
7. [Put Scripts at the Bottom](http://developer.yahoo.com/performance/rules.html#js_bottom)
8. [Avoid CSS Expressions](http://developer.yahoo.com/performance/rules.html#css_expressions)
9. [Make JavaScript and CSS External](http://developer.yahoo.com/performance/rules.html#external)
10. [Reduce DNS Lookups](http://developer.yahoo.com/performance/rules.html#dns_lookups)
11. [Minify JavaScript and CSS](http://developer.yahoo.com/performance/rules.html#minify)
12. [Avoid Redirects](http://developer.yahoo.com/performance/rules.html#redirects)
13. [Remove Duplicate Scripts](http://developer.yahoo.com/performance/rules.html#js_dupes)
14. [Configure ETags](http://developer.yahoo.com/performance/rules.html#etags)
15. [Make AJAX Cacheable](http://developer.yahoo.com/performance/rules.html#cacheajax)
16. [Use GET for AJAX Requests](http://developer.yahoo.com/performance/rules.html#ajax_get)
17. [Reduce the Number of DOM Elements](http://developer.yahoo.com/performance/rules.html#min_dom)
18. [No 404s](http://developer.yahoo.com/performance/rules.html#no404)
19. [Reduce Cookie Size](http://developer.yahoo.com/performance/rules.html#cookie_size)
20. [Use Cookie-Free Domains for Components](http://developer.yahoo.com/performance/rules.html#cookie_free)
21. [Avoid Filters](http://developer.yahoo.com/performance/rules.html#no_filters)
22. [Do Not Scale Images in HTML](http://developer.yahoo.com/performance/rules.html#no_scale)
23. [Make favicon.ico Small and Cacheable](http://developer.yahoo.com/performance/rules.html#favicon)

### Application Performance Monitoring

Monitor application performance and track historical trends. 
Should include page load times, error rates, slow transactions, servers resource usage. Correlate performance metrics with deployments/releases. Alerting for severe performance degradation.

* [NewRelic](http://newrelic.com/) - _A powerfully simple way to monitor your Web & Mobile applications._

### Error Tracking

Aggregate client and server errors, exceptions and failures. Should include stack traces, environment information, intelligent notifications, trend analysis. 

* [Sentry](https://getsentry.com/welcome/) - _Know immediately when things happen in your application. Engage users before they have a chance to report a problem._
* [Airbrake](http://airbrake.io/) - _With deploy tracking, logging, dupe detection and a dashboard to track your exceptions, managing and triaging errors has never been easier._
* [RayGun](http://raygun.io/) - _Real time error reporting you can set up in under 5 minutes!_
* [Exceptional](http://www.exceptional.io/) - _Tracks errors in web apps. It reports them in real-time and gathers the info you need to fix them fast._

#### Client-side error tracking

* [Errorception](http://errorception.com/) - _Simple and painless way to find out about JavaScript errors, as they occur in your users' browsers. All you need to do is insert a script tag on your page, and you will start recording errors as they happen in real-time._
* [QBaka](https://qbaka.com/) - _Cloud-based frontend error monitoring and analytics for web services & mobile HTML5._
* [JSLogger](http://jslogger.com/) - _Log Javascript errors and events in the cloud._
* [Muscula](http://www.muscula.com/) - _Log your JavaScript errors, so you can fix them._
* [BugSense](https://www.bugsense.com/) - _Get actionable reports on the health of your Javascript apps & websites!_
* [ExceptionHub](http://www.exceptionhub.com/) - _Easy Setup, drop in code and start collecting errors._
