
https://anders.unix.se/2015/10/26/interview-with-dennis-ritchie-2003/
http://doc.cat-v.org/bell_labs/utah2000/utah2000.pdf "Systems Software Research is Irrelevant" - Rob Pike - Bell Labs Feb 21, 2000

"Do you agree with Rob Pike’s thoughts on the (ir)relevance of systems research? (http://cm.bell-labs.com/who/rob/utah2000.ps)

Pretty much, although Rob was stating his case in a deliberately provocative way. It’s true that compared with the scene when Unix started, today the ecological niches are fairly full, and fresh new OS ideas are harder to come by, or at least to propagate."

---


Inferno® is a distributed operating system, originally developed at Bell Labs, but now developed and maintained by Vita Nuova® as Free Software.  Applications written in Inferno's concurrent programming language, Limbo, are compiled to its portable virtual machine code (Dis), to run anywhere on a network in the portable environment that Inferno provides.  Unusually, that environment looks and acts like a complete operating system.

Inferno represents services and resources in a file-like name hierarchy.  Programs access them using only the file operations open, read/write, and close.  `Files' are not just stored data, but represent devices, network and protocol interfaces, dynamic data sources, and services.  The approach unifies and provides basic naming, structuring, and access control mechanisms for all system resources.  A single file-service protocol (the same as Plan 9's 9P) makes all those resources available for import or export throughout the network in a uniform way, independent of location. An application simply attaches the resources it needs to its own per-process name hierarchy ('name space').

Inferno can run 'native' on various ARM, PowerPC, SPARC and x86 platforms but also 'hosted', under an existing operating system (including AIX, FreeBSD, IRIX, Linux, MacOS X, Plan 9, and Solaris), again on various processor types.

This Bitbucket project includes source for the basic applications, Inferno itself (hosted and native), all supporting software, including the native compiler suite, essential executables and supporting files.
