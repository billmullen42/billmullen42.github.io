---

layout: essay

type: essay

title: Which came first, the chicken or chickenHub?
date: 2016-09-12

labels:

  - Configuration Management

  - Version Control

---



<img class="ui medium left floated image" src="../images/GitHub-Mark-120px-plus.png">

## Which came first, the chicken or chickenHub?

The first time I ran into the issue of configuration management, or at least version control, was not in a software context. At the time, about a decade ago, I was getting my first bachelor's degree and working at the copy desk of the student newspaper. We used a fairly simple program to check documents in and out from the server, to pass an article through the various stages on the way to publication. At the time, I was impressed.

## Oh, but there's a downside?

But the process of reverting to an earlier version was flimsy at best, and nightmarish at worst. There was no formal system for documenting changes, and adding comments in-line was a passable but unenforceable solution - plus, there would be no way to know if text was added or removed without comment.

Not to mention the performance. I'm not certain if all of our problems were due to the software or poor server hardware, but problems would abound. Checking documents in or out involved significant delay, and often threw errors that were difficult to troubleshoot. Server crashes were all too common, and would involve time-consuming re-synching of local version after reboot. And, best of all, even taking all precautions during a server crash, there was a chance that work on the latest version of a document would simply be destroyed!

As one of the last two people to leave before the issue went to print, the performance issues were a special favorite of mine.

<img class="ui medium left floated image" src="../images/chicken.png">

## Git vs GitHub

So we can all agree that we like Git, right? Sound good? Great.

An interesting question is whether GitHub owes its popularity to GitHub, or the other way around. If you see this as a chicken-or-egg argument, it's worth noting that Git predates GitHub by about 3 years (2005 and 2008 releases, respectively), so it's not unreasonable to assume that GitHub is popular because of Git. 

It's also reasonable to assume the two are, for the purposes of this argument, inseparable. If GitHub makes Git better, and Git makes GitHub better, then we have a positive feedback loop of popularity, with no sole culprit.

I would wager that both of these are, to some extent, true, but let's look at how and why. As someone who's dealt with bad version control software, I have to lean heavily towards Git as the culprit for success. After all, take GitHub away from Git, and Git is still a good, and necessary, program. Take Git away from GitHub, and you just have cloud storage. Without good version control, GitHub might just be another GoogleDrive or Microsoft OneDrive. But in reality, it's so much more than that, because version control is so vital to what we do. GitHub is a logical extension of Git, whereas Git radically changes and defines what GitHub is.

But that's probably too reductive. Back to the idea of feedback loops, surely GitHub contributes significantly to the massive popularity of the pair. Imagine a scenario where Git is clearly better than the alternatives, but there's no corresponding cloud storage site. Could it be popular? Certainly. Could it be massively, dominantly popular? Perhaps not. Without the open-source component, without a presence in the cloud, Git could be the gold standard for those in the know, but perhaps it would be harder to know how good it is. If you or your team were using mediocre software for version control, perhaps you wouldn't know there's something else out there when it's not instantly available. Furthermore, if not for a huge existence online, there wouldn't be a need for there to be a single standard. Facebook is popular because other people are on Facebook, and it's reasonable to assume the same for GitHub: in this space, success begets success.

So, Git is what makes the pair good, but GitHub is what makes them discoverable.
