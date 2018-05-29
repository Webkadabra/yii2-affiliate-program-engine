# yii2-affiliate-program-engine
A set of modules &amp; components for Yii2 application that provides system similar to PostAffiliate Pro

This is a private module - I still need to make some dough! Please, contact me at <devkadabra@gmail.com> to get access to private repo and start your own partner/affiliate program. 

Package contents:

* Module for partner's panel (e.g. main page of your Affiliate program, where people read rules, register and access partner's dashboard with promos, stats, commissions etc.)
* Module for admin/backend management of all things affiliate: manage affiliate partners, campaigns, promotions etc.
* Tracking component for your frontend - which only registers a JS script, like sometihng you would get with GA, and the rest of tracking activity is performed via JS and tracking pixels, and is loaded/requested fron/to your "Partners/Affiliates" website (so absolutely zero new SQL requests on your frontend)

Affiliate features:

* Standard campaigns, banners, and commonly-used affiliate/partner links like `http://website.com/?ref=getit` (Of course, all query parameters are customizable)
* Verified domains: allows partner to add a domain and verify website ownership to gain access to more features
* Many ways to track visitor form affiliate, besides using partner links (based on landing page, query parameters, *verified* partner domains, emails, UTM tags etc.)
