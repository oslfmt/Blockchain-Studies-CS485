# Development Update #1
*January 30th 2022*

## Previously...
Prior to this week, I mostly was getting some paperwork done for setting up the class with Dr. Bindner and figuring out some possible directions I could take. I did do a couple of development related things. A couple of my PRs [here](https://github.com/ethereum/trin/pull/229) and [here](https://github.com/ethereum/trin/pull/84) were merged into Trin (the Portal Net client). At this point, the work I set out to do on the Portal Network has been completed--it is a matter now of if I want to continue contributing to this effort.

I also interviewed with the people @ Acala. Although this did not pan out, as part of my preparation I read a lot about what Acala is and the technology it's built on (Polkadot). This has led to me to explore so-called "3rd generation blockchains", a fascinating topic.

## Updates
This week, I primarily continued my exploration of 3rd generation blockchains. I read overviews on both the Polkadot and Cosmos ecosystems, and experimented a bit with Substrate and the Cosmos SDK, the respective frameworks for each. Here are some resources I used:
- [Polkadot Lightpaper](https://polkadot.network/Polkadot-lightpaper.pdf)
- [Cosmos Primer](https://v1.cosmos.network/intro)
- [Substrate](https://substrate.io/technology/)
- [Cosmos SDK](https://docs.cosmos.network/v0.44/basics/app-anatomy.html)

After gaining a basic understanding of why these technologies are here, and what they enable, I looked into some projects built using Substrate (part of the Polkadot ecosystem). A few caught my eye, but the one that seemed most interesting to me was the [Robonomics](https://robonomics.network/) project. I read an overview of their project, and it seems to me they are trying to build an economic network for robots and other IoT devices, so that robots and IoT can plug into this network and start seamlessly transacting with each other.

## Key Takeaways
Here are the key themes that I took away from this week:

- 3rd Generation blockchains seek to make building an entire blockchain like building a regular application. The difference is that blockchains need to bootstrap a network, so there will be great demand for people to run nodes.
- Interoperability is a huge narrative amongst 3rd gen blockchains. But will 3rd gen blockchains be interoperable amongst themselves?
- 3rd gen blockchains make it easier than ever to build your own blockchain out-of-the-box. But why should someone build a blockchain instead of a regular web app?

Here's an in-depth [writeup](https://hackmd.io/@6RDftSXaRAuyfQjhzN0Abw/HkIUZNVRK) that I did, giving an overview of 3rd gen blockchains.

## Next Week
With a high-level overview of 3rd gen blockchains achieved, I now plan to dig in and start some development. I plan to play around with the Substrate and Cosmos SDK, and get a feel for their capabilities.

In later weeks, I plan to look at some of the projects being built in these ecosystems and what they offer, and potentially delve into how the core technology of Polkadot and Cosmos work.

- Complete the tutorials of the Substrate and Cosmos SDK, and read about their main concepts
- Build a very simple blockchain using the framework I prefer

### Misc.
- I also looked into libp2p, a modular networking framework.
