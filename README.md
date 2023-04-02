# Reentrancy-attack
<br>
Q1) What is a reentrancy attack?
<br>
<p>
A reentrancy attack is an exploit that takes advantage of a computer program or smart contract
vulnerability. It allows an attacker to execute malicious code multiple times before the original
function has been completed, potentially causing damage to the program or allowing the attacker
to steal resources or data.
</p>


<br>
Q2) What happens in it?
<br>
<p>
In a reentrancy attack, an attacker exploits a vulnerability in the smart contract code that
allows them to call the same function repeatedly before it has finished executing. In a
reentrancy attack, an attacker exploits a vulnerability in the smart contract code that allows
them to call the same function repeatedly before it has finished executing. It allows an
attacker to execute malicious code multiple times before the original function has been
completed, potentially causing damage to the program or allowing the attacker to steal
resources or data.
</p>

<br>
3) How it occurs?<br>
<p>
• One way that reentrancy attacks can be carried out is through the use of recursive calls. When a
smart contract function calls another function, it may be possible for the second function to call
the first function again before the first function has finished executing. If this happens, the second
function can execute malicious code before the first function has a chance to complete.
<br>
• Another way that reentrancy attacks can be carried out is through the use of external calls.
When a smart contract calls an external contract or function, it may be possible for the
external contract or function to call the original contract again before the original contract
has finished executing. This can create a loop that allows the attacker to repeatedly execute
malicious code.
</p>

<br>
4) How to prevent it?
<br>
<p>
• To prevent reentrancy attacks, it is important for developers to carefully review their code and
identify any vulnerabilities. One way to do this is through the use of automated tools that can
detect potential weaknesses in the code. Additionally, developers should avoid using external calls
whenever possible and should carefully manage the flow of control within their smart contracts.
Another way is to use mutex.
</p>

