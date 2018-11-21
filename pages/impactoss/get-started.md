---
title: Get started with IMPACT OSS
meta_title:
lead: "Learn about your options to start using IMPACT OSS"
permalink: "/impactoss/get-started/"
header_image: header-pattern.jpg
header_title: Get started with IMPACT OSS
---

## Individual installation for every state or organisation

IMPACT OSS is designed to be **flexible and adaptable** to suit the specific needs and requirements states and organisations may have to coordinate and monitor the implementation of human rights and SDGs. It is **not a generic out-of-the-box service** and every state or organisations that wishes to use IMPACT OSS requires its own individual installation.

Each installation requires both the server and client applications to be **configured** and **installed** on appropriate web servers (as both components are only loosely coupled they can also be used independently and in combination with a custom server API or client UI).

In addition, some states or organisations may wish to further **customise** existing or **develop** new features.

---

# Managed installation

We, the Impact Open Source Software Trust, would love to help you with all the tasks needed to install and operate IMPACT OSS. You can read more about the services we offer on [Support for IMPACT OSS]({{ site.baseurl }}/impactoss/support) or just get in touch at [info@impactoss.org](mailto:info@impactoss.org).

---

# Independent installation

You can also use IMPACT OSS independently and for free but please be aware that some technical knowledge is required.

Please see our **[Installation Guide](https://install-guide.impactoss.org)** for detailed instructions on how to configure and install the [server](https://github.com/impactoss/impactoss-server) (Rails) and [client](https://github.com/impactoss/impactoss-client) (React/JavaScript) applications.

## Installation

Before you start, you will need to create your own copy of the source codes, selecting one of the three configuration options we offer. Alternatively to the

* `master` branches ([client](https://github.com/impactoss/impactoss-client), [server](https://github.com/impactoss/impactoss-server), [demo](https://demo.impactoss.org)) for the standard configuration,

you can also start with one of the configuration options provided by the [Permanent Mission of Singapore, Geneva](https://www.mfa.gov.sg/content/mfa/overseasmission/geneva.html) and in particular aimed at Small States:

* `demo-rights` branches ([client](https://github.com/impactoss/impactoss-client/tree/demo-rights), [server](https://github.com/impactoss/impactoss-server/tree/demo-rights), [demo](https://demo-rights.impactoss.org)): Human Rights implementation only, no SDGs
* `demo-sdgs` branches ([client](https://github.com/impactoss/impactoss-client/tree/demo-sdgs), [server](https://github.com/impactoss/impactoss-server/tree/demo-sdgs), [demo](https://demo-sdgs.impactoss.org)): Human Rights and SDG implementation

Regardless, the installation requires the following steps

1. Configure server
2. Install server components on suitable hosting providers
3. Configure client
4. Install client on suitable hosting provider

#### Documentation

We have developed the following resource to support the installation of IMPACT OSS:

**[Installation Guide](https://install-guide.impactoss.org)** (customise or contribute on [GitHub](https://github.com/impactoss/impactoss-installation-guide))

## Operation

To operate IMPACT OSS, the following is required or recommended:

* Hosting of client and server components
* Backing up server database and document storage
* Providing user support

In addition, it is recommended to

* Update client and server applications sporadically when new versions become available

#### Documentation

We have developed the following resources to support the operation of IMPACT OSS:

**[Admin Quick Start Guide](https://quick-start.impactoss.org)** (customise or contribute on [GitHub](https://github.com/impactoss/impactoss-admin-quick-start-guide))

**[User Manual](https://user-manual.impactoss.org)** (customise or contribute on [GitHub](https://github.com/impactoss/impactoss-user-manual))

## Customisation

You can further customise the appearance and behaviour of IMPACT OSS to suit your specific needs. For the server you will require knowledge of [Rails](https://rubyonrails.org) and for the client JavaScript, more specifically [React](https://reactjs.org).

We encourage users to make any significant enhancements available to all other users by contributing them back to the core open source project (also see [Get involved]({{site.baseurl}}/impactoss/get-involved/#become-an-open-source-contributor)).


---

If you need help with any of the above or custom development of new and existing features, please have a look at [Support for IMPACT OSS]({{ site.baseurl }}/impactoss/support) for the services we offer or just write to [info@impactoss.org](mailto:info@impactoss.org)
