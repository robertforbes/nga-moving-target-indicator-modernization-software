<img src="https://www.nga.mil/Partners/PublishingImages/720px-US-NationalGeospatialIntelligenceAgency-2008Seal.svg.png" width="200" style="margin: 20px;" />

# National Geospatial-Intelligence Agency (NGA)

## Moving Target Indicator (MTI) Software Modernization

## Request for Proposal (RFP) DRAFT

**April 6, 2018**

## Instructions

### Submission of Response

The National Geospatial-Intelligence Agency (NGA) is soliciting comment and questions on the Moving Target Indicator (MTI) Software Modernization DRAFT Request for Proposal (RFP). NGA seeks comments on all aspects of the acquisition strategy/approaches described in this notice, including feedback concerning the Statement of Objectives and overall approach. This DRAFT RFP is issued solely for information and planning purposes; it does not constitute a RFP or promise to issue a RFP in the future. This DRAFT RFP does not commit the Government to contract for any supply or service.

Responses may be [submitted publicly, as Issues on this GitHub repository](/ngageoint/nga-moving-target-indicator-modernization-software/issues), or they may be submitted via email. All comments that are submitted shall be sent on or before, but by no later than, **1700 Eastern Standard Time on Friday, May 4, 2018**.

If emailing comments, please include your full name, reference number **HM047618R0032** and title **"COMMENTS on NGA's Moving Target Indicator (MTI) Software Modernization,"** your organization's name, complete address, phone number and email address. Comments marked confidential or proprietary will be protected accordingly. Any response regarding this notice shall be submitted via email to [joseph.w.hicks@nga.mil](mailto:joseph.w.hicks@nga.mil).

## Background

NGA intends to retire its current traditional data center and replace it with a cloud-based computing environment. This necessitates migrating motion imagery data—MTI, Video, Wide Area Motion Imagery, and the associated operational capabilities—to the cloud.

## Contents

1. [Request for Proposals (RFP)](00_RFP.md)
2. Attachment 01: [Statement of Objectives (SOO)](01_SOO.md)
3. Attachment 02: [Quality Assurance Surveillance Plan (QASP)](02_QASP.md)
4. Attachment 03: [Pricing Template](03_Pricing_Template.md)
5. Attachment 04a: [Available AWS Environment Services & Tools](04a_AWS.md)
6. Attachment 04b: [MTI Backlog](04b_Backlog.md)
7. Attachment 05: [Clauses & Provisions](05_Clauses_and_Provisions.pdf)

## STANAGs

This RFP cites two “STANAGs,” or NATO STANdardization AGreements, that this work relies on: STANAG 4607 and STANAG 4676. These function like ISO or ANSI standards, but are instead promulgated by the North Atlantic Treaty Organization. There are [STANAGs on many topics](http://nso.nato.int/nso/nsdd/listpromulg.html), some technical, most not. The work here requires parsing both of these STANAG file formats.

### STANAG 4607
4607 defines the NATO [Ground Moving Target Indicator](https://en.wikipedia.org/wiki/Moving_target_indication) (GMTI) format—radar, basically. The NATO Standards Office publishes both [the standard itself](http://nso.nato.int/nso/zPublic/stanags/CURRENT/4607Eed03.pdf) and [an implementation guide](http://nso.nato.int/nso/zPublic/ap/aedp-7(2).pdf). MITRE publishes [an interesting history](https://www.mitre.org/sites/default/files/pdf/05_0164.pdf) of how the 4607 standard came to be. To get an idea of what it looks like to interact with GMTI [see this open source GMTI library](https://github.com/pentlandedge/s4607), [these open source GMTI utilities](https://github.com/pentlandedge/s4607_extra), or [this Leaflet-based GMTI viewer](http://www.hawkstream.net/), which includes sample data.

### STANAG 4676
4676 is the NATO Intelligence, Surveillance and Reconnaissance Tracking Standard, establishing the standard for tracking the location and spatial movement of mobile objects and associated motion imagry. [The standard](http://nso.nato.int/nso/zPublic/ap/AEDP-12(A)V1.pdf) defines an XML schema.


## Public domain

This project is in the [public domain](LICENSE).

