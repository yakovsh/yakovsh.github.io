---
layout: post
title: Response to a WSJ article on C/R
date: 2003-11-18 09:00:05.000000000 -05:00
redirect_from:
  - /work/anti-spam/response-to-a-wsj-article-on-cr-november-18th-2003/
---
This is written in response to a [recent column](https://web.archive.org/web/20060113001248/http://ptech.wsj.com/archive/mailbox-20031113.html) by [Walter Mossberg](https://en.wikipedia.org/wiki/Walt_Mossberg) that was printed in the [Wall Street Journal](http://www.wsj.com). In this column, Walter calls challenge/response technology "the only truly effective method for fighting spam". The following response from myself was sent to Walter.  
  
It is hardly possible to call C/R "the only truly effective method". The more correct description would be "a rather effective method TODAY", as I am going to explain.The basic C/R process has three different approaches\[4\]: (1) autheticating the sender, (2) making sure the same exact message originated from the sender, and (3) making sure the sender is human by presenting some graphic (Turing tests). There are numerous problems with these three approaches (see \[4\] section 2.2\].

The first approach where a sender is being autheticated by sending an email to his address, puts an additional burden on the sender. The problem also is that many C/R systems are not implemented properly\[2\]\[5\] and can end up challenging other machines or even each other\[2\]. Furthermore, nothing stops spammers from setting up automated systems which respond to such challenges\[8\]. Mailing lists are also affected by C/R systems to a degree where some list operators have refused to respond to C/R messages all together because of the burden\[8\]. Additionally, given enough incentive spammers can forge the return address of someone from the receiver's whitelist, granting them access\[2\]. There are also numerous privacy issues\[8\].

The second approach which asks the sender's server whether a specific message originated from that server, is not widely used today because of a lack of protocols to enable such transactions \[1\] (the ASRG is currently considering one such protocol called CRI \[4\]). The problems inherent with this approach is the lack of a standard protocol \[1\], inability to people who are travelling to send email from different servers\[1\], and the need to the sender's server to keep copies of all sent messages which raises significant privacy issues\[1\].

The third approach, being the most popular today, includes in the message a link to an image or an image that presents the sender with a puzzle, usually some letters or numbers, that cannot be readily recognized by a computer, but can be easily read by a human being. These are called "reverse Turing tests" \[4\]. There are numerous problems with these tests. First of all, they cannot be used by disabled users \[4\], which has been recently pointed out by the W3C in their draft on the issue \[6\]. Second, it has not been proven that these images cannot be recognized by a computer, and some approaches have been broken by spammers. Third, given enough incentive a spammer can hire people in developed countries to answer the challenges, still regaining the cost advantage\[8\].

However, the best example of spammers's innovation ability is the recent finding of a spammer who setup a free porn site which serves a Turing test challenge every five or ten images. People visiting the site, responded to the challenges solving spammer's problem\[7\]. While this particular case was not used to break C/R systems, but rather registration forms, the point is the same.

While challenge/response is an effective method of fighting spam today, with some anti-spam companies deploying the technology reporting over 99% block rates, nevertheless it is not the ultimate or the "only" solution to spam. Additionally, the percentage of deployed C/R systems is so low, that spammers do not have the incentive to break them\[8\]. This is akin to having a security product that has never been tested in public - until hackers actually start attacking, one cannot claim that it is effective. The real test of C/R will come once a significant number of C/R systems are deployed, and spammers will try to break them. It is then that the C/R technology will either win or fall by the wayside like many others.

Therefore, challenge / response is only one of the many tools used to fight spam, and cannot be called "the only truly effective method" by any strech of imagination. One thing must be kept in mind that C/R addresses the issue of forgery in email\[1\], something that is a general authetication problem which has many solutions. C/R is not the only solution for that problem out there, there are many others which may or may not operate better\[1\]\[2\]. Putting things in perspective, the spam problem has many facets, and authetication vs. forgery is only one of them. An effective response to spam requires a combination of many efforts on many fronts including technical, legal, and social. Even within the technical realm, an effective solution requires an on-going, adaptive effort, with stochastic rather than complete results, utilizing multiple, adaptive techniques\[3\].

References:  
1. Leibzon, W.; "Email Path Verification", ASRG,  
[http://www.elan.net/~william/asrg-emailpathverification-presentation.pdf](http://www.elan.net/~william/asrg-emailpathverification-presentation.pdf)  
2. Levine, John R.; "Technical Responses to Spam", Taughannock Networks,  
[http://www.taugh.com/spamtech.pdf](http://www.taugh.com/spamtech.pdf)  
3. Crocker, D., Levine, J., and Schryver, V.; "Technical Considerations for Spam Control Mechanisms", ASRG,  
[http://www.ietf.org/internet-drafts/draft-crocker-spam-techconsider-02.txt](http://www.ietf.org/internet-drafts/draft-crocker-spam-techconsider-02.txt)  
4. Dean, E., and Shafranovich, Y.; " Challenge / Response Interworking (CRI) Framework for Challenge / Response Email Systems", ASRG,  
[http://www.ietf.org/internet-drafts/draft-irtf-asrg-cri-00.txt](http://www.ietf.org/internet-drafts/draft-irtf-asrg-cri-00.txt)  
5. Templenton, B.; "Proper principles for Challenge/Response anti-spam systems"  
[http://www.templetons.com/brad/spam/challengeresponse.html](http://www.templetons.com/brad/spam/challengeresponse.html)  
6. May, M.; "Inaccessibility of Visually-Oriented Anti-Robot Tests: Problems and Alternatives"; W3C,  
[http://www.w3.org/TR/turingtest/](http://www.w3.org/TR/turingtest/)  
7. Spice, B,; "CMU student taps brain's game skills", Pittsburgh Post-Gazette,  
[http://www.post-gazette.com/pg/03278/228349.stm](http://www.post-gazette.com/pg/03278/228349.stm)  
\[ALSO see: [https://www1.ietf.org/mail-archive/working-groups/asrg/current/msg07899.html](https://www1.ietf.org/mail-archive/working-groups/asrg/current/msg07899.html)\]  
8. ASRG Mailing List,  
[https://www1.ietf.org/mail-archive/working-groups/asrg/current/maillist.html](https://www1.ietf.org/mail-archive/working-groups/asrg/current/maillist.html)  
[http://news.gmane.org/gmane.ietf.asrg](http://news.gmane.org/gmane.ietf.asrg)
