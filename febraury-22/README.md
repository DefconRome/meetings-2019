## Transient Execution Attacks explained to your Grandma, by anticlockwise

We will dive into how modern processor optimizations such as branch prediction and out-of-order execution may lead to leak of secrets through the CPU’s microarchitectural state. 
Numerous attacks have been proposed, and we will give an overview of the state of the art of these techniques.

## Foreshadow-VMM: Breaking Virtual Machines Isolation, by marcux_95

On August 14, 2018, a new set of vulnerabilities collectively named "L1 terminal fault" were announced.
Systems with microprocessors utilizing out-of-order execution could allow unauthorized disclosure of information residing in the L1 data cache, by breaking the virtual memory abstraction.
The vulnerability was mentioned for three different scenarios, the most complex one among the three being the "VMM" case of an attacker residing in a Virtual Machine (VM), and targeting information leakage from the host OS and other independent VMs.
In the talk, we will analyze the critical aspects of the attack and discuss a possible solution to replicate the attack.
