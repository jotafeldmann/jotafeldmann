# UOL / PagSeguro: ownership at scale

I joined UOL / PagSeguro on October 2, 2012. It was the first nationally recognized company I had
worked for and the first job whose product my mother immediately understood. PagSeguro's card readers
were changing how Brazilian businesses accepted payments, making card transactions more accessible
and reducing the cost and complexity of traditional point-of-sale systems.

PagSeguro was also expanding rapidly inside UOL. What had begun as a small number of teams was growing
into an operation that occupied almost an entire floor. I moved from working alone or in very small
groups to a team of around seven people inside an engineering organization of roughly one hundred.
That scale changed my understanding of collaboration, shared ownership and product development.

## Engineering across teams

My official title was Webmaster, at a time when frontend and backend engineering were only beginning
to become clearly separated disciplines. In practice, I worked across JavaScript, jQuery and Java in
several contexts:

- Phoenix, a generalist team that worked across the product stack;
- back-office systems used to operate the payment platform; and
- partner checkout integrations, including redirected and invisible checkout flows embedded in
  third-party commerce experiences.

The organization still relied heavily on SVN while experimenting with `git-svn`. Multiple teams
worked on a shared trunk, and monthly delivery cycles culminated in a difficult integration week. That
experience made the cost of late integration tangible and shaped how I later thought about version
control, smaller changes and collaboration across teams.

## The anti-phishing beacon

One of my most meaningful contributions began outside a planned sprint. I overheard PagSeguro's head
of security discussing persistent phishing attacks with our technical lead and product representative.
I turned my chair and said, "I think I can help with that."

Attackers were cloning PagSeguro pages to capture credentials before redirecting customers to the
legitimate site. I proposed and built an anti-phishing mechanism we called Beacon. A small JavaScript
component detected when copied pages were running from an unrecognized location, protected credential
inputs and notified a Java reporting API. I implemented the work end to end, from the browser code to
the backend and operational reporting.

The Beacon reduced the security team's detection and response cycle from weeks to hours. Reports from
the security team showed that operators of cloned sites could no longer understand how their pages
were being identified. I documented the design and operating model in Confluence so the knowledge
could be shared and maintained by the team.

The experience remains a defining example of ownership for me: noticing a problem outside my assigned
work, volunteering to help, building across frontend and backend, and seeing the result protect a
product I genuinely cared about.

## A culture of trust

UOL was also my first experience of a highly flexible and informal engineering culture. Flexible
hours, casual dress and open technical discussions created a strong sense of trust. That autonomy made
me more invested in the team and the product, not less. Constructive sprint discussions with
engineers, product stakeholders and agile practitioners taught me how much a healthy environment can
change both the quality of the work and the way people feel responsible for it.
