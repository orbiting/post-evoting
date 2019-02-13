# post-evoting

#### Deutsch

Die [Post](https://www.post.ch/de/geschaeftlich/themen-a-z/branchenloesungen/e-voting-loesung-der-post/e-voting-quellcode) hat den Source Code ihrer E-Voting-Plattform [in einem privaten GitLab-Repository](https://gitlab.com/swisspost/evoting-solution) zur Verfügung gestellt. 

Leider ist die Dokumentation zu Kompilierung und Deployment sehr mager. Deshalb sammelt das Magazin [Republik](https://www.republik.ch) hier Patches, damit man das System «untersuchen, verändern, kompilieren und ausführen» kann – so wie es die 
[Verordnung der Bundeskanzlei über die elektronische Stimmabgabe (VEleS)](https://www.admin.ch/opc/de/classified-compilation/20132343/index.html#a7b) verlangt.

#### English

The [Swiss Post](https://www.post.ch/en/business/a-z-of-subjects/industry-solutions/swiss-post-e-voting/e-voting-source-code) has released the source code of its e-voting platform as a [private, registration-required repository on GitLab](https://gitlab.com/swisspost/evoting-solution). Here, the magazine [Republik](https://www.republik.ch) collects patches to “examine, modify, compile and execute” the system, in accordance with the [Federal Chancellery Ordinance on Electronic Voting (VEleS)](https://www.admin.ch/opc/en/classified-compilation/20132343/index.html#a7b). 

## Getting started

 1. Read the [intro](https://www.post.ch/en/business/a-z-of-subjects/industry-solutions/swiss-post-e-voting/e-voting-source-code)
 1. [Register](https://www.evoting.ch/sourcecode/ui/home?lang=en) to gain access to the private repository
 1. `git clone https://gitlab.com/swisspost/evoting-solution.git`
 1. `git clone https://github.com/orbiting/post-evoting`
 1. `cd evoting-solution && git apply ../post-evoting/getting-started.patch`
 
## Contributing

Pull requests to facilitate the build and deployment process are welcome!