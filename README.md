# SaaS Startup Checklist

## Development

- [ ] Source Code Repository
- [ ] Continuous Integration
- [ ] [Cross Browser Testing](#cross-browser-testing)
- [ ] [API](#api)

## Deployment

- [ ] [Domain Name](#domain-name)
- [ ] [Hosting](#hosting)
- [ ] [Automated Deployment](#automated-deployment)
- [ ] [Backups](#backup)
- [ ] [Redundancy and Failover](#redundancy-and-failover)
- [ ] [Alert and Monitoring](#alert-and-monitoring)
- [ ] [Transport Layer Security](#ssl-certificate)
- [ ] [Content Delivery Network](#content-delivery-network)
- [ ] [YSlow! Web Performance Best Practices and Rules](#yslow!-web-performance-best-practices-and-rules)
- [ ] [Application Performance Monitoring](#application-performance-monitoring)
- [ ] [Error Tracking](#error-tracking)
- [ ] [Analytics](#analytics)
- [ ] [Social Media](#social-media)
- [ ] [Status Page](#status-page)
- [ ] [Image Optimisation](#image-optimisation)
- [ ] [Feedback Form](#feedback-form)

## Resources

### Cross Browser Testing

* [BrowserSwarm](http://www.browserswarm.com/)
* [Sauce Labs](https://saucelabs.com/)

### API

#### Documentation

* [API Blueprint](http://apiblueprint.org/) - _API Documentation with powerful tooling._
* [API Blueprint Language Specification](https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md)
* [iglo](https://github.com/subosito/iglo) - _API Blueprint's formatter._
* [Apiary](http://apiary.io/) - _Build beautiful APIs with collaborative design, instant API mock, generated documentation, integrated code samples, debugging and automated testing._

### Domain Name

* [Namecheap](http://www.namecheap.com/)
* [Gandi](https://www.gandi.net/)

### Hosting

#### Virtual Private Server (VPS)

* [Linode](https://www.linode.com/)

#### Dedicated Server

* [OVH](https://www.ovh.co.uk/dedicated_servers/)
* [Digital Ocean](https://www.digitalocean.com/)
* [Hetzner](http://www.hetzner.de/en/hosting/)

#### Cloud

* [Amazon EC2](http://aws.amazon.com/)
* [Rackspace Cloud](http://www.rackspace.co.uk/cloud)

### Automated Deployment

### Backups

Database replication and frequent, off-site backups.

* [Amazon S3](http://aws.amazon.com/s3/)

### Redundancy and Failover

Server redundancy and fail-over, load balancing. Multiple, redundant hosting providers to handle datacenter outages.

### Alert and Monitoring

* [PagerDuty](http://www.pagerduty.com/) - _Provides SaaS IT on-call 
schedule management, alerting and incident tracking._

### Transport Layer Security

Keep your customer's data safe by using an encrypted connection with an SSL certificate. Mandatory for registration and login pages.

### Content Delivery Network

Optimise delivery of web pages, block threats and limit abusive bots and crawlers.

* [CloudFlare](https://www.cloudflare.com)

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
* [Errbit](http://errbit.github.io/errbit/) - _The open source, self-hosted error catcher._
* [Google Stackdriver Error Reporting](https://cloud.google.com/error-reporting/) - _Real-time exception monitoring and alerting. No limits._ 

#### Analytics

* [Google Analytics](https://www.google.co.uk/analytics/)
* [Go Squared](https://www.gosquared.com)

#### Client-side error tracking

* [Errorception](http://errorception.com/) - _Simple and painless way to find out about JavaScript errors, as they occur in your users' browsers. All you need to do is insert a script tag on your page, and you will start recording errors as they happen in real-time._
* [QBaka](https://qbaka.com/) - _Cloud-based frontend error monitoring and analytics for web services & mobile HTML5._
* [JSLogger](http://jslogger.com/) - _Log Javascript errors and events in the cloud._
* [Muscula](http://www.muscula.com/) - _Log your JavaScript errors, so you can fix them._
* [BugSense](https://www.bugsense.com/) - _Get actionable reports on the health of your Javascript apps & websites!_
* [ExceptionHub](http://www.exceptionhub.com/) - _Easy Setup, drop in code and start collecting errors._

### Social Media

Register appropriate usernames/pages on social media sites. Configure alerts for mentions, complaints and praise.

* [Twitter](https://twitter.com/)
* [Facebook](http://www.facebook.com/)

### Status Page

Externally hosted resource displaying real-time system availabilty, historical uptime, latency, past incidents.

* [StatusPage.io](https://www.statuspage.io/) - _The best way to create a status page for your app or website._

### Image Optimisation

* [Tools for image optimization](http://addyosmani.com/blog/image-optimization-tools/)

### User Authentication

* [LoginRadius](https://www.loginradius.com/)
* [Okta](https://www.okta.com/)

