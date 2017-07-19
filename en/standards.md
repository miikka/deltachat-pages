---
title: Standards used in Delta Chat
layout: default
---

# Standards used in Delta Chat

For everyone, who's technically interested, here are some of the standards Delta Chat is based on.

Tasks                            | Standards
---------------------------------|---------------------------------------------
Transport                        | IMAP v4 ([RFC 5301](https://tools.ietf.org/html/rfc3501)), SMTP ([RFC 5321](https://tools.ietf.org/html/rfc5321)) and Internet Message Format (IMF, [RFC 5322](https://tools.ietf.org/html/rfc5322))
Embedded media                   | MIME document series ([RFC 2045](https://tools.ietf.org/html/rfc2045), [RFC 2046](https://tools.ietf.org/html/rfc2046)), Content-Disposition Header ([RFC 2183](https://tools.ietf.org/html/rfc2183)), Multipart/Related ([RFC 2387](https://tools.ietf.org/html/rfc2387))
Push                             | IMAP IDLE ([RFC 2177](https://tools.ietf.org/html/rfc2177))
End-to-end encryption            | [Autocrypt Level 1](https://autocrypt.org/en/latest/level1.html), OpenPGP ([RFC 4880](https://tools.ietf.org/html/rfc4880)) and Security Multiparts for MIME ([RFC 1847](https://tools.ietf.org/html/rfc1847))
Configuration assistance         | [Autoconfigure](https://developer.mozilla.org/en-US/docs/Mozilla/Thunderbird/Autoconfiguration) and [Autodiscover](https://technet.microsoft.com/library/bb124251(v=exchg.150).aspx)
Messenger functions              | [Email-chat v0.9.0](https://delta.chat/en/spec)
Detect mailing list              | List-Id ([RFC 2919](https://tools.ietf.org/html/rfc2919))
Send and receive system messages | Multipart/Report Media Type ([RFC 6522](https://tools.ietf.org/html/rfc6522))
Return receipts                  | Message Disposition Notification (MDN, [RFC 8098](https://tools.ietf.org/html/rfc8098), [RFC 3503](https://tools.ietf.org/html/rfc3503))

Delta Chat itself is licensed under the GPL license.
If you want to know, whether a concrete feature is supported, a look into the [source code](https://github.com/deltachat) may help.