---
category: Integrate
subGuides:
  - ab-tests/browser
  - ab-tests/server
  - ab-tests/apps
  - ab-tests/campaign
---
# A/B Testing - Experiments

This section contains guides that will help you run experiments (A/B tests) on your websites and apps using Piwik.

[A/B Testing](http://www.ab-tests.net/) is a plugin for Piwik that can be purchased on 
the [Piwik Marketplace](https://plugins.piwik.org/AbTesting). It is developed by [InnoCraft](https://www.innocraft.com), 
the makers of Piwik. If you want to learn more about this plugin we recommend to have a look at the developer guides, 
the [A/B Testing User Guide](https://piwik.org/docs/ab-testing/) and the [A/B Testing FAQs](https://piwik.org/faq/ab-testing/).

An A/B test lets you compare different versions and see which variation makes you more successful. 
A/B tests are also known as experiments or split tests. In an A/B test you show two or more different variations to your 
users (visitors) and the variation that performs better wins. When a user enters the experiment, a variation will be 
randomly chosen and the user will see this variation for all subsequent visits. Experimenting in this 
way lets you take data-driven decisions that maximise your success.

This section contains the following developer guides that will help you running experiments:

* **Websites (JavaScript)**: Run experiments on your website in the browser. Follow the [website implementation guide](/guides/ab-tests/browser) when you use the Piwik JavaScript Tracker on your website.  
* **Websites (Server-side)**: Run experiments server-side by using any A/B testing framework of your choice by following the [server side implementation guide](/guides/ab-tests/server) as long as you are also using the Piwik JavaScript tracker (works with [PHP](https://github.com/piwik/piwik-php-tracker), [Java](https://github.com/piwik/piwik-java-tracker), [C#](https://github.com/piwik/piwik-dotnet-tracker), [Python](https://github.com/piwik/piwik-python-tracker/tree/dev), ...).
* **Mobile, Desktop Apps & Games**: Run experiments using any A/B testing framework of your choice by following the [apps implementation guide](/guides/ab-tests/apps) when you are using a Piwik Tracker SDK (eg [Android SDK](https://github.com/piwik/piwik-sdk-android), [iOS SDK](https://github.com/piwik/piwik-sdk-ios), [C#](https://github.com/piwik/piwik-dotnet-tracker), [PHP](https://github.com/piwik/piwik-php-tracker), [Java](https://github.com/piwik/piwik-java-tracker), [Python](https://github.com/piwik/piwik-python-tracker/tree/dev)) to track your application.
* **Campaigns & Email Marketing**: Track how different campaigns affect the browsing behaviour on your website by following the [campaign implementation guide](/guides/ab-tests/campaign).
