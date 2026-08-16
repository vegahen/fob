# vegahen/fob

*Copyright (c) 2026 vegahen*

I don't know if we have reached any consensus as to which quantum secure PKI we should use, but since the fobs and readers need to be free and open-source configurable anyways, we might as well start out with RSA to avoid a bunch of nerds fighting a war over which algorithm is the best one. Whenever proton.me decides which one to use, that is good enough for me.

I myself would like to have three private keys on my fob:

- One anonymous key signed by Signal
- One personal key signed by the Norwegian authorities
- One work key signed by my employer

but there should be no limit to how many key pairs you can create.

You need to pay the respective certificate authority to sign your key, but being Norwegian I suspect that our very own Big Brother is happy to do so for free as long as we behave ourselves. I'm not so sure about X, Facebook, Instagram, WhatsApp, and TikTok however.

Signal needs to make money for their servers anyways, so I will happily pay them for a couple of signatures. I don't know how they are going to verify that I am a human, but that is not my task to decide anyways.

The mobile app is called fob, obviously. But I don't like carrying my phone around with me everywhere I go. And think of the old people.

That's why I didn't mention the mobile app until now.

## Versions

I am writing this from my friend's apartment. They put their keys in the mailbox, which is an elegant solution for people who are not paranoid. It doesn't scale well, though.

When I need to rent an apartment from someone who does not trust me, I simply send them my public key on Signal or wherever, and they can verify it with the respective certificate authority, look up some previous reviews if we figure out how to do that fairly and keep the data stored for a voluntary/configurable time period (I would maybe pick one or two years for myself so that my personality is given room to change without being haunted by any potential future previous mistakes) in a distributed database without any servers in some datacenter.

Or maybe we could just see how many followers that person has on GitHub or some other kinds of empathic networking criteria. Poeple on GitHub tend to be trustworthy. So far.

Or maybe we could just judge them by their Git bio, on whatever static IPv6 address they choose to host it? [This is my bio](https://github.com/vegahen/life), by the way.
