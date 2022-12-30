
[]{#_bookmark56 .anchor}**CHAPTER 5**

**第五章**

MODIFIED SOURCE AND BINARY DISTRIBUTION

修改后的源代码及二进制的分发

In this chapter, we discuss the two core sections that define the
rights and obligations for those who modify, improve, and/or
redistribute GPL'd software. These sections, GPLv2 2--3, define the
central core rights and requirements of GPLv2.

在本章中，我们将讨论两个核心篇章，以定义修改、改进和/或重新分发GPL下软件的人的权利及义务。该篇章中，GPLv2第2至3条款，定义了GPLv2的中心核心权利及要求。

## GPLv2 §2: Share and Share Alike

## GPLv2第2条：共享且以相同方式共享

For many, this is where the "magic" happens that defends software
freedom upon redistribution. GPLv2 2 is the only place in GPLv2 that
governs the modification controls of copyright law. If users
distribute modified versions a GPLv2'd program, they must follow the
terms of GPLv2 2 in making those changes. Thus, this sections ensures
that the body of GPL'd software, as it continues and develops, remains
Free as in freedom. To achieve that goal, GPLv2 2 first sets forth
that the rights of redistribution of modified versions are the same as
those for verbatim copying, as presented in GPLv2 1. Therefore, the
details of charging money, keeping copyright notices intact, and other
GPLv2 1 provisions are intact here as well. However, there are three additional requirements.



### The Simpler Parts of GPLv2 §2

The first (GPLv2 2(a)) requires that modified files carry "prominent
notices" explaining what changes were made and the date of such
changes. This section does not prescribe some specific way of marking
changes nor does it control the process of how changes are made.
Primarily, GPLv2 2(a) seeks to ensure that those receiving modified
versions know the history of changes to the software. For some users,
it is important to know that they are using the standard version of
program, because while there are many advantages to using a fork,
there are a few disadvantages. Users should be informed about the
historical context of the software version they use, so that they can
make proper support choices. Finally, GPLv2 2(a) serves an academic
purpose --- ensuring that future developers can use a diachronic
approach to understand the software.

GPLv2 2(c), a relatively simple section, requires that any program
which (before modification) "normally reads commands interactively
when run" and displays or prints legal information also display all
copyright notices, warranty disclaimer, modification indications and a
pointer to the license, even in modified versions. The requirement is
relatively simple, and relates to an important policy goal of
copyleft: downstream users should be informed of their rights. Its
implications and details are straightforward and simple.

### GPLv2 §2(b)

Meanwhile, GPLv2 2(b) requires careful and extensive study. Its four
short lines embody the some of the essential legal details of "share
and share alike". These 46 words are considered by some to be the most
worthy of careful scrutiny because they can be a source of great
confusion when not properly understood.

In considering GPLv2 2(b), first note the qualifier: it *only* applies
to derivative, combined and/or modified works that "you distribute or
publish". Despite years of education efforts on this matter, many
still believe that modifiers of GPL'd software *must* publish or
otherwise share their changes. On the contrary, GPLv2 2(b) **does not
apply if** the changes are never distributed. Indeed, the freedom to
make private, personal, unshared changes to software for personal use
only should be protected and defended.[^1^](#_bookmark60)

Next, we again encounter the same matter that appears in GPLv2 *§*0,
in the following text: "\...that in whole or part contains or is
derived from the Program or any part thereof."

Again, the GPL relies here on copyright law. If, under copyright law,
the modified version "contains or is derived from" the GPL'd software,
then the requirements of GPLv2 2(b) apply. The GPL invokes its control
as a copyright license over the modification of the work in
combination with its control over distribution of the work.

The final clause of GPLv2 2(b) describes what the licensee must do if
she distributes or publishes a modified version of the work ---
namely, the following:

\[The work must\] be licensed as a whole at no charge to all third
parties under the terms of this License.

That is probably the most tightly-packed phrase in all of the GPL.
Consider each subpart carefully.

The work "as a whole" is what is to be licensed. This is an important
point that GPLv2 2 spends an entire paragraph explaining; thus this
phrase is worthy of a lengthy discussion here. As a programmer
modifies a software program, she generates new copyrighted material
--- fixing expressions of ideas into the tangible medium of electronic
file storage. That programmer is indeed the copyright holder of those
new changes. However, those changes are part and parcel to the
original work distributed to the programmer under GPL. Thus, the
license of the original work affects the license of the new whole
combined and/or derivative work.

It is certainly possible to take an existing independent work (called
) and combine it with a GPL'd program (called ). The license of , when
it is distributed as a separate and independent work, remains the
prerogative of the copyright holder of . However, when is combined
with , it produces a new work that is the combination of the two
(called + ). The copyright of this combined work, + , is held by the
original copyright holder of each of the two works.

In this case, GPLv2 2 lays out the terms by which + may be distributed
and copied. By default, under copyright law, the copyright holder of
would not have been permitted to distribute + ; copyright law forbids
it without the expressed permission of the copyright holder of .
(Imagine, for a moment, if were a proprietary product --- would its
copyright holders give you permission to create and distribute +
without paying them a hefty sum?) The license of , the GPL, states the
options for the copyright holder of

who may want to create and distribute + . The GPL's pre-granted
permission to create and distribute combined and/or derivative works,
provided the terms of the GPL are upheld, goes far above and beyond
the permissions that one would get with a typical work not covered by
a copyleft license. Thus, to say that this condition is any way
unreasonable is simply ludicrous.

The GPL recognizes what is outside its scope. When a programmer's work
is "separate and independent" from any GPL'd program code with which
it could be combined, then the obligations of copyleft do not extend
to the work separately distributed. Thus, Far from attempting to
extend copyleft beyond the scope of copyright, the licenses explicitly
recognize.

Thus, GPL recognizes what is outside its scope. When a programmer's
work is "separate and inde- pendent" from any GPL'd program code with
which it could be combined, then copyleft obligations do not

^1^[]{#_bookmark60 .anchor}Most Free Software enthusiasts believe
there is a **moral** obligation to redistribute changes that are
generally useful, and they often encourage companies and individuals
to do so. However, there is a clear distinction between what one
**ought** to do and what one **must** do.

extend to the independent work separately distributed. Thus, far from
attempting to extend copyleft beyond the scope of copyright, GPL
explicitly limits the scope of copyleft to the scope of copyright.

GPL does not, however (as is sometimes suggested) distinguish
"dynamic" from "static" linking of pro- gram code. It is occasionally
suggested that a subroutine "dynamically" linked to GPL'd code is, by
virtue of the linking alone, inherently outside the scope of copyleft
on the main work. This is a misunderstanding. When two software
components are joined together to make one work (whether a main and
some library subroutines, two objects with their respective methods,
or a program and a "plugin") the combination infringes the copyright
on the components if the combination required copyright permission
from the com- ponent copyright holders, as such permission was either
not available or was available on terms that were not observed.

In other words, when combining other software with GPL'd components,
the only available permission is GPL. The combiner must observe and
respect the GPL observed on the combination as a whole. It matters not
if that combination is made with a linker before distribution of the
executable, is made by the operating system in order to share
libraries for execution efficiency at runtime, or results from runtime
references in the language at runtime (as in Java programs).

The next phrase of note in GPLv2 2(b) is "licensed . . . at no
charge." This phrase confuses many. The sloppy reader points out this
as "a contradiction in GPL" because (in their confused view) that
clause of GPLv2 2 says that re-distributors cannot charge for modified
versions of GPL'd software, but GPLv2 1 says that they can. Avoid this
confusion: the "at no charge" **does not** prohibit re-distributors
from charging when performing the acts governed by copyright
law,[^2^](#_bookmark62) but rather that they cannot charge a fee for
the *license itself*. In other words, redistributors of (modified and
unmodified) GPL'd works may charge any amount they choose for
performing the modifications on contract or the act of transferring
the copy to the customer, but they may not charge a separate licensing
fee for the software.

GPLv2 2(b) further states that the software must "be licensed . . . to
all third parties." This too yields some confusion, and feeds the
misconception mentioned earlier --- that all modified versions must be
made available to the public at large. However, the text here does not
say that. Instead, it says that the licensing under terms of the GPL
must extend to anyone who might, through the distribution chain,
receive a copy of the software. Distribution to all third parties is
not mandated here, but GPLv2 2(b) does require re- distributors to
license the whole work in a way that extends to all third parties who
may ultimately receive a copy of the software.

In summary, GPLv2 2(b) says what terms under which the third parties
must receive this no-charge license. Namely, they receive it "under
the terms of this License", the GPLv2. When an entity *chooses* to
redistribute a work based on GPL'd software, the license of that whole
work must be GPL and only GPL. In this manner, GPLv2 *§*2(b) dovetails
nicely with GPLv2 *§*6 (as discussed in Section
[7.3](#gplv2-6-gpl-my-one-and-only) of this tutorial).

The final paragraph of GPLv2 2 is worth special mention. It is
possible and quite common to aggregate various software programs
together on one distribution medium. Computer manufacturers do this
when they ship a pre-installed hard drive, and GNU/Linux distribution
vendors do this to give a one-stop CD or URL for a complete operating
system with necessary applications. The GPL very clearly permits such
"mere aggregation" with programs under any license. Despite what you
hear from its critics, the GPL is nothing like a virus, not only
because the GPL is good for you and a virus is bad for you, but also
because simple contact with a GPL'd code-base does not impact the
license of other programs. A programmer must expend actual effort to
cause a work to fall under the terms of the GPL. Redistributors are
always welcome to simply ship GPL'd software alongside proprietary
software or other unrelated Free Software, as long as the terms of GPL
are adhered to for those packages that are truly GPL'd.

### Right to Private Modification

The issue of private modifications of GPLv2'd works deserves special
attention. While these rights are clearly explicit in GPLv3 2 2 (see
[9.4](#gplv3-2-basic-permissions) of this tutorial for details), the
permission to create private modifications is mostly implicit in
GPLv2. Most notably, the requirements of GPLv2 2 (and GPLv2 3, which
will be discussed next) are centered around two different copyright
controls: both modification *and* distribution. As

^2^[]{#_bookmark62 .anchor}Recall that you could by default charge for
any acts not governed by copyright law, because the license controls
are confined by copyright.

such, GPLv2 2's requirements need only be met when a modified version
is distributed; one need not follow them for modified versions that
are not distributed.[^3^](#_bookmark65)

However, the careful reader of GPLv2 will notice that, unlike GPLv3,
no other clauses of the license actually give explicit permission to
make private modifications. Since modification of software is a
control governed by copyright, a modifier needs permission from the
copyright holder to engage in that activity.

In practice, however, traditional GPLv2 interpretation has always
assumed that blanket permission to create non-distributed modified
versions was available, and the [FSF has long opined that distribution
of](http://www.gnu.org/licenses/gpl-faq.html#GPLRequireSourcePostedPublic)
[modified versions is never
mandatory.](http://www.gnu.org/licenses/gpl-faq.html#GPLRequireSourcePostedPublic)
This issue is one of many where GPLv3 clarifies in explicit text the
implicit policy and intent that was solidified via long-standing
interpretation of GPLv2.

## GPLv2 §3: Producing Binaries

Software is a strange beast when compared to other copyrightable
works. It is currently impossible to make a film or a book that can be
truly obscured. Ultimately, the full text of a novel, even one written
by William Faulkner, must be presented to the reader as words in some
human-readable language so that they can enjoy the work. A film, even
one directed by David Lynch, must be perceptible by human eyes and
ears to have any value.

Software is not so. While the source code --- the human-readable
representation of software --- is of keen interest to programmers,
users and programmers alike cannot make the proper use of software in
that human-readable form. Binary code --- the ones and zeros that the
computer can understand --- must be predicable and attainable for the
software to be fully useful. Without the binaries, be they in object
or executable form, the software serves only the didactic purposes of
computer science.

Under copyright law, binary representations of the software are simply
modified versions (and/or deriva- tive works) of the source code.
Applying a systematic process (i.e., "compilation"[^4^](#_bookmark66))
to a work of source code yields binary code. The binary code is now a
new work of expression fixed in the tangible medium of electronic file
storage.

Therefore, for GPL'd software to be useful, the GPL, since it governs
the rules for creation of modified works, must grant permission for
the generation of binaries. Furthermore, notwithstanding the relative
popularity of source-based GNU/Linux distributions like Gentoo, users
find it extremely convenient to receive distribution of binary
software. Such distribution is the redistribution of modified works of
the software's source code. GPLv2 3 addresses the matter of creation
and distribution of binary versions.

Under GPLv2 3, binary versions may be created and distributed under
the terms of GPLv2 1--2, so all the material previously discussed
applies here. However, GPLv2 3 must go a bit further. Access to the
software's source code is an incontestable prerequisite for the
exercise of the fundamental freedoms to modify and improve the
software. Making even the most trivial changes to a software program
at the binary level is effectively impossible. GPLv2 3 must ensure
that the binaries are never distributed without the source code, so
that these freedoms are passed through the distribution chain.

GPLv2 3 permits distribution of binaries, and then offers three
options for distribution of source code along with binaries. The most
common and the least complicated is the option given under GPLv2 3(a).

GPLv2 3(a) offers the option to directly accompany the source code
alongside the distribution of the binaries. This is by far the most
convenient option for most distributors, because it means that the
source- code provision obligations are fully completed at the time of
binary distribution (more on that later).

### Complete, Corresponding Source (CCS)

Under GPLv2 3(a), the source code provided must be the "corresponding
source code." Here "correspond- ing" primarily means that the source
code provided must be that code used to produce the binaries being
distributed. That source code must also be "complete". GPLv2 3's
penultimate paragraph explains in de- tail what is meant by
"complete". In essence, it is all the material that a programmer of
average skill would

^3^[]{#_bookmark65 .anchor}As a matter of best practice, it's useful
to assume that all software may eventually be distributed later, even
if there no plans for distribution at this time. Too often, GPL
violations occur because of a late distribution decision of software
that was []{#_bookmark66 .anchor}otherwise never intended for
distribution.

^4^"Compilation" in this context refers to the automated computing
process of converting source code into binaries. It has absolutely
nothing to do with the term "compilation" in copyright statues.

need to actually use the source code to produce the binaries she has
received. Complete source is required so that, if the licensee
chooses, she should be able to exercise her freedoms to modify and
redistribute changes. Without the complete source, it would not be
possible to make changes that were actually directly derived from the
version received.

Based on the appearance of those two words, GPL theorists will often
refer to the source code required under the previsions of this section
as "Complete, Corresponding Source", sometimes abbreviated as CCS. CCS
is not a formal, defined term in GPLv2, but rather, GPL theorists
coined the acronym CCS to embody not just the concepts of "complete"
and "corresponding" as found in GPLv2, but the entirety of GPLv2's
requirements for source code provisioning. In other words, GPL
theorists might say: "the company provided some source, but it wasn't
CCS", which would mean the source code failed in some ways to meet
some term of GPLv2.

Indeed, CCS needs completely include not just that source which is
directly translated by the compiler into object code, but other
materials necessary to convert the source into equivalent binaries.
Specifically, GPLv2 3 requires that the source code include
"meta-material" like scripts, interface definitions, and other
material that is used to "control compilation and installation" of the
binaries. In this manner, those further down the distribution chain
are assured that they have the unabated freedom to build their own
modified works from the sources provided.

This requirement is not merely of theoretical value. If you pay a high
price for a copy of GPL'd binaries (which comes with CCS, of course),
you have the freedom to redistribute that work at any fee you choose,
or not at all. Sometimes, companies attempt a GPL-violating cozenage
whereby they produce very specialized binaries (perhaps for an obscure
architecture). They then give source code that does correspond, but
withhold the "incantations" and build plans they used to make that
source compile into the specialized binaries. Such distributions
violate GPL, since the downstream users cannot effectively "control
compilation and installation" of the binaries.

### Additional Source Provision Options

Software distribution comes in many forms. Embedded manufacturers, for
example, have the freedom to put GPL'd software into mobile devices
with very tight memory and space constraints. In such cases, putting
the source right alongside the binaries on the machine itself might
not be an option. While it is recommended that this be the default way
that people comply with GPL, the GPL does provide options when such
distribution is unfeasible.

GPLv2 3, therefore, allows source code to be provided on any physical
"medium customarily used for software interchange." By design, this
phrase covers a broad spectrum --- the phrase seeks to pre-adapt to
changes in technology. When GPLv2 was first published in June 1991,
distribution on magnetic tape was still common, and CD was relatively
new. By 2002, CD was the default. By 2007, DVD's were the default.
Now, it's common to give software on USB drives and SD cards. This
language in the license must adapt with changing technology.

Meanwhile, the binding created by the word "customarily" is key. Many
incorrectly believe that dis- tributing binary on CD and source on the
Internet is acceptable. In the corporate world in industrialized
countries, it is indeed customary to simply download a CDs' worth of
data quickly. However, even today in the USA, many computer users are
not connected to the Internet, and most people connected to the
Internet still have limited download speeds. Downloading CDs full of
data is not customary for them in the least. In some cities in Africa,
computers are becoming more common, but Internet connectivity is still
available only at a few centralized locations. Thus, the "customs"
here are normalized for a worldwide userbase. Simply providing source
on the Internet --- while it is a kind, friendly and useful thing to
do --- is not usually sufficient.

Note, however, a major exception to this rule, given by the last
paragraph of GPLv2 3. *If* distribution of the binary files is made
only on the Internet (i.e., "from a designated place"), *then* simply
providing the source code right alongside the binaries in the same
place is sufficient to comply with GPLv2 *§*3.

As is shown above, under GPLv2 3(a), embedded manufacturers can put
the binaries on the device and ship the source code along on a CD.
However, sometimes this turns out to be too costly. Including a CD
with every device could prove too costly, and may practically
(although not legally) prohibit using GPL'd software. For this
situation and others like it, GPLv2*§* 3(b) is available.

GPLv2 3(b) allows a distributor of binaries to instead provide a
written offer for source code alongside those binaries. This is useful
in two specific ways. First, it may turn out that most users do not
request the source, and thus the cost of producing the CDs is saved
--- a financial and environmental windfall. In addition, along with a
GPLv2 3(b) compliant offer for source, a binary distributor might
choose to *also* give a URL for source code. Many who would otherwise
need a CD with source might turn out to have those coveted high
bandwidth connections, and are able to download the source instead ---
again yielding environmental and financial windfalls.

However, note that regardless of how many users prefer to get the
source online, GPLv2 3(b) does place lasting long-term obligations on
the binary distributor. The binary distributor must be prepared to
honor that offer for source for three years and ship it out (just as
they would have had to do under GPLv2 3(a)) at a moment's notice when
they receive such a request. There is real organizational cost here:
support engineers must be trained how to route source requests, and
source CD images for every release version for the last three years
must be kept on hand to burn such CDs quickly. The requests might not
even come from actual customers; the offer for source must be valid
for "any third party".

That phrase is another place where some get confused --- thinking
again that full public distribution of source is required. The offer
for source must be valid for "any third party" because of the freedoms
of redistribution granted by GPLv2 1--2. A company may ship a binary
image and an offer for source to only one customer. However, under
GPL, that customer has the right to redistribute that software to the
world if she likes. When she does, that customer has an obligation to
make sure that those who receive the software from her can exercise
their freedoms under GPL --- including the freedom to modify, rebuild,
and redistribute the source code.

GPLv2 3(c) is created to save her some trouble, because by itself
GPLv2 3(b) would unfairly favor large companies. GPLv2 3(b) allows the
separation of the binary software from the key tool that people can
use to exercise their freedom. The GPL permits this separation because
it is good for re-distributors, and those users who turn out not to
need the source. However, to ensure equal rights for all software
users, anyone along the distribution chain must have the right to get
the source and exercise those freedoms that require it.

Meanwhile, GPLv2 3(b)'s compromise primarily benefits companies that
distribute binary software commercially. Without GPLv2 3(c), that
benefit would be at the detriment of the companies' customers; the
burden of source code provision would be unfairly shifted to the
companies' customers. A customer, who had received binaries with a
GPLv2 3(b)-compliant offer, would be required under GPLv2 (sans GPLv2
3(c)) to acquire the source, merely to give a copy of the software to
a friend who needed it. GPLv2 3(c) reshifts this burden to entity who
benefits from GPLv2 3(b).

GPLv2 3(c) allows those who undertake *noncommercial* distribution to
simply pass along a GPLv2 3(b)- compliant source code offer. The
customer who wishes to give a copy to her friend can now do so without
provisioning the source, as long as she gives that offer to her
friend. By contrast, if she wanted to go into business for herself
selling CDs of that software, she would have to acquire the source and
either comply via GPLv2 3(a), or write her own GPLv2 3(b)-compliant
source offer.

This process is precisely the reason why a GPLv2 3(b) source offer
must be valid for all third parties. At the time the offer is made,
there is no way of knowing who might end up noncommercially receiving
a copy of the software. Companies who choose to comply via GPLv2 3(b)
must thus be prepared to honor all incoming source code requests. For
this and the many other additional necessary complications under GPLv2
*§§*3(b--c), it is only rarely a better option than complying via
GPLv2 *§*3(a).

