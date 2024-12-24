---
layout: post
title: "Distributed Systems and the art of Open Office Survival"
date: 2024-12-24
---

Sometimes, I feel like my office is a distributed system — not the kind that’s covered in textbooks like ``Introduction to Reliable and Secure Distributed Programming," but the kind where noise is the only reliable broadcast primitive.

Picture this: four people sharing a cozy little space with a lovely view of Leuven, Belgium. It’s not a library, but it’s not quite a free-for-all cafeteria either. It’s an "open office" in every sense of the term—open to brainstorming sessions, open to heated debates about the latest zero-knowledge virtual machines, and very open to my focus flying out the window.

The other day, I sat down with noble intentions. I’d cracked open a book — yes, a physical book—on distributed systems. I was ready to revise my knowledge about broadcast primitives: reliable broadcast, uniform reliable broadcast, and something called “flooding.” (Spoiler: flooding works for both data packets and conversations.) I’d made it two paragraphs in when the first impromptu seminar began. This time, it was about ``the worst code" someone had ever seen — complete with reenactments and dramatic pauses. 

``They named the variable 'x' in a thousand-line function," one of them lamented, ``and then wondered why nobody could debug it." 

It’s not that I don’t enjoy these moments. Who doesn’t love hearing about bugs so terrifying they’d make Kafka blush? But when you’re trying to understand the nuances of Byzantine Reliable Broadcast and all you can hear is a hot take on suboptimal naming conventions, it’s… distracting.

And then it hit me: what if I applied the concepts of broadcast primitives to office life? Maybe I needed a reliable broadcast mechanism to ensure my cries for quiet reached all the right nodes. Or a uniform reliable broadcast to make sure everyone agreed to the silence — and stuck to it.

Of course, in reality, my office runs on a more chaotic protocol. There’s a lot of asynchronous communication (someone’s always talking over someone else), gossip dissemination (yes, even research chatter qualifies), and no leader election — because everyone’s convinced they’re the main character.

The book was right about one thing: distributed systems are hard to design. But at least in my office, the system is surprisingly… robust. Somehow, ideas are shared, problems are solved, and nobody has been deadlocked at the coffee machine. Yet.

As for me? I’m still figuring out how to focus amidst the noise. Maybe I just need to multicast a request for peace — or invest in noise-cancelling headphones and call it my personal leader election. Maybe next time I’ll try a timeout—or just embrace the chaos and join the next brainstorming session. Please email me if you have better suggestions! 

