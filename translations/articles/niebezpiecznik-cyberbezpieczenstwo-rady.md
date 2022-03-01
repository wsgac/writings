# Russian war on Ukraine and cybersecurity in Poland. Some advice #

You're asking how the Russian aggression in Ukraine influences the
security of Polish internet and how to defend yourselves against
potential negative impact of cyberattacks aimed at Ukraine and allied
countries. So far there hasn't been any negative impact, which doesn't
mean it won't change. Here are some pieces of advice and a description
of what we think might threaten all of us on the internet.

The bombing of Ukraine started in the middle of the night, but **the
first phase of this war were cyberspace activities**. Actually, these
have commenced on January 15th, when we reported ["an attack on
several government
networks"](https://niebezpiecznik.pl/post/ktos-chcial-nas-wplatac-w-cyberkonflikt-z-ukraina/)
(so called **Deface**). The crackers used tools similar to those used
by Russian groups to swap the contents of government sites for a
message suggesting that responsible for the attack were Poles hostile
to Ukrainians.

Additionally, on January 15th some Ukrainian government networks were
infected by malware used to erase data (so called **wipers**). This
was a month ago. Whereas yesterday we have [informed on our
Twitter](https://twitter.com/niebezpiecznik/status/1496591393074163717?cxt=HHwWisC94ar8-sQpAAAA)
that around 16:00 ESET reported another wave of attacks against
"hundreds" of computers in Ukrainian companies and
institutions. Wipers were used again, these institutions were
paralyzed and forced to restore their systems from security
backups. This attack is thought to have been designed to hamper
reactions in the opening phase of an armed invasion which came 10
hours later. So this war began with a cyberattack.

Let us also mention lesser threats - regular
[DDoS](https://niebezpiecznik.pl/post/ukraina-informuje-o-atakach-ddos-na-mon-i-banki/)
attacks against Ukrainian servers. These attacks do not cause data
loss, but they **heighten the anxiety** among people unable to access
their bank accounts as a result.

Yesterday at 16:30 such a DDoS attack was launched against Ukrainian
institutions. Interestingly, at the same time a similar attack has
been detected by us and some other networks in Poland. It wasn't large
and was over in 30 minutes, but its nature was interesting - the
proportion of malicious traffic from Polish addresses had been larger
than in previous attacks we've seen.

## Consequences for Poland ##

Based on the above description of the current situation in Ukrainian
cyberspace we see 3 types of threats:

### 1. Malware ricochet ###

So far all actions of this type that we know of have targeted networks
and companies in Ukraine. But it's worth remembering that **the
internet has no boundaries** and many Polish companies have branches
or other connections to Ukraine. This means that an infection or
attack can quickly propagate to connected Polish branches and
offices. Yesterday's wiper attacks also affected **Lithuanian
companies** and a similar attack some years ago also hit [Polish
companies](https://niebezpiecznik.pl/post/kolejny-grozny-globalny-atak-tym-razem-ransomware-petya-ofiary-sa-takze-w-polsce/)
connected to Ukraine.

That is why Polish companies maintaining network contact with Ukraine
should:
  * make sure that connections between networks (branches) are
    properly filtered
  * verify configurations of security solutions and mechanisms,
    especially with respect to wiper propagation
  * introduce, wherever feasible, two-factor authentication,
    preferably based on U2F keys, to limit phishing and credential
    stuffing attacks
  * verify the correctness of backup copies and the ability to restore
    from them
	
### 2. Direct attack on Polish infrastructure ###

So far we don't have news of Polish infrastructure being a direct and
prioritized target of Russian attacks. This may change since, among
other things, we have officially begun (together with many other
countries) helping Ukraine in the cyberconflict, so Russians may want
to bind our resources with domestic problems.

Poland has already introduced
[CHARLIE-CRP](https://niebezpiecznik.pl/post/wprowadzono-stopien-alarmowy-charlie-crp-po-raz-pierwszy-w-polsce/)
alert state. This means that at least core infrastructure should be
monitored closer than usual. 24h surveillance has been established,
emergency procedures were tested - you can learn more about what this
means from our 4 minute video:

We don't think we are facing total cyber-paralysis, but we should be
prepared for temporary outages of various services and do not panic
when they do occur. To minimize the impact of such attacks:
  * **Make sure you keep your critical data locally, not in the
    cloud**. Contact information, licence keys, etc.
  * **Locate your money in multiple banks**. If one of them has
    trouble, you'll be able to use another one.
  * **Carry some cash** in case of bank system outages, but also in
    the event of trouble with payment intermediaries, card terminals,
    etc.
  * **Update your operating systems** on your computer, phone, TV,
    surveillance camera, fridge. Everywhere. This way you make it
    harder for potential attackers to exploit known vulnerabilities
    and gain access to your devices.
  * **Charge your powerbanks**. But presently more due to strong winds
    than Russian hacker attacks :).

### 3. Disinformation and PsyOp (happening already) ###

We've long seen disinformation activities on the part of Russia and
Belarus, also targeted at Poland. There are
[many](https://ik.org.pl/inwazja-na-ukraine-komunikat-instytutu-kosciuszki-dot-rosyjskich-narracji-w-infosferze/)
narratives. Let's recall just two examples. Weak "evidence" to the
effect that [Poles were responsible for cyberattacks on Ukrainian web
services](https://niebezpiecznik.pl/post/ktos-chcial-nas-wplatac-w-cyberkonflikt-z-ukraina/)
and the latest, so called **false-flag**, regarding an alleged Polish
attack on chlorine tanks [in a Donetsk sewage processing
plant](https://twitter.com/EliotHiggins/status/1495355366141534208):

The aim of these activities is to **pull allies apart**, but in the
internet era the threat of disinformation is much more complex and
frightening. We are seeing **fake news** in social media
(e.g. informing where a "tragic attack" took place) or traces of PsyOp
operations. Below is an example of SMS messages, to be sent to
Ukrainian soldiers immediately before the invasion, "encouraging" them
to flee and surrender without a fight:

Let's recall similar SMS messages, never seen directly (only
screenshots were circulated), sent to Poles near the border, informing
of a military mobilization [a couple of years
ago](https://niebezpiecznik.pl/post/niezalezna-pl-i-inne-serwisy-w-polsce-zhackowane-rozsiewaly-plotki-o-ewakuacji-polakow-przez-zandarmerie-i-wojska-usa/).

Such actions and posts are frequently **highly emotional** and aim to
**polarize** the discussion, falsely accuse somebody of something,
**cause anxiety**. They are quickly posted and shared. Basing on
half-truths, mixing facts with fake news, they're effective in
building false narratives. That is why:
  * **Do not believe everything you see on the net regarding "conflict
    area"**. Very often photos and videos have different locations and
    timestamps than they claim. Remember that such materials cannot
    always be easily verified and [their metadata can be
    falsified](https://niebezpiecznik.pl/prezent/).
  * **Base your knowledge on trusted sources**. Choose legitimate
    journalists who know the geopolitical situation, are present on
    site and are used to verifying news validity, because their
    reputation is at stake. You can find a list of people reporting
    from Ukraine
    [here](https://twitter.com/i/lists/1494327296383021062), but
    remember that they can also be susceptible to emotions, which is
    why...
  * **Think before passing information along**. Check the
    comments. Maybe someone noticed something suspicious about a piece
    of news.
  * **If, after the fact, you realize that new information invalidates
    what you've "passed along", make appropriate corrections or delete
    your entry**. Do not be ashamed to do so. Situation changes
    dynamically and many news items are truly professional
    manipulation. The risk of error is inevitable in internet
    discussion, but honest participants can be known by how they admit
    their own mistakes.
  * **Are you a journalist?** Describing a "computer attack" is no
    easy task - it requires technical knowledge. Because a DDoS is not
    as scary as RCE and not every leak is what it seems. Which is why
    before you publish a piece on a "cyberattack", ask someone from
    the cybersecurity community to fact-check it and avoid unnecessary
    panic. If you don't have a person you trust,
    [let_Qus_know](https://niebezpiecznik.pl/kontakt). We'll gladly
    help you understand the "scale" of an incident and explain its
    complexities.
	
But above all else:

## THE MOST IMPORTANT PIECE OF ADVICE FOR EVERYBODY ##

We think the advice below is the most important. If you only do one
thing to increase your cybersecurity, do this, because you have the
most control. This applies to everybody, but these attacks target
especially **politicians, journalists, influencers, VIPs - because
their influence and web of trust is particularly valuable to Russian
propaganda.**:

Make sure you're using a **password manager** and that you've enabled
[two-factor authentication (preferably U2F hardware
keys)](https://www.youtube.com/watch?v=Zr0PffkN09w) wherever
possible. Your passwords have long ago leaked from various
services. If you're reusing some of them, someone can use them to
impersonate you and **circulate fake news**.

A great example of how this strategy works, how it can disinform,
polarize and cause general media chaos, have been fake news
[circulated from Polish politicians'
accounts](https://niebezpiecznik.pl/post/jak-pani-minister-konto-przejeto-albo-nie/).

## Improve your cybersecurity for free ##

If you feel like time is ripe to finally take care of your
cybersecurity, we have some free resources for you:
1. Secure your email: [concise tutorial with tips for various email
   providers](https://www.youtube.com/watch?v=f0h_Ow2rw7s)
2. Secure your other accounts against attacks and interception. See
   [our free webinar](https://sklep.niebezpiecznik.pl/opis/7), dealing
   in detail with what one can do to decrease the possibility of
   intrusion and interception of one's accounts.
3. If you want to increase your awareness and competence in detecting
   disinformation and manipulation, and finding information on the net
   (about people, companies, even movements of Russian troops), have a
   look at our [free webinar on OSINT
   techniques](https://niebezpiecznik.pl/prezent/). Here is an example
   of a "traffic jam" at 3 a.m. from Google Maps. The jam was caused
   by slow-moving Russian tanks full of soldiers with cell phones...

In addition, on our [YouTube
channel](https://www.youtube.com/channel/UCe6nK69Yc1zna7QSJEfA9pw?sub_confirmation=1&cbrd=1&ucbcb=1)
you can find hours and hours of quality cybersecurity material. We
also have some paid tutorials on [how to secure your
smartphone](https://sklep.niebezpiecznik.pl/s/smartfony), as our
primary networked device today, carrying our most crucial data. Using
discount code CZUJNY you can buy them for half the price.

## Do you see anything weird? React! ##

If you notice any suspicious attacks, outages, website swaps, leaks -
[let us know](https://niebezpiecznik.pl/kontakt) or contact the
relevant CSIRT.

## Stay up to date! ##

We remind you that we post much more relevant information about the
Polish cyberspace situation on our
[Twitter](https://twitter.com/niebezpiecznik) and
[Facebook](https://facebok.com/niebezpiecznik) accounts. This website
contains the most important topics. So if you want real-time info,
follow us on [Twitter](https://twitter.com/niebezpiecznik) and
[Facebook](https://facebok.com/niebezpiecznik).

## Webinar for government employees ##

In recent days we've been contacted by employees of government
institutions, fearing being targeted for attacks due to the nature of
their work. Which is why we're planning to hold a special webinar
(around 30 minutes of condensed advice and Q&A), devoted to
**defending against cyberattacks** for government employees.

If you have an email account in the gov.pl domain or elsewhere
connected to public administration, you can subscribe to the list
below (other emails will be rejected). We'll let you know by email
when the webinar will take place.
