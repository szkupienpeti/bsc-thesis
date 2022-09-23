# Generating Real-Time Tests from Timed Behavioral Models
My BSc thesis in the field of Computer Science Engineering at Budapest University of Technology and Economics ([BME](https://www.bme.hu/?language=en) [VIK](https://vik.bme.hu/en/) [MIT](https://www.mit.bme.hu/eng/) [ftsrg](https://ftsrg.mit.bme.hu/en/)) under the supervision of [Vince Molnár, PhD](https://inf.mit.bme.hu/members/molnarv). The thesis is written in Hungarian (original title: *Valós idejű tesztek generálása időzített viselkedésmodellekből*).

## Abstarct
Nowadays almost all safety critical systems are controlled by software which must operate correctly under all circumstances, otherwise we face unforeseeable consequences. Formalizing the system and its requirements is an essential base of proving correctness. Although formal methods are used more and more often in order to prove the correctness of systems, they do not, on their own, replace running certain test cases.

It is a general expectation towards test sets that they cover as many use cases as possible, which can be achieved by model-based test generation—generating test cases by traversing the behavioral model of the system instead of defining them manually. For timed systems, however, test generation becomes more complex as it is not enough to define a state sequence of the system but timing also has to be mapped to transitions to obtain a real-time test case.

In this thesis, the basics of model checking, theory of timed behavioral models, as well as applicable abstractions of timed automata and the SMT problem are presented. The concepts and expectations of real-time tests are formalized and an algorithm is presented which, using an abstract model of the system, generates a test set covering every available location of the system. The timing of the abstract test cases obtained from the traversal of the abstract model is reduced to SMT problems.

The relevant parts of the model checking framework Theta are also presented and the algorithm is implemented as their extension. Finally, the algorithm is discussed in detail through a case study and measurements.

---
Based on the [LaTeX thesis template](https://github.com/ftsrg/thesis-template-latex) of [ftsrg](https://ftsrg.mit.bme.hu/en/).
