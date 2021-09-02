# Some Pseudo-Random Notes

# Contents
* [Compiler Construction and Models of Computation](#ccmc)
* [Alan Turing and Turing Machine](#at)
* [The Imitation Game](#tig)

<h2 id = "ccmc"> Compiler Construction and Models of Computation </h2>

*"Computation is all about language."* <br/>

*"Compilation is computation, nothing more or less"* <br/>

Finite State Machine, Context Free Grammar, Pushdown Automata, Turing Machine- these are different models of computation. These are mathematical and in most cases theoretical in nature. But many of them can be constructed for different purposes or at least simulated. [This DFA](https://github.com/NA-Shuvo/CD_testing/blob/master/Compiler%20Design/Documentation_DFA.md) class is a very simple program that simulates simple deterministic finite automata. These models are at the very centre of the modern computer science. They give theoretical bases and constrains on the limit of computation in terms of capacity.<br/>

Models of computation are reviewed in Compiler Construction course though they are the elements of Theory of Computation studies. The reviewing is not irrelevant. Because Compiler Construction is largely dependent on theories of computation, in fact compilation is computation. All the above mentioned models perform linguistic computations, process some strings and linguistic instructions,  so does the compiler. Some of the computational models like DFA, CFG have some direct implication on the construction of compilers. DFA is used in the construction of lexical analyzer which converts the string in input program to tokens of the prigramming language. Parsers can be represented concisely as various kinds of automata. <br/>

<h2 id = "at"> Alan Turing and Turing Machine </h2>

<img src="https://github.com/NA-Shuvo/Writings/blob/main/Images/50-pounds-1.png" alt="Alan Turing in bank note"/>
<br/>

*"Beyond any doubt, the most important thing that has happened in cognitive science was Turing’s invention of the notion of mechanical rationality." - Jerry Alan Fodor* <br/>

*"Turing Machines are a terrible model for thinking about first computation;..." - Jeff Erickson* <br/>

Alan Mathison Turing (23 June 1912 – 7 June 1954) was an British mathematician and is considered as the father of modern theoritical computer science. To non-science background people he was almost nobody and American historical drama film "The Imitation Game" made him world wide popular figure in 2014 but introduced him as a World War II hero whose contribution ended the war within two years and directed the whole biopic to somewhat different image of him. <br/>

Alan Turing is great mainly because of his two important papers. 

*   [1] [On Computable Numbers, with an Application to the Entscheidungsproblem (1936)](https://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf)
*   [2] [Computing Machinery and Intelligence (1950)](https://academic.oup.com/mind/article/LIX/236/433/986238)

In [1] Turing provided a model of computation which is called Turing Machine. It can be considered as a model of general purpose computer. But our digital computer is not a complete Turing Machine. Turing machines are equivalent to modern electronic computers at some certain theoretical level, but differ in many details. This model is still regarded as one of the most important theoretical foundations of today's modern computer.<br/>

But Turing discusses many other very important things in this paper. He tried to define computing machines. He outlined a proof to the Hilbert and Akkerman famous decision problem known as Entscheidungsproblem. What is this? This asks for an alogorithm to decide whether a given statement of first order logic is true. Turing's paper provided a negative solution- no such algorith exists. Although Turing didn't know at his time that he was not the first man who provided a solution to this problem. It was Kurt Godel. The first implicit proof was in his work on "incompleteness theorem". Turing even was not the second man. The first published proof was by Alonzo Church. Church used completely different model of computation which is called untyped λ-calculus. There were more on the paper. He provided a description of a single universal machine  that can be used to compute any function computable by any other Turing machine. ... <br/>

Let's get back to Alan Turing. Turing died in 1954, 16 days before his 42nd birthday. The probable cause of his death was suicide by cyanide poisoning. The highest award in computer science is named after him- "ACM A M Turing Award" which is often referred to as the "Nobel Prize of Computing" (Though I don't know why people do this unnecessary referring? What a crap!). <br/>

Alan Turing has recently honored on new UK 50-pound bank note. The bank note is formally issued to the public on June 23, 2021, Turing's 109th birthday.

<h2 id = "tig"> The Imitation Game </h2>

*"Can machines think?" - Alan Turing* <br/>

*"We can only see a short distance ahead, but we can see plenty there that needs to be done" - Alan Turing*<br/>

But Alan Turing was not only the father of modern theoretical computer science. He was also the father of Artificial Intelligence. The second paper [2] was published in 1950 in Mind – A Quarterly Review of Psychology and Philosophy which is still one of the remarkable papers on Artificial Intelligence. Here Turing introduced a test which now known as Turing Test but Alan Turing himself called it "The Imitation Game". <br/>

[2] is an very interesting paper. It's elements and style of writing crosses the boundary of science and shows Turing's high level of linguistic capacity. It is easy going and enjoyable to read. Here, Turing expressed his thoughts on the philosophy of Artificial Intelligence.  <br/>

In this paper Turing acknowldged that there was no universal definition of machine. And there was no universal definition of thinking. So, can machine think is not a valid question at all. Turing rephrased new question that was -"can machine imitate human being?" He modeled a game like test. This game tests a machines's ability to exhibit intelligent behavior equivalent to, or indistinguishable from, that of a human being. <br/>

Not all mathematical mind is revolutionary. Alan Turing was revolutionary. He specified nine objections raised against Artificial Intelligence at the time of his writing of the paper and he argued! Those nine objections are listed bellow. Students are requested to search and read those arguments.

*   Religious Objection.
*   'Heads in the Sand' Objection.
*   The Mathematical Objection.
*   Argument From Consciousness.
*   Arguments from various disabilities.
*   Lady Lovelace's Objection.
*   Argument from continuity in the nervous system.
*   Argument from the informality of behaviour.
*   Extra-sensory perception.

The paper consists of seven sections numbered from 1 to 7 with a bibliography. In the final section of his paper, Turing wrote his idea of learning machines that could successfully play the imitation game. 
