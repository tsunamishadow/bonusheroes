# How to win games of Dota in flowcharts.

## Simple 'win the game' tactics:
![alttext][https://mermaidjs.github.io/mermaid-live-editor/#/view/eyJjb2RlIjoiZ3JhcGggVEQ7XG5BW0FtIEkgZG9pbmcgc29tZXRoaW5nIHRoYXQgd2lsbCBhbGxvdyBtZSBvciBteSB0ZWFtIHRvIGRlc3Ryb3kgYW4gZW5lbXkgdG93ZXIsIHJheCBvciB0aHJvbmUgaW4gdGhlIG5lYXIgZnV0dXJlP11cbkEtLVllcy0tPkJbS2VlcCBkb2luZyB0aGF0IHVudGlsIGVuZW15IGZlYXNpYmx5IHN0b3BzIHlvdS5dXG5CLS1UaGUgZW5lbXkgaGFzIHN0b3BwZWQgbWUtLT5DXG5BLS1Oby0tPkNbRG8gc29tZXRoaW5nIGVsc2UuXVxuQy0tPkFcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In19]

```mermaid
graph TD;
A[Am I doing something that will allow me or my team to destroy an enemy tower, rax or throne in the near future?]
A--Yes-->B[Keep doing that until enemy feasibly stops you.]
B--The enemy has stopped me-->C
A--No-->C[Do something else.]
C-->A
```
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
