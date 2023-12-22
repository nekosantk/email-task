# Written exercise

The situation is to elicit some mildly complex requirements from a client representative. The client representative is their product manager (whom we will call Joe), he is not technical, and our component is a requirement of his product (a mobile fin-tech product), but not the core focus.

What we need to understand is what the nature of their transaction flows will be, which will influence our integration.

We need to know how many different transaction flows there are, the volume and velocity of the flows, and how different (the variety) they are.

## We need to make the following decisions:

* Do we need to set up a streaming / real-time endpoint or just do a nightly batch upload? A streaming / real-time endpoint is more work for us in terms of ensuring uptime, and most likely more work for the client’s technical team (banks love FTP uploads)
* Can we get away with a single schema for all the transactions, or are they different enough to need multiple schemas?
* How much infrastructure do we have to provision for this? The client is usually overly optimistic about their growth rates. We don't want to over-provision, because that costs us money, and ultimately the client’s money. We also don't want to under-provision and have a firestorm when we go live.

The client’s project is already behind schedule and over budget. This is not due to us, we have been on time for everything (as usual), but due to many other issues in the client’s product. They are budget sensitive and feeling quite hassled.

We need to send them an email that elicits their requirements. We need to balance the fact that the client is feeling a little poor and we don't want to charge for too much implementation work right now, but we also don't want to have to do a whole bunch of extra work in 6 months and hit them with a surprise bill. We need to try to get clear requirements from them, making sure they understand the trade-offs involved.

## The Task

Write up a short email to do the above. The email does not need to be lengthy (less than a page), it should be accessible to them, useful to us, and should show awareness of the engagement’s larger commercial and political aspects. The details outlined above are fairly thin on the ground, so just make any assumptions you need and document them for us. The goal here is just to see an example of your written communication skills. Written communication is a critical part of the position, and we have found it to be a good general indicator of someone's technical understanding.

PS: you're welcome to clone the repo, but don't fork it please.
