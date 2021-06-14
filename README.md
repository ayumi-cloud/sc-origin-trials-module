<h1 align="center">Summer CMS - Origin Trials Module</h1>
<p align="center">(Being heavily coded in private repos at the moment - we look forward to publity releasing a candidate release)</p>
  
<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/code.svg"> <img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/buttons/stars.svg" alt="stars"> <img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/buttons/php.svg"> <img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/laravel-badge.png" alt="laravel"> <img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/buttons/conduct.svg" alt="conduct"> <img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/buttons/docs.svg" alt="docs"></p>
  
<p align="center"><img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/cover.jpg"></p>


---------

  WARNING CURRENTLY BEING WRITTEN
  
---------


## Summer CMS Modules :eyes:

**Note: This is the origin trials module for Summer CMS, see here for the full list of [Summer CMS Modules](https://github.com/summer-cms/sc-main/blob/main/README.md#summer-cms-modules-).**

## Table of Contents 📑

- [Transparency](#transparency-)
- [Introduction](#intro-)
- [Goals](#goals-soccer)
- [Privacy as Default](#privacy-as-default-)
  - [General Data Protection Regulation (GDPR)](#general-data-protection-regulation-gdpr-)
  - [ePrivacy Regulation](#eprivacy-regulation-)
  - [California Consumer Privacy Act (CCPA)](#california-consumer-privacy-act-ccpa-)
  - [Strong Customer Authentication (SCA) ](#strong-customer-authentication-sca-)
  - [The Second Payment Services Directive (PSD2)](#the-second-payment-services-directive-psd2-)
  - [Federated Learning of Cohorts (FLoC)](#floc-)
  - [Cookies](#cookies-)
    - [SameParty Cookie Attribute](#sameparty-cookie-attribute-)
- [Vanilla Code](#vanilla-code-)
- [Naming Prefix](#naming-prefix-%EF%B8%8F)
- [Requirements](#requirements-)
- [Big data](#big-data-)
- [Citation](#citation-)
- [API's](#apis-gem)
- [Deprecations and removals](#deprecations-and-removals-)
- [Enhancements](#enhancements-)
- [Issues](#issues-)
- [Troubleshooting](#troubleshooting-)
    - [Something](#something-)
- [Reporting a Vulnerability](#reporting-a-vulnerability-)
- [Code of Conduct](#code-of-conduct-)
- [For Future](#for-future-)
- [Browser Support ](#browser-support-)
   - [Notes](#notes) 
- [Changelog](#changelog-)
- [Contributions, Feature Requests and Feedback](#contributions-feature-requests-and-feedback-)
	- [Testers](#testers-)
        - [With testing ](#with-testing-)
        - [Without testing](#without-testing-)
- [PSR](#psr-%EF%B8%8F)
- [PHP Coding Standards Fixer](#php-coding-standards-fixer-)
    - [Installation](#installation-)
    - [Usage](#usage-)
    - [Testing](#testing-%EF%B8%8F)
- [Semantic Versioning](#semantic-versioning-)
- [Copyright and License](#copyright-and-license-)

## Transparency 📢

This project is completely transparent and honest, before we started we contacted and discussed this project with the authors and admins of the October project. We have given the links to this repo to the authors and we continue to be transparent throughout the whole process! We feel it's important to state this and be open from day one! This repo contains one module, of many other modules all dedicated to different sections of the Summer CMS upgrade proposal. Instead of writing ideas and suggestions, we have taken a pro-active approach and are actively coding a fully working solution! The code is held on private repo's, due to the code being heavily developed and changed on a daily basis. We will release a stable test release to the admins and authors in private for feedback before releasing to the general public for beta-testing. This is a long-term project and we will continue to grow!

Over years we have coded and created well over a hundred pull requests (under various github accounts) which have been merged to the October core, we have never asked or recevived any money for any of the pull requests. We use the cms for professional purposes and therefore it is beneficial for our companies to have a professional working solution to give to our end-users and clients. In order for us to delivery a high quality product we made the discussion to update the cms with new and exciting features and modernize old and existing features, there are breaking change!

## Introduction ⭐

=== TO DO ===

## Goals :soccer:

This module aims to identify the following details:

- Browser

=== TO DO ===

(*) Note: The list above is not an extensive and complete list, it is intended to give a broad overview.

## Privacy as Default 👀

The Summer CMS takes privacy and user data seriously, we strongly believe in putting the user first and being fully transparent! Below lists some major components. However, for a full list see the legal module section here: https://github.com/summercms/sc-legal-module#goals-soccer

### General Data Protection Regulation (GDPR) 🔔

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/gdpr.jpg"></p>

The General Data Protection Regulation (GDPR) is one of the most wide-ranging pieces of legislation passed by the EU in recent memory. It was introduced to standardise data protection law across the single market and give people in a growing digital economy greater control over how their personal information is used. Summer CMS has a dedicated legal module to easily complie with current laws and sets the `opt-out` as the default and allows webmasters and users can then `opt-in`.

### ePrivacy Regulation 🔔

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/eprivacy.jpg"></p>

The ePrivacy Regulation will complement the GDPR’s general rules on personal data processing by providing specific rules governing electronic communications.

As such, the ePrivacy Regulation will take precedent over the GDPR in situations where both laws apply.

Note that, unlike the GDPR, the ePrivacy Regulation does not apply to just personal data. It also affects, for instance, B2B marketing.

Summer CMS has a dedicated legal module to easily complie with current laws and sets the `opt-out` as the default and allows webmasters and users can then `opt-in`.

### California Consumer Privacy Act (CCPA) 🔔

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/ccpa.jpg"></p>

The California Consumer Privacy Act (CCPA) is a law that allows any California consumer to demand to see all the information a company has saved on them, as well as a full list of all the third parties that data is shared with.

Businesses are subject to CCPA if they meet the requirements of having gross annual revenues of more than $25 million; buy, receive or sell the personal information of 50,000 or more consumers, households or devices in California; or derive 50% or more annual revenue from selling consumers' personal information.

The CCPA requires business privacy policies to include information on consumers' privacy rights and how to exercise them: the Right to Know, the Right to Delete, the Right to Opt-Out of Sale and the Right to Non-Discrimination.

Summer CMS has a dedicated legal module to easily complie with current laws and sets the `opt-out` as the default and allows webmasters and users can then `opt-in`.

### Strong Customer Authentication (SCA) 🔔

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/sca.png"></p>

Strong Customer Authentication (SCA) is a new European regulatory requirement to reduce fraud and make online payments more secure. To accept payments and meet SCA requirements, you need to build additional authentication into your checkout flow.

Summer CMS has a dedicated legal module to easily complie with current laws and customize secure settings and sca notices.

### The Second Payment Services Directive (PSD2) 🔔

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/psd2.jpg"></p>

The Payment Services Directive Two (PSD2) is a piece of legislation designed to force providers of payment services to improve customer authentication processes and to also bring in new regulation around third-party involvement.

Summer CMS has a dedicated legal module to easily complie with current laws and customize secure settings and sca notices.

### Federated Learning of Cohorts (FLoC) 🔔

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/floc.png"></p>

FLoC enables ad selection without sharing the browsing behaviour of individual users. A site should be able to declare that it does not want to be included in the user's list of sites for cohort calculation. Summer CMS puts it's users privacy first and so sets the `opt-out` as the default, webmasters and users can then `opt-in`. This also passes GDPR/ePrivacy laws.

FLoC is part of a suite intended to bring targeted ads into a privacy-preserving future. But the core design involves sharing new information with advertisers. Unsurprisingly, this also creates new privacy risks.

The first issue is fingerprinting. Browser fingerprinting is the practice of gathering many discrete pieces of information from a user’s browser to create a unique, stable identifier for that browser.

The second problem is less easily explained away: the technology will share new personal data with trackers who can already identify users. For FLoC to be useful to advertisers, a user’s cohort will necessarily reveal information about their behavior.

### Cookies 🔔

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/cookie.svg" width="250" height="250"></p>

Cookies in Summer CMS auto detect if the cms is being hosted from a secure connection and sets the following default for https connections:

Attribute | Default Value | Description
---|---|---
Prefix | `__Secure-` | Set to `__Secure-` automatically on `secure` connections and not `__Host-` to allow subdomains.
Expires | session: `1 day`, modules: `3 months` | The main cms session cookie is set to a `single day`, the cookies for modules are set longer at `3 months`. End-users can change the cookie expiry dates of all cookies using the legal module on the frontend. Allowing Summer CMS to be fully compliant with GDPR and ePrivacy laws.
Max-Age | lifetime: `120`, expire on close: `false` | This can be setup and changed using the config file `session.lifetime` value. 
HttpOnly | `true` | Forbids JavaScript from accessing the cookie. This can be setup and changed using the config file `session.http_only` value. 
Secure | `true` | Cookie is only sent to the server when a request is made with the `https:` scheme (except on localhost) and therefore is more resistent to `man-in-the-middle` attacks. This can be setup and changed using the config file `session.secure` value. 
SameSite | `Lax` | Controls whether a cookie is sent with cross-origin requests, providing some protection against cross-site request forgery attacks (CSRF). This can be setup and changed using the config file `session.same_site` value. 
SameParty | `none` | This is currently an Origin Trial in Chrome 89 and greater browsers only. Adding `SameParty` to a cookie that would otherwise be subject to the "[Lax](https://tools.ietf.org/html/draft-ietf-httpbis-rfc6265bis-05#section-5.3.7.1)" or "[Lax-allowing-unsafe](https://tools.ietf.org/html/draft-west-cookie-incrementalism-01#section-3.1.1)" enforcement modes of `SameSite` weakens security properties by expanding the set of contexts in which the cookie may be accessed. This can be setup and changed using the config file `session.same_party` value. 

#### SameParty Cookie Attribute 🍪

**A `SameParty` cookie is included in an HTTP request if the origins of the requested URL and all of the ancestor frames in the target browsing context belong to the same First-Party Set.** For example, a top-level navigation will always send `SameParty` cookies. Note that requests are treated the same regardless of the HTTP method (GET, POST, etc.), and the origin of the request initiator does not factor into whether the `SameParty` cookie should be allowed.

For example, suppose that owner.example owns a First-Party Set containing {member1.example, member2.example}. Then a `SameParty` cookie set by member1.example **would be sent** to https://member1.example in the following contexts:

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/same_party_table.png"></p>

## Vanilla Code 🍦

<p align="center"><img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/vanilla.jpg"></p>

Vanilla often refers to **pure** or **plain**. So in terms of programming languages, it means either without the use of **3rd party libraries** or without the use of **frameworks**.

The `core` files and `modules` in Summer CMS use `Laravel`, an open-source PHP web framework. However, all the styling, javascript and data interchange formats have been written using `vanilla` code. This makes upgrading the code **quick** and **simple** without the constraints of relying solely on a single library or framework! Plus reducing the code size and optimizing the performance by reducing the overheads of loading third-party libraries (such as jQuery as an example). Summer CMS treats all third-party libraries and frameworks as optional extras and developers are welcome to use any of them to enhance their websites and applications using Summer CMS.

The [framework module](https://github.com/summer-cms/sc-framework-module) adds bridges and interconnects different frameworks to Summer CMS with ease to give a customized experience for each framework!

## Naming Prefix ✒️

**Summer CMS uses the `sc-` naming prefix to advoid conflicts.**

## Requirements 🚩

This module has been optimized to work with php `7.4.x` and `8.x` versions - we recommend upgrading from any lower php version.

The origin trials module has also been optimized to work with twig `2.x` and `3.x` versions. No support for twig version one!

**A full list of requirements to install Summer CMS, can be found here: [Summer CMS Requirements](https://github.com/summer-cms/sc-main/blob/main/README.md#requirements-).**

## Citation 📚

<a href="https://zenodo.org/">
  <img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/buttons/citation.svg" />
</a>

If you use this origin trials module for your research, then kindly cite it. Click the above badge for more information regarding the complete citation for this origin trials module and the diffferent citation formats like: IEEE, APA, BibTeX, CSL, DataCite, Dublin Core, DCAT, JSON, JSON-LD, GeoJSON, MARCXML and Mendeley etc.

## API's 💎

Below are some of the API's the origin trials module uses (this is not a complete list):

- [Content Security Policy Level 3](https://www.w3.org/TR/CSP3/)
- [Content-Security-Policy-Report-Only](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy-Report-Only)
- [CSP: report-to](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/report-to)
- [CSP: trusted-types](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/trusted-types)
- [HTML Sanitizer API](https://wicg.github.io/sanitizer-api/)
- [Trusted Types API](https://w3c.github.io/webappsec-trusted-types/dist/spec/)

=== TO DO ===

## Deprecations and removals ⛔

- [Content Security Policy Level 1](https://www.w3.org/TR/CSP1/)
- [Content Security Policy Level 2](https://www.w3.org/TR/CSP2/)

The origin trials module has been optimized to work with CSP 3 and allow backwards compatibility with browsers supporting older CSP versions.

## Enhancements ⭐

- The origin trials module has been optimized to work a long side modern browsers that support the **back/forward cache** (bfcache) api. To learn more about bfcache, see these resources:

    [Exploring a back/forward cache for Chrome](https://developers.google.com/web/updates/2019/02/back-forward-cache)

## Issues 🔨

<img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed-raw/summer-cms/sc-origin-trials-module?style=plastic"> <img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/summer-cms/sc-origin-trials-module">

If you face any issue, you can create a new issue in the `Issues` tab and we will be glad to help you out!

## Troubleshooting 👿

### Something 💊

=== TO DO ===


## Reporting a Vulnerability 💥

We strive to make the code accessible to a wide audience of beginner and experienced users.

We welcome bug reports, false positive alert reports, evasions, usability issues, and suggestions for new detections. Submit these types of non-vulnerability related issues via Github.

Please include your installed version and the relevant portions of your audit log.

False negative or common bypasses should [create an issue](https://github.com/summer-cms/sc-origin-trials-module/issues/new) so they can be addressed.

Do this before submitting a vulnerability:

1) Verify that you have the latest version of Summer CMS.
2) Validate which Paranoia Level this bypass applies to. If it works in PL4, please send us an email.
3) If you detected anything that causes unexpected behavior of the engine via manipulation of existing provided rules, please send it by email.

We are happy to work with the community to provide CVE identifiers for any discovered security issues if requested.

If in doubt, feel free to reach out to us!

## Code of Conduct 💯

In order to ensure that the Summer CMS proposal community is welcoming to all, please review and abide by the [Code of Conduct](https://github.com/summer-cms/sc-origin-trials-module/blob/master/CODE_OF_CONDUCT.md).

## For Future 🔮

Shoutout to people willing to contribute to this project. Please take a look at the [projects board](https://github.com/summer-cms/sc-origin-trials-module/projects) for a list of things to be done.

## Browser Support ✅

The origin trials module has been tested in the following browsers:

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/chrome_48x48.png" alt="Chrome"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/firefox_48x48.png" alt="Firefox"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/safari_48x48.png" alt="Safari"><br>
      9+
    </td>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/edge_old_48x48.png" alt="Edge Legacy"><br>
      ✖ (1)
    </td>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/edge_48x48.png" alt="Edge"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/internet-explorer_9-11_48x48.png" alt="Internet Explorer"><br>
      ✖ (2)
    </td>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/opera_48x48.png" alt="Opera"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/samsung-internet_48x48.png" alt="Samsung"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/uc_48x48.png" alt="UC"><br>
      ✔
    </td>
    <td align="center">
      <img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/browser/vivaldi_48x48.png" alt="Vivaldi"><br>
      3+
    </td>
  </tr>
</table>

### Notes

(1) Microsoft announced on 17 August that Edge Legacy will have its life support switched off on 9 March 2021, Summer CMS will support Edge Chromium only.

(2) Internet Explorer version 1-11, Summer CMS will not support due to only supporting `Evergreen` brwosers.

For a full list of browser support with Summer CMS, see here: [Browser Support](https://github.com/summer-cms/sc-main/blob/main/docs/browser_support.md).

## Changelog 🏆

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributions, Feature Requests and Feedback ✨

We are actively inviting new contributors! To start, please read the [contribution guide](CONTRIBUTING.md).

This project is only possible thanks to the work of many dedicated volunteers. Everyone is encouraged to help in ways large and small. Here are a few ways you can help:

- Read the current content and help us fix any spelling mistakes or grammatical errors.
- Choose an existing [issue](https://github.com/summer-cms/sc-origin-trials-module/issues) on GitHub and submit a pull request to fix it.
- Open a new issue to report an opportunity for improvement.

If you find any bugs in the code or have any improvements in mind then feel free to generate a pull request.

**Note:** Please use Unit Testing and Coding Best Practices in order to have a valid pull request 😉

Patches and pull requests are encouraged. All code should follow the [PSR-1](https://www.php-fig.org/psr/psr-1/) and [PSR-2](https://www.php-fig.org/psr/psr-2/) style guidelines. **Please include unit tests whenever possible!**

### Testers 😺

Get the `composer.json` file from the admins and install.

### With testing 🔺

```
composer update
```

### Without testing 🔻

```
composer update --no-dev
```

### Gitpod 🐥

Summer CMS has experimental support for [Gitpod](https://www.gitpod.io/), a pre-configured development environment that runs in your browser. To use Gitpod, click the button below and sign in with GitHub. Gitpod also offers a browser add-on, though it is not required.

[![Edit with Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/summercms/sc-origin-trials-module)

## PSR ♻️

This origin trials module uses some PSR standards to be the most interoperable possible:

- [PSR-1](https://www.php-fig.org/psr/psr-1/) Basic Coding Standard.
- [PSR-2](https://www.php-fig.org/psr/psr-2/) Coding Style Guide.
- [PSR-6](https://www.php-fig.org/psr/psr-6/) Caching Interface.
- [PSR-7](https://www.php-fig.org/psr/psr-7/) Standard interfaces to represent http requests, responses and uris.
- [PSR-16](https://www.php-fig.org/psr/psr-16/) Common Interface for Caching Libraries.
- [PSR-17](https://www.php-fig.org/psr/psr-17/) Standard factories to create PSR-7 objects.
- [PSR-18](https://www.php-fig.org/psr/psr-18/) Standard interface to send a http request and return a response.

We also suggest using Cross-browser testing provided by BrowserStack (*) where a real-browser can't be used in-house.

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/browser-stack.png"></p>

## PHP Coding Standards Fixer ⭕

The PHP Coding Standards Fixer (PHP CS Fixer) tool fixes your code to follow standards; whether you want to follow PHP coding standards as defined in the PSR-1, PSR-2, etc., or other community driven ones like the Symfony one.

### Installation 🔹

The recommended way to install PHP CS Fixer is to use [Composer](https://getcomposer.org/download/) in a dedicated `composer.json` file in your project, for example in the
`tools/php-cs-fixer` directory:

```bash
$ mkdir --parents tools/php-cs-fixer
$ composer require --working-dir=tools/php-cs-fixer friendsofphp/php-cs-fixer
```

For more details and other installation methods, see: [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).

### Usage 🔸

Assuming you installed PHP CS Fixer as instructed above, you can run the following command to fix the files PHP files in the `src` directory:

```bash
$ tools/php-cs-fixer/vendor/bin/php-cs-fixer fix src
```

(*) Change the above command to the correct folder location.

### Testing ⚙️

The origin trials module uses the following:

- A [PHPUnit](https://phpunit.de) test suite.
- A coding style compliance test suite using [PHP CS Fixer](http://cs.sensiolabs.org/).
- A code analysis compliance test suite using [PHPStan](https://github.com/phpstan/phpstan).

To run the tests, run the following command from the project folder.

```bash
$ composer test
```

## Semantic Versioning 🎁

The Summer CMS and all modules use: [Semantic Versioning](https://semver.org/).

<p align="center"><img src="https://github.com/summercms/sc-origin-trials-module/blob/main/src/assets/images/semver.png"></p>

Semantic Versioning is a 3-component number in the format of `X.Y.Z` where:

- X stands for a major version.
- Y stands for a minor version.
- Z stands for a patch.

The goal of Semantic Versioning is to bring some sanity to the management of rapidly moving software release targets. As discussed above, 3 numbers i.e, `Major`, `Minor` and `Patch` are required to identify a software version. For example, if we take version `5.12.2`, then it has a `major` version of 5, a `minor` version of 12 and a `patch` version of 2.

Below are some scenarios when Summer CMS creates a new version release:

- Bump the value of X when breaking the existing API.
- Bump the value of Y when implementing new features in a backward-compatible way.
- Bump the value of Z when fixing bugs.

Pre-release metadata is identified by appending a hyphen to the end of the Semantic Versioning sequence. Thus a pre-release for version 1.0.0 could be `1.0.0-alpha.1`. Then if another build is needed, it would become `1.0.0-alpha.2` and so on. Note that names cannot contain leading zeros, but hyphens are allowed in names for pre-release identifiers.

Summer CMS uses the following pre-release metadata:

| Version     | Description        |
| ----------- | ------------------ |
| 3.3.x-aplha | The alpha phase of the release life cycle is the first phase of software testing. |
| 3.3.x-beta  | The beta phase follows after the alpha phase. A Beta phase generally begins when the software is feature complete but likely to contain a number of known or unknown bugs. |
| 3.3.x-rc    | A release candidate (RC), is a beta version with potential to becoming a stable product and is ready to release unless significant bugs emerge. |

## Copyright and License 📄

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Everyone is permitted to copy and distribute copies of Summer CMS, but changing and hard forking are not allowed.

[⬆ back to top](#table-of-contents-)

<p align="center"><img src="https://github.com/summer-cms/sc-origin-trials-module/blob/main/src/assets/images/luv.png"></p>
