# SIMPAT-Verification
Verification process is an integral part of the proposed solution. Verification provides the formal check of the system creation possibility in accordance with the requirements and limitations as well as that designed system is secured against an attacker of certain level of knowledge which is connected from certain access point and has certain amount of resources. In the experiments we worked with SPASS theorem prover, the Maude system and daTac. We used these tools to investigate different possibilities to build a cyber-physical system based on available building blocks. For each of this tool we developed appropriate specifications which full descriptions are presented in this GitHub repository.

As a conclusion on the work done, it should be noted that adaptation of the different verification tools for automated composition of the system building blocks is not an easy task and requires a lot of effort. Each verification tool works with its own language and it is not always possible to describe what we want based on their limitations, so we have to develop different hacks. Moreover, some of the available tools, in example - the E theorem prover, require a lot of time effort because of the need to manually input each component description. As one of the possible solutions to this issue, we are currently considering development of a tool that could take information about the system components from the database and convert it into the format of the desired verification tool.
