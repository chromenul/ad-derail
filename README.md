## ad-derail
A weaponized DNS resolver to enable users to pierce their ad-induced veil while ensuring user data privacy.

### Reasoning

On the internet, anyone and everyone is an adversary. The current cybersecurity marketing constantly
telling us who the adversaries are and how we can protect ourselves from them, it's easy to miss the
biggest adversaries. The ones pointing their fingers. 

The old security model is to isolate, restrict and contain as much as possible. In relation to outbound
internet requests, that model makes it much easier for adversaries to create a unique behaviorial pattern
from your likes and interests. What is this behaviorial pattern used for? It's used to predict future behavior
to present to you the best possible internet experience that will maximize consumption of products,
services and advertising.

Your behaviorial pattern coupled with your likes and interests creates a container that you almost never
leave. You search, view, watch, listen, read, produce and consume an internet experience that is personalized
to your past interaction with the internet. Ultimately you never leave the container you are in because it's
comfortable.

Personalization is another form of containerization.

A lot can be revealed of a persons likes and interests and ultimately behaviors, by the Domain Names their 
system needs to resolve to IP addresses. This data coupled with the rest of your online activity data helps
to build a more complete personal profile.

## How do you break out of the box?

When your system performs a DNS lookup, it sends a DNS Query Message to the DNS server. What constitutes your
data is very fuzzy. Is it the query itself? It surely isn't the Response Message that the server sends to you.
That's the DNS providers data. Where the delineation lies between whats your data and whats their data is
obviously spelled out in a privacy policy. 

Let's assume the query and the response is your data and the provider ensures that it remains private. 
A provider while honoring all of that can create a behaviorial profile based on the responses and work backwards
which would be their data. They spent the server processing power to generate that infered data and ultimately
can do whatever they want with it.

To ensure your privacy and no behaviorial patterns can be produced from your queries, the only real solution is
to query the entire internet. Essentially reversing the old security model to exsolate, destrict and expand.

ad/derail is the first of many tools that will enable users to ensure their privacy. 
