---

title: "Update to Recognize the IETF IPMC as the IETF Trust Successor"
abbrev: "IETFIPMC"
category: bcp
updates: 5378, 8714, 8721
docname: draft-deen-ietf-ipmc-update-latest

submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "General Area"
workgroup: gen
standalone: yes

keyword:
 - IETF IPR
 - IETF Trust
 - IETF IPMC

venue:
   group: "genarea"
   type: "Working Group"
   mail: ipr-wg@ietf.org
   arch: https://mailarchive.ietf.org/arch/browse/ipr-wg
   github: gitnnelg/draft-deen-ietf-ipmc-update
   latest: https://gitnnelg.github.io/draft-deen-ietf-ipmc-update/draft-deen-ietf-ipmc-update.html

author:
 -
    fullname: Glenn Deen
    organization: Comcast-NBCUniversal
    email: rgd.ietf@gmail.com


normative:
   RFC5378:
   RFC8714:
   RFC8721:
   RFC8729:
   RFC9280:
   RFC9920:

informative:
  IPMC-BYLAWS:
  title: "BY-LAWS OF IETF INTELLECTUAL PROPERTY MANAGEMENT COPRPORATION"
  target: https://www.ietf-ipm.org/administration/bylaws/
  date: 2025-12-10

  TRUST-TLP:
  title: "Corrected Legal Provisions Relating to IETF Documents"
  target: https://trustee.ietf.org/documents/trust-legal-provisions/
  date: 2015-03-25


--- abstract

This document updates IETF documents that reference the IETF Trust to include the Trust's successor, the IETF Intellectual Property Management Corporation.

Discussion of this draft is on the ipr-wg@ietf.org mailing list.

--- middle

# Introduction

The IETF Trust, a Virginia trust, was established in 2005 as the intellectual property rights (IPR) manager for the IETF. The IETF Trust has held and managed IPR, including those granted by authors of IETF Contributions and IETF Documents following the terms of BCP 78, currently specified in {{RFC5378}} and its predecessors.

The IETF Intellectual Property Management Corporation (IPMC), a Delaware not-for-profit corporation was established in December 2022 as the successor to the IETF Trust, replacing it and assuming all of its roles and responsibilities. Since its establishment the IETF IPMC has been undertaking the necessary steps to establish itself as a 501c3 non-profit, to prepare for and execute the transfer of all assets held by the IETF Trust, and to update where necessary agreements and IETF documents to complete the task of assuming the role as the replacement of the IETF Trust.

The IETF Trust has never held or been involved in patents and likewise, the IETF IPMC will continue not being involved with any patent related activity.

This document updates {{RFC5378}}, {{RFC8714}} and {{RFC8721}} to recognize that the IETF IPMC is now the proper custodian of all IETF-related intellectual property rights and successor in interest to the IETF Trust.

#  Updates

## References to the IETF Trust in IETF RFCs and BCPs

All references to “IETF Trust” in any IETF document, including RFCs, BCPs, Internet-Drafts, and other IETF publications, shall be read and interpreted as referring to the IETF Intellectual Property Management Corporation (IETF IPMC) as the successor entity.

The IETF IPMC has assumed all rights, responsibilities, and obligations previously held by or attributed to the IETF Trust in such documents.

## Websites and URLs

### IETF IPR

