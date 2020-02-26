# ZIP Code Stats

In a conversation at work the other day, a colleague asked whether or not
the last digit of ZIP codes were "reasonably random," e.g., to assign a
people to treatment in a randomized trial.

My bet was "no" based on the fact that ZIP codes were designed not just to
be a random digit, but also to have some meaning so that they could be
memorable both to postal workers and to residents. For instance, Manhattan's
ZIP codes start at 10001 and count up-ish. In general, I expected the primary
ZIP code to be more central in a city, and then to count up from there.

Thus, you'd expect there to be more ZIP codes that end in 1 and that ZIP
codes that end in 1 would more likely reflect demographics of the center city.

This repo contains some facts from the ACS about ZIP code tabulation areas
(not ZIP codes). It turns out that, at least nationwide, and at least on the
few variables I pulled out, there's actually less difference in distributions
than I expected!

However, there are definitely more ZIP codes that end in 1, and the
distribution of, say, population by ZIP code does change when you filter to
the last digit. Indeed, several such distributions are multimodal and several
are unimodal.

Still, differences aren't that bad, and in a pinch, randomizing by last ZIP
code digit for a nationwide study might make sense, at least if you account
for overall population differences.
