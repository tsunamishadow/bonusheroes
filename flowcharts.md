# How to win games of Dota in flowcharts.

## Simple 'win the game' tactics:
![Graph 1](/images/mermaid-diagram-20180530151138.svg) 

Should I build Hand of Midas?
```mermaid
graph TD;
A("Without sacrificing basic core items (like brown boots) can I get my first use of it before 5:43?")
A--Yes-->B("Go ahead.")
A--No-->C["Are you Invoker, Arc Warden, AA, Phoenix, SB, Treant or Silencer?"]
C--Yes-->D["Can I get my first use before 9:00?"]
D--Yes-->B
C--No-->E["Are you Warlock?"]
E--Yes-->G["Can I get my first use before 16:30 AND before Level 15?"]
E--No-->F("Don't build it.")
G--Yes-->B
D--No-->F
G--No-->F
A--We've lost two towers already-->F
```

What items should I build after core items?
```mermaid
graph TD;
A["Are you winning?"]
A--Losing-->B("Build Damage")
A--Parity-->G["Are you the highest networth on your team?"]
A--Winning-->D["What is your networth ranking (1st to 5th) on your team?"]
G--Yes-->F
G--No-->C
C("Build Damage\Utility")
D--1st or 2nd-->E("Build Survival")
D--3rd or 4th-->F("Build Survival\Utility")
D--5th-->C
```

How do I calculate my Net Worth?
```mermaid
graph TD;
A["Do you have Dota Plus?"]
A--Yes-->B["Top left on your screen underneath your LH/DN"]
A--No-->C["Hover over your gold count and note the Death Loss"]
C-->D["Take that number, multiply it by 40 then take away 2000."]
D--"or"-->E["Take that number, take away 50 then multiply by 40."]
```
> Written with [StackEdit](https://stackedit.io/).
