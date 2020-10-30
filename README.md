As long as I can remember I've been passionate about technology, software in particular.

I started "programming" when I was 8 (`HTML`), when I was 12 I built my first web applications (some in classic `ASP` (not `.net`), others using `PHP`). 

At 14 I hosted my own World of Warcraft private server and built a web application for it where you could design your own items (choose a 3d model, assign stats to the items) you could then use in-game by reverse engineering (looking around in a database, i feel reverse engineering is an overstatement here) how items were stored.

In high school I took the computer science class but didn't have to do the regular assignments, instead I spent the lesson with the system administrators helping them a bit.

I wrote my extended essay on software development (“How to get from an abstract idea to a working application”).

I got offered a job as system administrator by my high school when I graduated, worked there for a year and then started working as a software developer as I still do.

In my spare time I work on personal projects ranging from building web-applications, CLIs, desktop applications, mobile applications and more. 

I also spend a lot of time reverse engineering software.

Whether its implementing a non-trivial behaviour, decompiling and disassembling `jar`s, decompiling `Mach-O` binaries, inspecting network traffic using `wireshark` or proxying traffic through a tool like `nc` (netcat) or `whistle`. If I want something I'll go to the end of the world to find a way or find out its impossible; I'm extremely persistent; not prone to give up. I do tend to recognize when things are technically impossible or not worth the effort.

I have a weakness for:

- Having a deep/thorough understanding of what im dealing with
- Well organized/structured applications
- Modular systems
- Choosing the right level of abstraction
- Systems that delegate most functionality to extensions/plugins
- Automation of any kind, from your typical CI to things like watching the filesystem for changes and processing changes appropriately (e.g. when a `.webloc` or `.url` file is created, extract the URL from it, if its a youtube url use youtube's API to gather metadata, then classify it as music or not music, download the video or audio (depending on the classification))
- Standardization/Specifications (i love documents like [rfc2119](https://www.ietf.org/rfc/rfc2119.txt))
- AI, i like splitting a complex AI task into multiple smaller ones by combining various networks (e.g. using a classification by one network as a feature for another separate network)
- Reverse engineering software (e.g. I cracked an intellij plugin by disassembling a `.class` file in a jar and replacing an inline `base64` encoded public key that was used to verify if the entered license was signed by the correct private key with my own public key so that i could sign my own licenses using my own private key),
Hacking web-applications (to me its like solving a jigsaw puzzle but you don't know what the result should look like and you don't have the pieces but slowly gather them through research)
- Configuration as Code, I wrote a `GitHub Action` that runs a `CRON` job that pulls changes from a `DNS` server and writes them to a `yml` file in the repository, when the `yml` is changed manually it'd sync the changes to the `DNS` server
...more...
