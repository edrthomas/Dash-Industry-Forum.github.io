---
menu: "main"
title: "Guidelines"
weight: 3
---

# Introduction

DASH-IF publishes primarily three types of documents:

* [Completed Specifications and Guidelines](#completed-DASH-IF-Interoperability-Documents): The documents below are stable and have undergone a community review.
* [Documents for community review](#DASH-IF-Interoperability-Documents-for-Community-Review): These documents are technically solid, but public is asked for comments in order to improve details.
* [Position and White Papers](#DASH-IF-Position-and-White-Papers): These documents provide background and initial studies

# Completed DASH-IF Interoperability Documents

## Disclaimer

The documents below are stable and have undergone a community review. However, the DASH-IF welcomes feedback on these published documents, e.g, request for clarifications or bugs. For this purpose, please use the Github bug tracker cited along with the documents.

## DASH-IF Interoperability Points and Extensions

### Scope

The scope of the DASH-IF InterOperability Points (IOPs) defined in this document is to provide support for high-quality video distribution for over the top services using H.264/AVC and H.265/HEVC. Both live and on-demand services are supported. The specified features enable relevant use cases including on-demand, live services, ad insertion, trick modes, seek preview, content protection and subtitling. Extensions for multi-channel audio and next generation audio with different codecs as well as extensions to video different codecs and Ultra High Definition are defined.

Any identified bugs or missing features may be submitted through the DASH-IF issue tracker at https://github.com/Dash-Industry-Forum/DASH-IF-IOP/issues.

Note that version 4.3 is published as an add on to v4.2, but with the next version it is expected that a either a multipart version or a restructured version will be generated, with a major editorial updates. The new version is expected to be available by spring of 2020.

### Latest Version

* [Guidelines for Implementation: DASH-IF Interoperability Points V4.3: On-Demand and Mixed Services, HDR Dynamic Metadata and other Improvements](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v4.3.pdf) | ([Bugtracker](https://github.com/Dash-Industry-Forum/DASH-IF-IOP/issues)) | ([diff to v4.2](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v4.3-diff-v4.2.pdf)) | [License declarations](https://dashif.org/ipr-declarations/)

### Agreed Additions for Next Version

This clause lists a set of agreed additions that will be added to the next revision of the IOP Guidelines. They are typically documented as "Change Requests" documenting only the difference from the previous versions.

* [Low-Latency Modes for DASH](https://dash-industry-forum.github.io/docs/CR-Low-Latency-Live-r8.pdf) | ([Bugtracker](https://github.com/Dash-Industry-Forum/Live/issues))


### Previous Versions

* [Guidelines for Implementation: DASH-IF Interoperability Points V4.2: Multiple Clarifications and Bug fixes](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v4.2-clean.pdf) | ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/DASH-IF-IOP)) | ([diff to v4.1](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v4.2-diff-4.1.pdf)) | ([Online version](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v4.2-clean.htm))
* [Guidelines for Implementation: DASH-IF Interoperability Points V4.1: Robust Live, Seek Preview, Content Annotation, New Media Codecs and other extensions](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v4.1-clean.pdf) | [License declarations](https://dashif.org/ipr-declarations/)
* [Guidelines for Implementation: DASH-IF Interoperability Points V4.0: UHD Video and other extensions](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v4.0-clean.pdf) | ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/DASH-IF-IOP)) | ([diff to v3.3](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v4.0-diff-3.3.pdf)) | [License declarations](https://dashif.org/ipr-declarations/)
* [Guidelines for Implementation: DASH-IF Interoperability Points V3.3: Alignment with MPEG-DASH, Guidelines on keys and other corrections](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v3.3.pdf)| ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/DASH-IF-IOP)) | ([diff to v3.2](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v3.3-diff-v3.2.pdf))
* [Guidelines for Implementation: DASH-IF Interoperability Points V3.2: Addition of Adaptation Set Switching, HTTPS Guidelines, Key Rotation and MPEG-H Audio](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v3.2.pdf)| ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/DASH-IF-IOP)) | ([diff to v3.1](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v3.2-diff-3.1.pdf))
* [Guidelines for Implementation: DASH-IF Interoperability Points V3.1: Addition of CEA608/708, IMSC1, AC-4](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v3.1.pdf) | ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/DASH-IF-IOP))
* [Guidelines for Implementation: DASH-AVC/264 Interoperability Points V3.0: DRM updates, Improved Live, Ad Insertion, Events, HEVC support, Trick Modes, CEA608/708](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-v3.0.pdf) | ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/DASH-IF-IOP)) | [License declarations](https://dashif.org/ipr-declarations/)
* [Guidelines for Implementation: DASH-AVC/264 Interoperability Points V2.0: HD and Multi-Channel Audio Extensions](https://dash-industry-forum.github.io/docs/DASH-AVC-264-v2.00-hd-mca.pdf) | ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/DASH-IF-IOP))
* [Guidelines for Implementation: DASH-AVC/264 Interoperability Points V1.0](https://dash-industry-forum.github.io/docs/DASH-AVC-264-base-v1.03.pdf) | ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/DASH-IF-IOP)) | [License declarations](https://dashif.org/ipr-declarations/)

## DASH-IF Content Protection Information Exchange Format

### Scope

The scope of this document is to define a Content Protection Information Exchange Format (CPIX). The CPIX document contains keys and DRM information used for encrypting and protecting content, and can be used for exchanging this information among entities needing it in many possibly different workflows for preparing, for example DASH content or HLS content. The CPIX document itself can be encrypted, signed and authenticated so that its receivers can be sure that its confidentiality, source and integrity are also protected.

### Latest Version

DASH-IF Implementation Guidelines v2.2: [Content Protection Information Exchange Format (CPIX)](https://dash-industry-forum.github.io/docs/CPIX2.2/Cpix.html) | ([PDF](https://dash-industry-forum.github.io/docs/CPIX2.2/Cpix.pdf)) | ([XSD](https://dash-industry-forum.github.io/docs/CPIX2.2/XSD.zip)) | ([Bugtracker](https://github.com/Dash-Industry-Forum/CPIX/issues)) | ([Test vectors](https://github.com/Dash-Industry-Forum/cpix-test-vectors))

The document provides the following extensions to v2.1:

* Bug fixes on the HLS signalization support

### Previous Versions

* DASH-IF Implementation Guidelines v2.1: [Content Protection Information Exchange Format (CPIX)](https://dash-industry-forum.github.io/docs/CPIX2.1/HTML/Index.html) | ([PDF](https://dash-industry-forum.github.io/docs/CPIX2.1/PDF/Index.pdf)) | ([XSD](https://dash-industry-forum.github.io/docs/CPIX2.1/XSD/cpix.zip)) | ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/CPIX))
* DASH-IF Implementation Guidelines v2.0: [Content Protection Information
  Exchange Format (CPIX)](https://dash-industry-forum.github.io/docs/DASH-IF-CPIX-v2-0.pdf)| ([XML](https://dash-industry-forum.github.io/docs/Schema-Examples-v2.01.zip))| ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/CPIX))
* DASH-IF Implementation Guidelines v1.0: [Content Protection Information
  Exchange Format (CPIX)](https://dash-industry-forum.github.io/docs/DASH-IF-CPIX-v1.0.pdf)| ([XML](https://dash-industry-forum.github.io/docs/DASH-IF-CPIX-v1.0.zip))| ([Bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/CPIX))

## Guidelines for Implementation: DASH-IF Interoperability Point for ATSC 3.0

### Scope

The scope of this document is to provide a DASH interoperability point that is based on DASH-IF-IOPs and provides extensions to address use cases and requirements of ATSC 3.0.

Comments and bugs may be submitted through the [public github repository](https://gitreports.com/issue/Dash-Industry-Forum/ATSC).

### Latest Version

Version 1.1: Guidelines for Implementation: DASH-IF Interoperability Point for ATSC 3.0 ([pdf](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-for-ATSC3-0-v1.1.pdf) | [diff to v1.0](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-for-ATSC3-0-v1.1-diff-v1.0.pdf))

This updated version adds the following aspects:

* Update of references to refer to the latest correct versions
* Clarification on track selection in clause 3.3 and addition of a new clause 2.7.5
* Addition of a placeholder for a non-real time profile in clause 1.3
* Updates to the ROUTE protocol constraints when used with $TIME$ in clause 2.2
* Clarification on the usage of @r=-1 with the Segment timeline in clause 3.1.
* Reference to DASH-IF IOP for joining, initial buffering and playout in clause 4.
* Addition of High Dynamic Range (HDR) video in clause 3.3.
* Clarification on ATSC events and DASH events in clause 6.3
* Update to xlink behavior in clause 5.1
* Miscellaneous editorial updates

### Previous Versions

* [Version 1.0: Guidelines for Implementation: DASH-IF Interoperability Point for ATSC 3.0](https://dash-industry-forum.github.io/docs/DASH-IF-IOP-for-ATSC3-0-v1.0.pdf) | [License declarations](https://dashif.org/ipr-declarations/)

## Guidelines for Implementation: DASH-IF SAND Interoperability

### Scope

The scope of this document is to address interoperability aspects and deployment guidelines for Server and Network Assisted DASH (SAND). More specifically, the following aspects of SAND are covered:
•	Modes defining subsets of SAND messages and mandatory SAND protocols to use for specific deployment environments
•	Capability exchange procedures for DASH clients and DANEs
•	Security guidelines for SAND messages delivery
•	Procedures on DANE discovery for SAND

Comments and bugs may be submitted through the [public github repository](https://gitreports.com/issue/Dash-Industry-Forum/SAND)

### Latest Version

Guidelines for Implementation: DASH-IF SAND Interoperability Version 1.0 ([pdf](https://dash-industry-forum.github.io/docs/DASH-IF-SAND-IOP-v1.0.pdf)) | [License declarations](https://dashif.org/ipr-declarations/)

## DASH-IF Implementation Guidelines: Token-based Access Control for DASH (TAC)

### Scope

The scope of this document is to define a token-based access control mechanism and to enable the signaling of Authentication and Authorization (AA) protocols for DASH-based streaming. An Access Token is a proof that a DASH client or user of the client have been successfully authenticated and authorized in some pre-determined AA Systems to access a particular DASH resource, e.g. DASH segments or MPDs.
This document defines an Access Token format for accessing DASH resources and its transport between a DASH client and a server, hence ensuring interoperability between content providers and content delivery networks. The document focuses on the signaling and exchange mechanisms to facilitate Access Token-protected requests for the delivery of MPDs, licenses, keys and segments. This document can be used in addition to the general DASH-IF Interoperability Points.

Comments and bugs may be submitted through the [public github repository](https://gitreports.com/issue/Dash-Industry-Forum/TAC)

### Latest Version

[DASH-IF Implementation Guidelines: Token-based Access Control for DASH (TAC)] (https://dash-industry-forum.github.io/docs/DASH-TAC-v1.0.htm) ([pdf](https://dash-industry-forum.github.io/docs/DASH-TAC-v1.0.pdf)) | [License declarations](https://dashif.org/ipr-declarations/)

## DASH-IF Technical Specification: Live Media Ingest

### Scope

This document presents the DASH-IF Live Media Ingest Protocol Specification. Two protocol interfaces are defined. The first, interface 1, CMAF ingest, is based on fragmented MPEG-4 as defined in the common media application track format (CMAF). The second interface is based on MPEG DASH and HLS as defined by ISO SC29 WG 11 and IETF. Both Interfaces use the HTTP POST Method to transmit media objects from the ingest source to the receiving entity. Examples of live streaming workflows using these protocol interfaces are also presented. The protocol interfaces also support carriage of timed metadata and timed text. Guidelines for redundancy and failover are also included.

### Latest Version

[DASH-IF Live Media Ingest Protocol v1.0] (https://dashif-documents.azurewebsites.net/Ingest/master/DASH-IF-Ingest.html) ([pdf](https://dashif-documents.azurewebsites.net/Ingest/master/DASH-IF-Ingest.pdf)) | [License declarations](https://dashif.org/ipr-declarations/)

### Comments and Bugs

Comments may be submitted through the [github](https://github.com/Dash-Industry-Forum/Ingest/issues) or [public bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/Ingest)


## DASH-IF Test cases and Vectors

* Guidelines for Implementation: [Test cases and Vectors V1.0](https://testassets.dashif.org) | ([Bugtracker](https://github.com/Dash-Industry-Forum/Test-Cases/issues))

# DASH-IF Interoperability Documents for Community Review

## General

Community Review documents are published on the DASH-IF website in order to
get feedback from the industry on tools and features that are documented for
improved interoperability. For each of the documents, comments may be
submitted on the technologies itself, on specific features, etc. These
documents are only published temporarily for community review and will be
replaced by a full version after the commenting period has closed and the
comments have been addressed.

## Next Generation Audio Alignment with ATSC3.0

* The change request against IOP v4.3 for Community Review is accessible 
  [here (pdf)](https://dash-industry-forum.github.io/docs/NGA-Combined-CR-atsc_alignment_v6.pdf)
* AC-4 and MPEG-H have diverged over time from the specifications in the DASH-IF spec for ATSC3.0. This change request proposes the corresponding alignment, specifically:
  * For MPEG-H: This document proposes an update to the main DASH-IF IOP such that it aligns with the IOP for ATSC 3.0. 
  * For AC-4: This document proposes an update that aligns with ATSC 3.0 IOP, and includes signalling for the advanced use cases enabled by those services.
  * For DTS: Updates to general sections in include DTS-UHD
* Community review is open until June 15th, 2020. Addition to IOP is expected by early Q3/2020.
* Comments may be submitted through the [github](https://github.com/Dash-Industry-Forum/Audio/issues/new?labels=community-review).

## SPEKE-CPIX alignment

* A new version 2.3 of the Content Protection Information Exchange Format (CPIX) for Community Review is accessible [here (html)](https://dashif-documents.azurewebsites.net/Cpix/community-review/Cpix.html) [(pdf)](https://dashif-documents.azurewebsites.net/Cpix/community-review/Cpix.pdf) [(zip)](https://dashif-documents.azurewebsites.net/Cpix/community-review/Cpix.zip).
* Reason for Updates
  * CPIX 2.0 was published in September 2016. In November 2017, AWS Elemental released the first version of SPEKE, which is both a CPIX 2.0 profile, an API specification to transport CPIX documents and a set of deployment guidelines (for Content Key Encryption) – working with both on-premises equipment and cloud environments (AWS). The SPEKE specification also extends CPIX by introducing missing elements for MSS and HLS, using the ‘speke’ custom namespace (urn:aws:amazon:com:speke). 
  * While the SPEKE approach has worked well and allowed to create a unified ecosystem with 18 partners leveraging CPIX documents through SPEKE for DASH/HLS/MSS with multiple DRMs, it has also shown its limits, as SPEKE hasn’t followed the evolutions of CPIX which has now reached version 2.2. In the end, SPEKE is generating ecosystem fragmentation, whereas it was designed to facilitate interoperability around CPIX. It’s time to fix this situation and to allow implementers to benefit from all CPIX and SPEKE great features at the same time.
* Summary of changes: This update aims to align SPEKE and CPIX on the short term and to facilitate coordinated evolutions on the long term.
  * Clarification on the ContentKey/explicitIV element encoding
  * Addition of the ContentKey/commonEncryptionScheme element giving the CENC protection scheme used with the content key.
  * Addition of a section on using the same content key with different encryption schemes
  * Addition of a CPIX/version element 
  * Correction of XSD errors
  * Corrections of typos and broken references

* Community review is open until June 15th, 2020. Final publication is expected by Q2/2020.
* Comments may be submitted through the [github](https://github.com/Dash-Industry-Forum/CPIX/issues/new?labels=community-review). 

## Ad Insertion in DASH

* The change request against IOP v4.3 for Community Review is accessible 
  [here (pdf)](https://dash-industry-forum.github.io/docs/CR-Ad-Insertion-r5.pdf)
* Ad Insertion is considered as one of the most important aspects in online video distribution. Also with the development of CMAF, some additional aspects are relevant, such as consistent development of Ad content, content insertion into CMAF live content, etc. This document addresses latest development in the context of Ad Insertion and maps this to DASH, among others 
  * Description of most relevant use cases
  * Ad Insertion architecture
  * Definition of main content requirements and recommendations
  * Definition of ad content requirements and recommendations
  * Definition of combined main and ad content
  * Ad specific metadata
  * Ad tracking
* Community review is open until May 15th, 2020. Addition to IOP is expected by Q2/2020.
* Comments may be submitted through the [github](https://github.com/Dash-Industry-Forum/AdInsertion/issues/new?labels=community-review). 

## Updated Timing Model for v5

* The change request against IOP v4.3 for Community Review is accessible 
  [here (pdf)](https://dashif-documents.azurewebsites.net/Guidelines-TimingModel/master/Guidelines-TimingModel.pdf) and [here (html)]( https://dashif-documents.azurewebsites.net/Guidelines-TimingModel/master/Guidelines-TimingModel.html)
* The purpose of this chapter is to give a holistic overview of DASH presentation timing and related segment addressing. It is not intended to provide details of the timing model and all possible uses of the attributes in MPEG-DASH. In order to achieve higher interoperability, DASH-IF’s Implementation Guidelines allow considerably limited options than the ones provided by MPEG-DASH, constraining services to a specific set of reasonably flexible behaviors that are highly interoperable with modern client platforms. This chapter covers the timing model and related segment addressing schemes for these common use-cases.
* Please note: this Community Review is only limited to Chapter 5 of the Interoperability Guidelines, which includes the revised Timing model constraints and other interoperability constraints.  Community Review for the other portions of the Interoperability Guidelines will be available at a future time.
* Community review is open until November 30th, 2019. Addition to IOP is expected by Q1/2020.
* Comments may be submitted through the [github](https://github.com/Dash-Industry-Forum/Guidelines-TimingModel/issues/new?labels=community-review).


## Content Protection and Security

* The change request against IOP v4.3 for Community Review is accessible
  [html](https://dashif-documents.azurewebsites.net/Guidelines-Security/master/Guidelines-Security.html) and [pdf](https://dashif-documents.azurewebsites.net/Guidelines-Security/master/Guidelines-Security.pdf)
* Scope, Updates and Changes
  * This document is an update to the DASH-IF IOP Guidelines version 4.3. The scope remains the same, giving guidelines for interoperable behaviors of clients in front of well formed encrypted content. This means:
  * Updated encrypted content constraints for supporting CMAF. This includes the addition of the cbcs scheme support and recommendation for encrypting content when available both encrypted with cbcs and cenc schemes. Note that compared to DASH-IF IOP 4.3, there are no changes in the recommendations for using default_KID and pssh elements.
  * Added discussions on compliance and robustness rules and their impact on the choices of the DRM client to instantiate.
  * Added discussions on compliance and robustness rules and their impact on the choices of the DRM client to instantiate.
  * Clarified periodic reauthorization mechanisms, limited now the only Period change possibility. As a consequence, key hierarchy is moved in a different section as this is used for supporting different use cases.
  * Clarified the client reference architecture which is an MSE/EME type of player, more precisely connecting between the DASH/DASH-IF/CMAF content format specifications and W3C EME.
  * Introduces the Interoperable license request model that describes how players take content and consume it in ways that make sense on a platform that supports EME. From the Platform capabilities discovery and DRM selection to the license request protocol, this optional request model allows a player to obtain authorization tokens that can be used for retrieving licenses and content keys from a license server for rendering content. Any processing step in the proposed model can be redefined by the application logic.
  * Introduces DASH-IF XML schema where two elements are defined for supporting the license request model. These elements are namely the laurl (license acquisition server URL) and authzurl (Authorization server URL).
* Community review is open until March 31st, 2020. Addition to IOP is expected by Q2/2020.
* Comments may be submitted through the [github](https://github.com/Dash-Industry-Forum/Guidelines-Security/issues/new?labels=community-review).

## DASH Player’s Application Events and Timed Metadata Processing Models and APIs 

* The change request against IOP v4.3 for Community Review is accessible
  [here](https://dashif-documents.azurewebsites.net/Events/master/event.html) and a [pdf version](https://github.com/Dash-Industry-Forum/Events/blob/master/DASH%20Event%20Metadata%20API%20ver%208.pdf).
* For the proper usage of Events and Timed Metadata distributed in DASH Media Presentations, APIs pertaining to subscription and notification delivery are beneficially defined between the DASH client and the application consuming the Events. This document adds a client processing model for Events.
* Community review is open until August 31st, 2019. Addition to IOP is expected by Q1/2020.
* Comments may be submitted through the [github](https://github.com/Dash-Industry-Forum/Events/issues/new?labels=community-review) adding label "Community-Review" or [public bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/Events)

## WebIDL DASH Event Metadata API 

* The change request against IOP v4.3 for Community Review is accessible
  [here](https://dash-industry-forum.github.io/docs/Event API-WebIDL-r1.htm) and a [pdf version](https://dash-industry-forum.github.io/docs/Event API-WebIDL-CR.pdf).
* This document specifies an API that a user agent or DASH client can expose for application access to DASH events. This builds upon Media Source Extensions. The API correspond to partial interfaces with respect to the DASHEvent event target. It is meant to cover both in-band ('emsg') and MPD-carriage of events, as well as sparse timed metadata tracks.
* Community review is open until August 31st, 2019. Addition to IOP is expected by Q1/2020.
* Comments may be submitted through the [github](https://github.com/Dash-Industry-Forum/Events/issues/new?labels=community-review) adding label "Community-Review" or [public bugtracker](https://gitreports.com/issue/Dash-Industry-Forum/Events)

# DASH-IF Position and White Papers

* [DASH-IF position Paper: DASH-IF Position Paper: Server and Network
  Assisted DASH (SAND)](https://dash-industry-forum.github.io/docs/SAND-Whitepaper-Dec13-final.pdf) (500k PDF)
* [DASH-IF position Paper: Proposed QoE Media Metrics standardization for
  segmented media playback](https://dash-industry-forum.github.io/docs/ProposedMediaMetricsforSegmentedMediaDelivery-r12.pdf) (1M PDF)
* [DASH-IF/DVB Report on Low-Latency Live Service with DASH](https://dash-industry-forum.github.io/docs/Report%20on%20Low%20Latency%20DASH.pdf) (2M PDF)
* [DASH-AVC/264: A Baseline Implementation for MPEG-DASH Press Conference
  Material](https://dash-industry-forum.github.io/docs/DASH264-v1.5.pdf) (600k PDF)
* [DASH-AVC/264: A Baseline Implementation for MPEG-DASH Press Conference
  (Streaming recording)](https://meetings.webex.com/collabs/files/playRecording?encryptedDocID=0_29A910EB09C0BAEABD833A0CEE1CE0290D4477CBA394F385C9F76F5039B186DFC9A6CA6A732232122D7A07D19C5C921D_06C635CE7312194B5999E0695FBFC56E12BE2991)
* [Survey of European Broadcasters on MPEG-DASH](https://dash-industry-forum.github.io/docs/Survey-of-the-European-Broadcasters-on-MPEG-DASH-Whitepaper-V2.1.pdf)
* [Reinventing multimedia delivery with MPEG-DASH](http://spie.org/x648.html?product_id=897211), SPIE Applications of
  Digital Image Processing XXXIV, Sept 2011.
  
# ISO Publicly Available Specifications

* [MPEG-DASH 2nd Edition Specification (ISO/IEC 23009-1:2014)](http://standards.iso.org/ittf/PubliclyAvailableStandards/c065274_ISO_IEC_23009-1_2014.zip)
  * [Summary of new features](https://dash-industry-forum.github.io/docs/WhatsnewInMPEG-DASH2ndEdition.pdf)
  
* [MPEG-DASH 4th Edition Specification (ISO/IEC 23009-1:2020)](http://standards.iso.org/ittf/PubliclyAvailableStandards)
* T. Stockhammer: “[Dynamic Adaptive Streaming over HTTP-Design Priciples
  and Standards](http://www.w3.org/2010/11/web-and-tv/papers/webtv2_submission_64.pdf)” In: MMSys ’11: Proceedings of the second annual ACM conference on Multimedia systems New York, NY, USA: ACM Press , Feb 2011,S. 133-144.

