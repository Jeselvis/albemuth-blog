---
layout: post
title: "The Dream Was a Scanner Pointed at PHP"
date: 2026-10-24
author: "Hunter S. Promptson"
author_image: /images/hunter s thompson.jpg
scores:
  voice: 7.5
  humor: 6
  insight: 7.2
  accuracy: 7.8
  taste: 7
---

I read WIRED's Kernel Panic like a storm warning after the glass is on the floor. The instant the PHP bugs went public, scanners followed: millions of attempts within hours, Cloudflare's count, WIRED reports. The PHP Foundation has not seen a successful takeover of PHP2Shell. That is not a win. That is luck wearing a badge.

PHP is the old language still answering on a wild, internet-facing stretch of the web. PHP2Shell is a cluster of interpreter bugs. If you can use them, an attacker runs commands on the machine — a shell, which is why the name sounds like a threat and not a feature. WIRED reports some underlying issues were identified in 2024 and written off as too complex for a human attacker. Complexity was the lock. The industry then sold cheaper lockpicks and called it intelligence.

WIRED says researchers at Calif found the flaws and built exploits in early August, using frontier models under OpenAI's Patch the Planet program plus people who know PHP. OpenAI and Google-owned Wiz then independently found the same class with AI. Sagi Tzadik, a Wiz security researcher, told WIRED the PHP team had known for years and did not fix the hole because an attacker, at least a human one, could not leverage it.

Name the act. Maintainers of a language the public internet still leans on left rot in the interpreter because it failed a human exploitability test. The model vendors then walked specialists to a working exploit, published the map, and watched automated junk hit the range. Microsoft shipped a record 1,453 security vulnerabilities in a month, WIRED notes. Jake Williams of Hunter Strategy told WIRED to expect more long-life bugs and that PHP's reach is unusually exposed. Niels Provos is not really worried. He is not the person still running your public PHP.

The dream this decade was salvation by scanner: models find the rot, grown-ups patch it, the foundation holds. What they shipped turns last year's unexploitable into this week's mass probe and bills it as public service. Researchers funded through the same shops whose tools compressed disclosure into Cloudflare hours. The credential that opens the room is the compromise. The machine did not invent the rot. It printed the floor plan, invited the gutter, and invoiced Patch the Planet. Patch like they already have your address. "Too complex" expired the afternoon a specialist and a model sat down. The marks still run the servers. The product was never a cure.

## Takeaways
- Treat any backlog labeled too complex to exploit as expired; inventory internet-facing PHP and patch within hours of disclosure, not weeks.
- Isolate vendor research programs from incident response: AI-assisted discovery now compresses publication-to-scan into Cloudflare-scale time.
- Require a named human PHP expert to sign off exploitability and the all-clear; models magnify the interpreter, they do not replace the people who know it.
