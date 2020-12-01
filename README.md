# limits

## Preamble

Everything has limits, including software systems. When you hit these limits, bad things can happen.

You've probably hit memory and disk limits, but those aren't the only ones.

This page lists limits that, when breached, led to someone having a bad time. I [tweeted](https://twitter.com/lhochstein/status/1332781588246097927) about limits and
got all sorts of interesting responses. This page contains some of them, with links to the tweets, which often contain more details.

## Examples of limits that have been breached with ill consequences

inodes. [@aegis](https://twitter.com/ageis/status/1332931216014790656), [Alex Elman](https://twitter.com/_pkill/status/1332784570371100674), [Benjamin Stein](https://twitter.com/benstein/status/1332840496956260354), [Thomas Attree](https://twitter.com/attree/status/1332986131068186629), [@dmolnar](https://twitter.com/dmolnar/status/1332788022232936450), [@anotherwalther](https://twitter.com/anotherwalther/status/1332785877811142659), [Jinsy Oommen](https://twitter.com/thegoodoommen/status/1332797783552765967), [Rafael Jesus](https://twitter.com/_jesus_rafael/status/1332799734302584834), [Ondrej Kokes](https://twitter.com/pndrej/status/1333132013231026178), [Peter Wang](https://twitter.com/pwang/status/1333038343416934403), [Cadey A. Ratio](https://twitter.com/theprincessxena/status/1333017957514043392), [@williamsjoe](https://twitter.com/williamsjoe/status/1332829443748896768), [Nic Wise](https://twitter.com/fastchicken/status/1332821356681994240), [ericdennis](https://twitter.com/ericdennis/status/1332796988429983744)


open file descriptors / handles. [Moritz Lenz](https://twitter.com/nogoodnickleft/status/1333129430424805376), [Matt McDonald](https://twitter.com/overstood/status/1332971151413284866), [@aegis](https://twitter.com/ageis/status/1332931216014790656), [Bruno Félix](https://twitter.com/felix19350/status/1332792700882575361), [Ken Carroll](https://twitter.com/Crumlinfinglas/status/1332809128398512130), [@ehashdn](https://twitter.com/ehashdn/status/1332820368868839425), [Jeff Bean](https://twitter.com/jwfbean/status/1332801837188071425), [@patriotvn](https://twitter.com/patriotvn/status/1332801416986025989), [Peter Wang](https://twitter.com/pwang/status/1333038343416934403), [@asm0dio](https://twitter.com/asm0di0/status/1333027981393063940), [@williamsjoe](https://twitter.com/williamsjoe/status/1332829443748896768), [ericdennis](https://twitter.com/ericdennis/status/1332796988429983744), [Jakub Korab](https://twitter.com/jakekorab/status/1332791724146647040)


processes (pids). [@RuinTaughtMe](https://twitter.com/RuinTaughtMe/status/1332799858722238464), [@patriotvn](https://twitter.com/patriotvn/status/1332801416986025989), [Matt Tex Ackerle](https://twitter.com/MattTexEckerle/status/1333043006820282368), [@pete23com](https://twitter.com/pete23com/status/1332783470632984581)

Ports. [@qudooschaudhry](https://twitter.com/qudooschaudhry), [Alex Hidalgo](https://twitter.com/ahidalgosre/status/1332782613279502338), [Rafael Jesus](https://twitter.com/_jesus_rafael/status/1332799734302584834), [@williamsjoe](https://twitter.com/williamsjoe/status/1332829443748896768)

TCP connections. [Sheeri K. Cabral](https://twitter.com/sheeri/status/1332882656200159232), [@Pluto_Berlin](https://twitter.com/Pluto_Berlin/status/1332842844751585281)

Threads. [@dbsmasher](https://twitter.com/dbsmasher/status/1332787577934344192), [David Bezley](https://twitter.com/dabeaz/status/1333054692633563139)

Entropy pool. [Justin Manchester](https://twitter.com/JuMaUK/status/1332798142958477316), [Petru Ratiu](https://twitter.com/rpetre/status/1332798387398340609)

Shebang length. [@bengerman13](https://twitter.com/bengerman13/status/1332794119094153221), [Anthony Sottile](https://twitter.com/codewithanthony/status/1332832546086797312?s=20)

Virtual memory. [@shanemhansen](https://twitter.com/shanemhansen/status/1332812554251321344), [@williamsjoe](https://twitter.com/williamsjoe/status/1332829443748896768)

How fast the kernel can find an unused port to allocate a new connection.  [Sean Kilgore](https://twitter.com/log1kal/status/1332862515135401984)

Pod memory limits. [@dastbe](https://twitter.com/dastbe/status/1332828656515784704)

Environment variable size. [Glen Mailer](https://twitter.com/glenathan/status/1333033938038747136)

Java ring buffer size. [Richard Tibbetts](https://twitter.com/tibbetts/status/1332808950027268096)

.NET framework threadpool I/O completion port limit. [Brandon Paddock](https://twitter.com/BrandonLive/status/1333102381597245441)

SQL Server buffer cache. [Dave Poole](https://twitter.com/DavidJPoole/status/1332958574214049794)

Concurrency limit of Java concurrent hash map. [Matt McDonald](https://twitter.com/overstood/status/1332971151413284866)

ulimit on number of processes that can be run per user. [Ben Hemphill](https://twitter.com/benhemphill/status/1332799141236367360)

memlock with JVM. [@aegis](https://twitter.com/ageis/status/1332931216014790656)

IOPs [Arie Kachler](https://twitter.com/akachler/status/1332809935932035073), [Jesse Noller](https://twitter.com/jessenoller/status/1332788536890720256)

System time divergence. [Nicolai von Neudeck](https://twitter.com/vonneudeck/status/1332797263249371136)

Goroutines. [@beccadottex](https://twitter.com/beccadottex/status/1332824960453144576)


Number of fields in an elastic search index. [@bengerman13](https://twitter.com/bengerman13/status/1332794119094153221)

Filename / path size limit, on Windows. [@BennettElder](https://twitter.com/BennettElder/status/1332790932568215552), [Peter Wang](https://twitter.com/pwang/status/1333038343416934403)

Number of vlans in vmware vcloud director, 2015 edition. [Jose manuel de arce](https://twitter.com/j0sema/status/1332956583190466560)


ipconntrack. [@shanemhansen](https://twitter.com/shanemhansen/status/1332812778826989570), [Glen Mailer](https://twitter.com/glenathan/status/1332784414137397252)

Load balancer license connection limits. [Franklin Wirtz](https://twitter.com/franklinwirtz/status/1332793886595444736)

Wal senders. [Max Knee](https://twitter.com/maxknee/status/1332851399026208768)

Kernel udp rx buffer size. [@sjoeboo](https://twitter.com/sjoeboo/status/1332800957760081924)

Network bandwidth. [@anotherwalther](https://twitter.com/anotherwalther/status/1332785877811142659), [Rafael Jesus](https://twitter.com/_jesus_rafael/status/1332799734302584834)

AWS API limit on number of requests made per minute when requesting new instances. [Justin Manchester](https://twitter.com/JuMaUK/status/1332801575421669379)

Number of links to a file. [@mendel](https://twitter.com/mendel/status/1332807569384103940)

Number of files per directory. [@hlieberman](https://twitter.com/hlieberman/status/1332796977407533059)

VPC DNS packet limits. [Rafael Jesus](https://twitter.com/_jesus_rafael/status/1332799734302584834)

Number of huge pages. [@patriotvn](https://twitter.com/patriotvn/status/1332801416986025989)

Connections to Oracle database. [Viktor Gamov](https://twitter.com/gAmUssA/status/1332914886075174912)

Socket filename length limit. [Anthony Sottile](https://twitter.com/codewithanthony/status/1332832546086797312?s=20)

Stack size. [@williamsjoe](https://twitter.com/williamsjoe/status/1332829443748896768)

Buffer exhaustion in NICs & switches. [@williamsjoe](https://twitter.com/williamsjoe/status/1332829443748896768)

AWS EC2 instance count limits. [Nic Wise](https://twitter.com/fastchicken/status/1332821356681994240)

Time Wait Assasination. [John Allspaw](https://twitter.com/allspaw/status/1332789693474332674)

Semaphores. [@rknayyar](https://twitter.com/rknayyar/status/1333003544903954434)

Number of OS threads. [AWS 2020-11-25](https://aws.amazon.com/message/11201/). 
