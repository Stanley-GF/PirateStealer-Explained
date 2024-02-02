# PirateStealer
## My Goals When I Created PirateStealer
Back in 2020, I lost my Discord account due to malware I downloaded onto my computer. I suppose every villain has a backstory. When I lost my account, I wasn't mad or sad; I was amazed by how an application, a small 270kb executable file, took all my information.

I already had coding knowledge and wanted to demonstrate to Discord that their application was terribly insecure, especially using Electron, and even worse for Exodus. That's how I created the first malware using an injection in Electron to gather information like a keylogger.

My goals were never to infect people or to make money from it. The perfect example is that I never used it and always provided help to people contacting me. I created a malware remover and contributed to most of them, as well as to malware analysis. I was young at the time, 12 when the project started, and truly believed in the educational purpose of the malware.

## Do I Regret It?
To make it clear, I do not regret a single line of code of PirateStealer. If I hadn't been the one who made PirateStealer, someone else would have, keeping the source private and making it harder for malware & security engineers. Of course, some things could have gone differently (like BBY Stealer taking my source and research), but I feel that if I hadn't created this "malware" — which was more a proof of concept than actual malware — Discord would have continued to be insecure.

## What Would I Have Done Differently?
Firstly, yes, I made some mistakes. I was 12 at the time and wasn't fully aware of what I was doing, so keeping the source working, yes, but maybe not building a stub for it.

## How Was the PoC (PirateStealer) Working?
Electron is a JavaScript framework, and as you may know, JavaScript is not a compiled language. Injecting code was, therefore, easy, especially since it was retained on every startup, as was the case for Exodus.

## Will There Be Another PirateStealer One Day?
As I said at the beginning of 2023, PirateStealer is dead. There will be no more PirateStealer, and all the news relating PS and Gotham are purely fake. Gotham is a completely different project made by people I know and respect, but it is clearly a private & malicious malware.

## The Crazy Inactivity of Discord, Knowing the Vulnerability Is Still There
I remember publishing a thousand ways and proofs of concept on how to fix Discord, and not a single fix happened!

I wish to thank Exodus Wallet because, unlike Discord, they fixed the vulnerability as soon as I reported it to them.

## I Have Met Great People Through This Adventure
By the way, I made 0 dollars off PirateStealer while other people made money by stealing my source. At that moment, I understood how terrible open-source was. So, if I can give you one piece of advice, never do open-source. If you have a good idea, a good project, sell it!

Thank you.
## Resources About PirateStealer That I Wish to Share
- [Ars Technica article on malicious packages](https://arstechnica.com/information-technology/2021/12/malicious-packages-sneaked-into-npm-repository-stole-discord-tokens/)
- [Hacker News discussion](https://news.ycombinator.com/item?id=30146520)
- [PCRisk removal guide](https://www.pcrisk.com/removal-guides/27005-piratestealer-malware)
- [YouTube video on PirateStealer](https://www.youtube.com/watch?v=QEnYkkzwCG8)
- [OTX AlienVault pulse](https://otx.alienvault.com/pulse/61d55fb24f8cb2b3b187c7f5)
- [HowToFix guide](https://howtofix.guide/piratestealer-malware/)
- [HackerNoon reversing Node.js malware analysis](https://hackernoon.com/reversing-nodejs-malware-part-2-analysing-the-source-code)
- [ITNext article on reversing a Node.js malware](https://itnext.io/how-i-reversed-a-nodejs-malware-and-found-the-author-7dd9531b389f)
- [Discussion on Reddit about suspicious messages](https://www.reddit.com/r/discordapp/comments/qlgu1i/is_anyone_else_receiving_suspicious_messages_from/hj4n6ih/?context=3)
- [Reddit discussion on Discord malware analysis](https://www.reddit.com/r/Malware/comments/zdpzgz/discord_malware_analysis/)
