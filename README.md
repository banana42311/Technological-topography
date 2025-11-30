Hello,

My name is Ji Su Kim, and I am currently studying on the MA Information Experience Design programme at the Royal College of Art in the UK.

I am working on a project that asks the question: “How does technological accessibility form intangible boundaries?”
As part of this research, I am planning to create a network-quality-based technological map of the city (“techno-cartography”) as an experimental case study.

The project aims to visualise the geographic boundaries produced by technological infrastructure and to make these boundaries perceptible to people in their everyday lives.
Participants will reconstruct the network quality of their own locations onto the city map, generating a new kind of topography. Through this, users will be able to sensitively understand the technological strata they belong to, identify points of exclusion based on these metrics, and gain grounds to raise questions about structural inequalities.
To design and implement this, I would like to ask for your expert advice on several points:

1. Which metrics should be collected to represent “network quality” as objectively as possible?

ex) Latency / average ping, Latency jitter (RTT variability), Packet loss, Traceroute / MTR-based routing paths
Hop count, Per-hop RTT, ASN information


I am also considering including additional metrics such as API latency, routing paths, packet loss, and jitter, and visualising different combinations of metrics in different graphical forms.

If there are any established examples or best practices for creating a single composite “network quality score” from multiple indicators, I would be very grateful for references.


2. What would be a realistic methodology for crowdsourcing this data?

The basic interaction I imagine is:

A user opens an app or website

With a single click, their network quality is measured

The measurement data is sent to the server and mapped

I am currently considering two options:

A. Mobile application (iOS / Android)

B. Web-based measurement tool (browser-based)


Implementing measurements such as ping using JavaScript and browser APIs

For example, embedding a “Check network quality at this location” feature directly in a website and sending the results to the backend
In this context, I would like to ask:

To what extent is browser-based measurement of latency/routing technically feasible and reliable?

Are there known limitations or recommended approaches for such a web-based tool?



3. How can we reduce variation and bias in crowdsourced measurements?

Because this is crowdsourced, I am concerned about differences in device types, user behaviour, and measurement environments.

Are there recommended protocols or constraints (e.g. measurement duration, number of pings, target servers, time of day) that can reduce variance?

Are there examples where a measurement protocol is standardised and enforced in a similar crowdsourcing context?

4. What kinds of technical, physical, and ethical risks should I anticipate?

From my initial thinking, some possible risks include:

 1)Cost-related risks
 2) Security / privacy risks
 3) Technical risks
 4) Ethical risks (more broadly)


5. Other technical advice or open-source references

Finally, if you know of:

Relevant open-source projects (e.g. network measurement, crowdsourced speed-test platforms, traceroute visualisation, network cartography, etc.), or

Technical guidelines, libraries, or academic references that would be useful for this kind of project,

I would be very grateful for any recommendations.

Thank you very much for taking the time to read this long message.
Any brief comments, references, or critical feedback would be extremely helpful for developing this project further.

Best regards,
Ji Su Kim
10072613@netwrok.rca.ac.uk
MA Information Experience Design
Royal College of Art, London
