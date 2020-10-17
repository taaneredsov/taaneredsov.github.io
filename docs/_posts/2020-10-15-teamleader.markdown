---
layout: post
title: "Case 2: Teamleader"
short_title: "Case 2"
date: 2020-10-15 11:12:00 +0200
category: our-work
author: Renaat
---

A client started using Teamleader, a great Belgian accounting &amp; CRM SaaS. The mother company however users another accounting system. The exports from Teamleader could not be imported into this accounting system. We developed a conversion script, where the accountant can transform the Teamleader exports to the correct import structure. Automation is added (Sidekiq), where every 7 days the invoices from Teamleader will be exported, delivered to a network location (SFTP), and imported by the accounting software. Check out Teamleader's API here: [Teamleader API][teamleader-api]{:target="_blank"}.

[teamleader-api]: https://developer.teamleader.eu/