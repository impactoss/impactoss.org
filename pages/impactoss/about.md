---
title: About IMPACT OSS
hide_title: true
meta_title:
subheadline:
teaser: "IMPACT OSS is a software created to assist States with coordinating and monitoring implementation of human rights and the Sustainable Development Goals (SDGs), and also communicate implementation progress to the public"
permalink: "/impactoss/"
video: 262605219
video_source: vimeo
---

## About

**IMPACT OSS** is an _Open Source Software_ (OSS) for _Integrated Management and Planning of ACTions_ (IMPACT) that is maintained by the **Impact Open Source Software Trust** (see [About]({{site.baseurl}}/trust) to learn more about us).

IMPACT OSS is primarily designed to help **Governments' NMIRFs** (National Mechanism for Implementation, Reporting and Follow-up) and independent **NHRIs** (National Human Rights Institutions), but can also be used by **Human Rights NGOs** that wish to hold Governments accountable.

IMPACT OSS evolved from combining the development efforts for [Sadata](https://sadata-production.firebaseapp.com), Samoa's Database for its _National Mechanism for Reporting and Follow-up_ (NMRF), and the [New Zealand National Plan of Action](https://npa.hrc.co.nz) that is managed by the [New Zealand Human Rights Commission](https://hrc.co.nz) (see below for further credits).

IMPACT OSS consists of a **server application** (the 'API', [server source code](https://github.com/impactoss/impactoss-server) (Rails)) that manages the database, user authentication and automated emails, and a **client application** (the 'UI', [client source code ](https://github.com/impactoss/impactoss-client) (React/JavaScript)) that serves as the user interface for both the public and admin users.

All project code and related documentation are released under the [MIT Open Source License](https://github.com/impactoss/impactoss-client/blob/master/LICENSE.md) that allows any person or organisation to **use, modify and distribute the software free of charge** as long as the original copyright and license notice is included.

---

# Usage options

Join Samoa and New Zealand in using and improving IMPACT OSS. You can chose between  

<div class="row">
  <div class="large-6 columns">
    <h4>
      Independent installation
    </h4>
    <p>
      IMPACT OSS can be installed independently and for free by any person or organisation using suitable hosting providers. See <a title="Get started with IMPACT OSS" href="{{site.baseurl}}/impactoss/get-started/">Get started with IMPACT OSS</a> for further information and installation instructions.
    </p>
  </div>
  <div class="large-6 columns">
    <h4>
      Managed installation
    </h4>
    <p>
      Alternatively, you can engage the Trust's services for installing and hosting IMPACT OSS for you. In addition, we offer a variety of other services, including training, support and custom development (see <a title="Support for IMPACT OSS" href="{{site.baseurl}}/impactoss/support/">Support for IMPACT OSS</a> for an overview of services we offer).
    </p>
  </div>
</div>

**[Get started with IMPACT OSS]({{site.baseurl}}/impactoss/get-started/)**

---

![]({{site.urlimg}}features.png)

# Features

<div class="row">
  <div class="large-4 medium-6 columns">
    <h4>
      Manage and communicate implementation progress
    </h4>
    <p>
      At its heart, IMPACT OSS was designed to allow managing or documenting a country's implementation of human rights and the SDGs, as well as communicate implementation progress to the public.
    </p>
  </div>
  <div class="large-4 medium-6 columns">
    <h4>
      Powerful batch editing
    </h4>
    <p>
      Batch editing allows updating multiple items at once, including associating recommendations and actions with clusters and categories ('tagging'), as well as with each other.
    </p>
  </div>
  <div class="large-4 medium-6 columns">
    <h4>
      Import from CSV
    </h4>
    <p>
      The Import feature allows creating multiple items at once from a CSV text file.
    </p>
  </div>
</div>
<div class="row">
  <div class="large-4 medium-6 columns">
    <h4>
      Custom theming and configuration
    </h4>
    <p>
      IMPACT OSS was designed and developed to be highly customisable, including configuration of clusters and categories to match each country's specific needs, and theming of the UI appearance to match individual branding requirements.
    </p>
  </div>
  <div class="large-4 medium-6 columns">
    <h4>
      Optional: integration of SDGs
    </h4>
    <p>
      IMPACT OSS allows managing the 17 SDGs (Sustainable Development Goals) and the 169 internationally agreed SDG targets.
    </p>
  </div>
  <div class="large-4 medium-6 columns">
    <h4>
      Translation ready
    </h4>
    <p>
      IMPACT OSS is translation ready and can be easily translated into another language.
    </p>
  </div>
</div>

---
![]({{site.urlimg}}impactoss-demo.png)

#### Demo sites

# Try IMPACT OSS online

## Standard configuration

Please try out IMPACT OSS and all its features using our online demo. You can explore the admin functionality by signing in using `demo.manager@impactoss.org` (email) and `manager` (password). Please refer to our <strong><a target="_blank" href="https://user-manual.impactoss.org" title="User Manual">User Manual</a></strong> if you need help.

<a class="button medium radius" target="_blank" href="https://demo.impactoss.org">Launch demo</a>


## Other configurations for Small States

Further demo installations, provided by the [Permanent Mission of Singapore, Geneva](https://www.mfa.gov.sg/content/mfa/overseasmission/geneva.html) and in particular aimed at Small States, are available at:

<strong><a target="_blank" href="https://demo-rights.impactoss.org">demo-rights.impactoss.org</a></strong> (Human Rights implementation only, no SDGs)

<strong><a target="_blank" href="https://demo-sdgs.impactoss.org">demo-sdgs.impactoss.org</a></strong> (Human Rights and SDG implementation)

## Personal demo

We will happily give you an introduction and schedule a personal demo with you.

**Just get in touch at [contact@impactoss.org](mailto:contact@impactoss.org)**

---

#### Roadmap

# Where we are heading

We are committed to continue improving IMPACT OSS. In particular, we are currently planning the following improvements

## Integration of third party-developments

Ongoing developments by third parties that we are looking to integrate with IMPACT OSS.

* **Accessibility**: as part of the enhancements for its National Plan of Action, the NZ Human Rights Commission has provided funding to make IMPACT OSS accessible and compliant with <a href="https://www.w3.org/TR/WCAG20/" target="_blank" title="WCAG 2.0">WCAG 2.0</a>. Development is still ongoing and expected to be made available to all installations of IMPACT OSS in December 2018.

## Other planned enhancements

Enhancements we are planning but that subject to funding or third-party developments.

* **PDF exporting**: generate PDF reports
* **Integrate with other databases**: allow importing recommendations and observations from other databases such as OHCHR
* **Importing with tags**: allow importing recommendations and actions with category tags/clusters
* **Prominent recommendation clusters**: strengthen role of recommendation clusters
* **Automated clustering**: cluster recommendations automatically using methods such as machine learning
* **Improved indicators**: allow distinguishing progress from outcome indicators
* **Data visualisation component**: store and visualise indicator data
* **Improved filtering**: improve recommendation and action filtering, e.g. filtering by date ranges
* **Multi-language support**: introduce support for multiple languages
* **User invitation**: allow inviting new users from within the application

## Your ideas

If you would like to discuss or contribute to any of the above features or have ideas for any other features, please get in touch at [contact@impactoss.org](mailto:contact@impactoss.org) or learn more about how you can support us at [Get involved]({{ site.baseurl }}/get-involved/).

---

![]({{site.urlimg}}open.png)

# Free and open source

The source code for both server and client is open source and freely available under the MIT license. Anyone is therefore permitted to **use, modify and distribute the source code free of charge**.

However, we strongly encourage users to make any relevant enhancements available to all other users by contributing them back to the core open source project (see [Get involved]({{site.baseurl}}/impactoss/get-involved/) for details).

---

##  Credits

#### Design and Development

IMPACT OSS was designed and developed by human rights consultant Ashley Bowe and data visualisation agency [Unfold Data (formerly dumpark)](http://unfolddata.com), led by Edith Woischin and Timo Franz, with the help of human rights specialist Moana Eruera.

For full list of source code contributors, please see [contributors (client)](https://github.com/impactoss/impactoss-client/blob/master/CONTRIBUTORS.md) and [contributors (server)](https://github.com/impactoss/impactoss-server/blob/master/CONTRIBUTORS.md).

#### Funding

* Samoa's database [Sadata](https://sadata-production.firebaseapp.com) was made possible with funding provided by the [United Nations Development Program in Samoa](http://www.ws.undp.org/) and [New Zealand Aid](https://www.mfat.govt.nz/en/aid-and-development).
* [New Zealand's National Plan of Action](https://npa.hrc.co.nz) was funded by the [New Zealand Human Rights Commission](https://hrc.co.nz).
* IMPACT OSS documentation, customisation for Small States, and our video were funded by the [Permanent Mission of Singapore, Geneva](https://www.mfa.gov.sg/content/mfa/overseasmission/geneva.html) and our partner [Universal Rights Group](https://www.universal-rights.org/).
