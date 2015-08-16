---
title: York University / York Regional Police Ontario Mixup
related:
- porn
- hacker
- vuft
---

Someone at internic.net once screwed up the reverse lookup entries for
the University subnet (144.32). In fact they managed to overwrite the
entry by one for the York Regional Police in Ontario! This change
occurred on 25 January, and as our entries expired from the caches on
other domain name servers we found that some sites were refusing to
accept mail and FTP connections from the machines.

The original text was

> Network access to BIDS, NISS and some ftp servers continues to be
> restricted. This is due to the Internet authorities in the US losing
> the registration for the University of York, and with it, vital
> addressing information. The entry for NET-YORK has been allocated
> instead to York Regional Police, 17250 Yonge Street, Newmarket,
> Ontario; L3Y 4W5.
>
> We understand that the Internet Network Information Center (NIC) is
> attempting to recreate our original entries, but we do not know
> precisely when this will happen.
>
> Information provided on 2-FEB-1995 16:30 by jg

However, a whois query to internic.net reveals that NET-YORK still
(8/1996) points to York Regional Police, although NET-YORK2 points to
york.ac.uk.