The IETF publishes information on intellectual property rights (IPR) at [IETF IPR](https://ietf.org/ipr) and more general information at the [IETF IPR Process](https://ietf.org/process/ipr) dealing with IETF IPR topics in general and including patents.

### IETF Trust

The IETF Trust, historically, has published information related to licensing, assets, finances and notices of actions and changes on [the Trust web site](https://trustee.ietf.org).  This web site shall be maintained in perpetuity as URLs to it appear in published documents and the Trust Legal Provisions (TLP) version 1.0-5.0 that were active at the time when a contribution was made, and the date of a RFC publication will continue to apply to those works even after subsequent transfer of those IPR assets to the IETF IPMC.   The existing URLs in the required copyright boilerplate and other sections of I-Ds and RFCs will continue to work correctly for users of those documents.

### IETF IPMC

The IETF IPMC, has established the [IETF IPMC Website](https://www.ietf-ipm.org) as its official corporate website which it will use to publish governance and operational information including bylaws and financial statements and legal notices, along with the updated IETF IPMC published Technical Legal Provisions (TLP 6.0) which provide licensing terms for I-Ds and RFCs.

Cross reference navigation links on the old IETF Trust and the new IETF IPMC websites shall be established to provide easy navigation between them to users.

## Updates to RFC5378

{{RFC5378}} has a number of cited URLs directing readers to the locations of various IPR related information.   The IETF Trust web site URLs shall be maintained to preserve the URLs to it found in RFC5378.  There is no need to update or modify existing references in I-Ds or RFCs.

Additionally, RFC5378 is hence updated to include the IPMC web site as the location IETF IPMC licensing information for assets, including required notices.

### IETF IPMC Technical Legal Provisions Relating to IETF Documents (TLP)

The IETF Trust published a series of documents commonly known as the "TLP" {{TRUST-TLP}}. Versions 1.0-5.0 of {{TRUST-TLP}} contain basic common licensing declarations and required boilerplates and notices in I-Ds and RFCs.  To maintain this common terminology, while recognizing that the IETF IPMC is not a trust, the next version shall be also known as the TLP 6.0, with the new formal name being the "IETF IPMC Technical Legal Provisions Relating to IETF Documents" which shall be published starting as IETF IPMC TLP version 6.0 to maintain version consistency with the IETF Trust's TLP 1.0-5.0.

TLP 6.0 is published by the IETF IPMC on its website.

## Use of IETF Trust and IETF IPMC in other IETF IPR Framework Documents

All references to the IETF Trust in {{RFC5378}} and related operational documents shall be read as referring to the IETF IPMC effective upon the transition.

Updated versions of required copyright notices in I-Ds and RFCs reflecting this change can be found in Section 6 of the TLP 6.0.

Note that no required retroactive changes of copyright notices in prior IETF documents are to be made.

While it is not necessary to update pre-IPMC copyright notices, it is correct and accurate to refer to the IETF IPMC as the holder of all the intellectual property rights and assets previously held by the IETF Trust, since these have all been moved to the IETF IPMC.

## RFC8721 Advice to the IPMC Directors on the IETF IPMC on Rights to be Granted in IETF Documents

{{RFC8721}} provides advice to the IETF Trustees of the IETF Trust on rights to be granted in IETF documents.  This advice is now directed to the IETF IPMC Board of Directors in the same capacity.

## Intellectual Property Rights Held by IETF Trust

The intellectual property rights held by the IETF Trust have been transferred to the IETF IPMC, as the successor to the IETF Trust.  Inquiries regarding licenses and other IPR topics should now be made to the IETF IPMC.

## RFC Streams

{{RFC8729}} defines a series of RFC Streams, the IETF, IAB, IRTF and Independent Stream, and {{RFC9280}} adds the Editorial Stream as the distinct publication streams of the RFC Series.    Mentions of the IETF Trust and intellectual property rights management in {{RFC8729}} and  {{RFC9920}} are updated to recognize the IETF IPMC as the successor and replacement to the IETF Trust as the party responsible for providing the same role of copyright holder and administrator for those RFC Streams.

Specifics for each RFC Series Stream were described in {{TRUST-TLP}} 5.0 section 8, with the exception of the Editorial Stream, which was not mentioned explicitly in TLP 5.0 due to its creation after the publication of TLP 5.0. The IETF IPMC is assuming the role of the IETF Trust as described in TLP 5.0 and additionally it is formally adding the Editorial Stream into TLP 6.0.

Additional details on the RFC Series Streams can be found in the IETF IPMC TLP version 6.0 published on the IPMC website.

## IETF Trustees and IPMC Directors

{{RFC8714}} defines the selection and recall processes for IETF Trustees, under which Trustees are directly selected by the designated selecting organizations (the IETF NomCom, the IESG, and the ISOC Board of Trustees) to serve as Trustees of the IETF Trust.

The process for selecting IETF IPMC Directors is structurally different but functionally equivalent. While IPMC Directors are not appointed directly by the selecting organizations, the outcome is the same: director selection authority is effectively exercised by the same {{RFC8714}}-designated bodies, and director terms track the same durations specified in {{RFC8714}} for IETF Trustees.

### Corporate Governance Context

The IETF IPMC is a Delaware nonstock corporation with no members. Because Delaware General Corporation Law (DGCL) does not provide for the appointment of directors by third-parties, such corporations typically operate with self‑perpetuating boards, meaning that directors are elected by the sitting board rather than by members or shareholders or third-parties. This governance model is expressly reflected in {{IPMC-BYLAWS}}.

### IPMC Director Selection Mechanism

The process for IPMC board composition is defined in {{IPMC-BYLAWS}} § 3.3, and operates as follows:

* Initial Board Formation (§ 3.3(a))

The initial directors of the IPMC were the IETF Trustees serving at the time of the IPMC’s incorporation. This ensured continuity of fiduciary responsibility and alignment between the Trust and the newly formed IPMC.

* Subsequent Director Selection (§ 3.3(b))

Upon expiration of an IPMC director’s term or their resignation, the sitting IPMC Board elects a successor director. However, the pool of eligible candidates is constrained:

* Each director seat is associated with a specific nominating organization (IETF NomCom, IESG, or ISOC Board of Trustees), consistent with {{RFC8714}}.
* When a term expires or a director resigns, the relevant nominating organization selects the individual to be nominated.
* That individual is then submitted to the IPMC Board, which is then required under the bylaws to formally elect the nominee as a director.

In practice, this means that while the legal act of election is performed by the IPMC Board (as required by Delaware law), the substantive selection authority rests with the RFC 8714-designated nominating organizations.

### Protection of Nominating Organization Rights

The rights of the nominating organizations are protected by {{IPMC-BYLAWS}} § 3.6. That provision restricts the Board’s ability to:

* Modify eligibility requirements for directors, or
* Alter or eliminate the rights of nominating organizations to nominate directors

unless such changes are approved by:

* A two‑thirds vote of all then‑serving directors, and the affirmative vote of any director representing a nominating organization that would be adversely affected by the change.

The practical effect of this safeguard is that no nominating organization can be disenfranchised or have its representation diluted without its own consent, expressed through its representative director’s affirmative vote. This creates a strong governance lock‑in consistent with both Delaware law and the community‑driven structure envisioned by {{RFC8714}} and is in fact a more stringent control than exists under the Trust Agreement, where the consent of an affected organization is not required.

### IPMC Director Recall

{{RFC8714}} also defines recall mechanisms for IETF Trustees appointed by each of the selecting organizations.

Within the IPMC governance framework, these {{RFC8714}} recall authorities are implemented through {{IPMC-BYLAWS}} § 3.3(c). Under that provision:

* Each nominating organization retains the authority to replace its designated representative on the IPMC Board of Directors.
* When a nominating organization exercises its recall or replacement authority, the IPMC Board is required under the bylaws to elect the replacement nominee.

As with director selection, the Board’s role is ministerial and legally required under Delaware corporate law, while the decision to recall or replace a director remains entirely with the relevant nominating organization, consistent with {{RFC8714}}.

## IETF IPMC recognition of IETF BCPs

{{IPMC-BYLAWS}} obligate the IETF IPMC to manage IETF assets for the benefit of the IETF. Therefore, the IETF IPMC looks to comply with IETF BCPs, as far as legally possible to guide its directors in carrying out that obligation.

# Security Considerations

This document has no security considerations.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments

The IETF Trustees and IETF Intellectual Property Management Corporation directors during the restructuring of the IETF Trust to the IETF IPMC were: 

- Kristin Berdan
- Glenn Deen
- Lars Eggert
- Joel Halpern
- Victor Kuarsingh
- John Levine
- Kathleen Moriarty
- Jon Peterson
- Wendy Seltzer
- Sean Turner
