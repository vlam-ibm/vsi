---

copyright:
  years: 2017
lastupdated: "2017-10-24"

subcollection: virtual-servers

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:faq: data-hd-content-type='faq'}


# FAQs: Dedicated hosts and instances
{: #faqs-dedicated-hosts-and-instances}

## What is a dedicated host?
{:faq}

{{site.data.keyword.Bluemix}} dedicated hosts are physical servers committed to a group of users. Dedicated hosts offer virtual server provisioning capacity and maximum placement control.

## What are the benefits of using dedicated hosts over dedicated instances?
{:faq}

Both offerings are guaranteed single tenancy. Dedicated hosts provide the flexibility to specify on which host to provision dedicated host instances, as well as:
   * Control over which {{site.data.keyword.cloud}} data center the server is placed
   * Ability to manage your servers as workload requirements change; for example, migrate virtual servers between your dedicated hosts on the same POD

## Can I keep my existing dedicated instances or do I need to set up a dedicated host and dedicated host instances?
{:faq}

Yes, you can keep your existing dedicated instances.

## Can I interchange provisioning of dedicated instances (auto–assigned) and dedicated host instances?
{:faq}

No. Existing auto-assigned dedicated instances cannot be reprovisioned on dedicated hosts. If you require virtual server placement, you will need to provision them on dedicated hosts as dedicated host instances.

## What type of server, virtual or bare metal, supports the dedicated host offering?
{:faq}

The offering is supported on virtual servers; {{site.data.keyword.Bluemix_notm}} does have a bare metal offering. The differences between virtual hosts and bare metal servers are the time to provision and virtualization management.

## What is the provisioning lifecycle of a dedicated host?
{:faq}

Dedicated hosts are allocated to users when provisioned. They will persist to the account until it is reclaimed. Dedicated hosts are offered in only on-demand pricing, hourly or monthly, so when reclaimed, billing models will charge as either hourly or monthly {{site.data.keyword.BluSoftlayer_full}} offerings.

## How is the dedicated host offering billed?
{:faq}

You can purchase dedicated hosts on-demand with hourly or monthly billing. Hourly-only hosts allow only hourly instances to be provisioned; monthly-only hosts allow you to provision monthly *and* hourly instances. Pricing for dedicated hosts includes core, RAM, local SSD storage, and network port speeds. Premium operating systems, storage area network (SAN) storage, and software add-on prices and licensing are charged based on the instance deployed—hourly or monthly—on the dedicated host. The same pricing model as {{site.data.keyword.Bluemix_notm}} public and dedicated instances is followed for these items.

## I’m running an on-demand dedicated host; how am I billed?
{:faq}

You will be billed at the hourly or monthly on-demand rate for dedicated hosts. Dedicated host instances provisioned on dedicated hosts may incur instances charges as noted in the answer to **How is a dedicated host offering billed**.

## How is tenancy specified when provisioning dedicated hosts and dedicated host instances?
{:faq}

The default tenancy for dedicated instances is single tenant. You will have the option to provision dedicated instances on either a dedicated host (dedicated host instances) or an auto-assigned host (dedicated instances). Dedicated instances on auto-assigned hosts do not offer the same management level as those on a dedicated host.

## Can I mix and match different dedicated host instance configurations on my dedicated host?
{:faq}

Yes. You can provision different virtual server sizes on dedicated hosts within its capacity allotments.

## How do I know how many dedicated host instances I can run on each dedicated host?
{:faq}

Each dedicated host has a specific allotment of core, RAM, and local SSD storage. You will be able to view resource allocations on the host Allocations tab to know how many dedicated host instances are provisioned, current host capacity used, and what is available.

## What images can be provisioned on dedicated hosts?
{:faq}

You can provision {{site.data.keyword.Bluemix_notm}} virtual server stock images or import your own images as indicated in the third-party agreement.

## Is there a limit as to how many dedicated hosts can be allocated to a single account?
{:faq}

Yes, resource limitations are per account as defined for all {{site.data.keyword.BluSoftlayer_notm}} as a Service resources. You can have multiple orders per account but only two dedicated hosts per provisioning order.

## Can dedicated host deployments be oversubscribed?
{:faq}

No; you can only provision the listed capacity on dedicated hosts.
