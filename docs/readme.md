# DIGF5006 - New Interfaces for Musical Expression - OCAD University
## Blog
### Post 1 - May 18, 2018
#### Performer Audience Contract
A most interesting tangent emerged during our first 'sounding' session as part of Adam Tindale's new course New Interfaces for Musical Expression at OCAD University. If that's familiar tituallary, it's an homage to the course's inspiration, NIME – The International Conference on New Interfaces for Musical Expression. It's the first iteration of the course, but Adam's connection to the conference and his depth of experience forecasts an exciting, engaging, and experimental six weeks.

Back to the tangent, in our first experimental listening and performance 'sounding' session, we embarked on a lively debate on the definition of a performance in a musical context. More specifically, we explored the figurative contract a performer has with their audience.

Are there requirements of a performer that qualify them as a performer and the event a performance? If so, what are they?

Does a musician need to perform using their voice or other musical instrument in a performance? If yes, further gradations arise in the variances and possibilities of musical instruments themselves. Electronic instruments are ubiquitous in contemporary performance, but there's a wide range of interactions and engagement with the the apparatus that divides opinion on the validity of the resulting performance. Adam had a great example of the Orb, pushing play at the top of their set and then engaging in a game of chess for the duration of the musical experience. The interesting thing about this example is that no effort was spent trying to deceive the audience as to their on-stage activities or their real-time influence over the music playback. There's an honesty to this that I appreciate and perhaps this is the core of the contract; connect with your audience without embellishing the fundamental nature of your performance. If you’re singing, sing. If you’re turning a knob and grimacing, that knob should be doing something. This is not to say there should be no embellishment as that would make for mundane experiences. However, to suggest a sonic contribution where there is none only serves to create friction between the audience and performer if the deception is revealed.

There are examples where this friction is embraced and exploited as an element of the performance. The KLF was one such act that had a complex and sometimes antagonistic relationship with their audience. One of my favourite clips is their performance as the Timelords on Tops of the Pops, performing their early hit ‘Doctorin’ the Tardis’. The robust performance and mimicry create strong moments of synchresis but it’s obvious to any fan of popular music that the only music other than vocals are samples of the Doctor Who theme and Gary Glitter’s Rock and Roll Part 2. The deceit is playfully revealed when the drummers cease drumming for dramatic effect, but the recorded drum track keeps chugging along.

<iframe width="560" height="315" src="https://www.youtube.com/embed/zKQhB9Z5Jxg?start=49" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>



### Post 2 - May 31, 2018

Taking this thread further, it’s interesting to investigate what legitimizes a musical instruments. As part of the NIME course, each student is reading and presenting on papers from the NIME archive. Each week, we each examine both self-selected paper and a paper at random from a range of years. This past week was 2001 through 2005, the founding years of the conference. It was challenging to source a single entry from the wealth of papers available. Most of the topics warranted further investigation of the abstract. I read half a dozen papers before finally settling on Ge Wang and Perry Cook’s ‘On-the-fly programming: using code as an expressive musical instrument’. What interested me in this paper was the idea of live programming as a musical performance. I had heard about live coding jams where a coder would start a new program from scratch in a performance setting, but I had never considered a musical performance created by code in realtime. Perhaps this is the beauty of continuing education: small but important revelations on what’s possible in different contexts. As an electronic performer myself, I’m well versed in the use of electronic and digital instruments in performance but live code had escaped me. Using digital instruments, one is working with code, but at a higher surface-level connection with pre-coded control over specific parameters. As the paper spells out, this is performing live with a text editor and a live compiler. It’s the latter that really makes this possible, with the authors creating Chuck, a bespoke compiler for live musical coding. The main challenges of their work was creating a modular system that allowed for elements to be added and removed from a live running program. Secondly, this timing of this system must be robust enough to support a musical framework and not lose the beat or hiccup while modifying the existing program. The following is a key passage that illustrates the moment of submitting new code to the compiler for live inclusion into the running program. This is the magic of Chuck

> Add – type-checks and compiles a new shred (from a ChucK
source file, a string containing ChucK code, or a pre-compiled
shred). If there are no compilation errors, the shred is allocated
and sporked in the virtual machine with an unique ID. A new
virtual stack is allocated, and the shred is shreduled immediately
to execute from the beginning. When add fails due to compilation
errors, the virtual machine continues to run as before while the


