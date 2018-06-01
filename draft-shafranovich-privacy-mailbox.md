---
title: Mailbox Name for Privacy Issues
docname: draft-shafranovich-privacy-mailbox-00
ipr: trust200902
cat: info
pi:
  sortrefs: 'yes'
  strict: 'yes'
  symrefs: 'yes'
  toc: 'yes'
author:
- ins: Y. Shafranovich
  name: Yakov Shafranovich
  organization: Nightwatch Cybersecurity
  email: yakov+ietf@nightwatchcybersecurity.com

--- abstract
Multiple Internet standards describe common mailbox names (mailbox @ domain)
to be used by organizations for operational and business functions.
This document defines a new mailbox called "privacy" that SHOULD be
used for contacting domain name owners about privacy issues.

--- middle

# Introduction

Multiple Internet standards describe common mailbox names (mailbox @ domain)
to be used by organizations for operational and business functions.
This document defines a new mailbox called "privacy" that SHOULD be
used for contacting domain name owners about privacy issues.

# Mailbox Definition

Several mailboxes are defined in section 4 of {{!RFC2142}} that
are intended to be used by outside parties to contact the organization that own
the domain name about specific operational issues.
This document updates section 4 of {{!RFC2142}} with an addition of a new
mailbox that SHOULD be used to contact the domain name owner regarding privacy
issues. Further information regarding privacy issues in Internet protocols
can be found in {{!RFC6973}}.

The new mailbox is defined as follows:
MAILBOX |AREA              |USAGE
--------|------------------|-----:
PRIVACY |Customer Relations|Privacy issues and concerns

Example of a new mailbox: privacy@example.com

# Security considerations

Organizations setting up this mailbox should be aware of potential for spam,
malware and other attacks via emails sent to this address.

# Terminology

In this document, the key words "MUST", "MUST NOT", "REQUIRED",
"SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY",
and "OPTIONAL" are to be interpreted as described in {{!RFC2119}}.

--- back
# Note to Readers

> **Note to the RFC Editor:**  Please remove this section prior
> to publication.

Development of this draft takes place on Github at https://github.com/nightwatchcyber/privacy-mailbox
