Inspired by https://netguardia.com/learning-development/tutorials-guides/your-first-ctf-writeup-how-to-document-and-teach-what-you-solved/

# Header 

| | |
|---|---|
| **Platform** | |
| **OS / Category** | |
| **Difficulty** | |
| **Date solved** | |
| **Status** | Retired / Event ended |

## Summary
Two or three lines on the attack chain.

## Reconnaissance 
What you scanned, what you found, and why it mattered.

## Enumeration & Discovery
How you narrowed down the attack surface. The thing you noticed that mattered, and what you ruled out.

## Vulnerability Analysis
Why the bug exists. The class of flaw, the underlying primitive, what makes it exploitable here specifically.

## Exploitation
The payload, the script, the request. Annotated. Show what each piece does and why this construction works.

## Privilege Escalation
For boxes only. Same structure as exploitation but applied to root or admin. Skip if not relevant.

## Lessons & Mitigations
What you learned, what dead-ends you hit, how the bug should have been prevented. The teaching layer.

## References
CVEs, blog posts, docs, tools used. Credit your sources. Link to original research where applicable.
