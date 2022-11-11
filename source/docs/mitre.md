# MITRE

MITRE is a government-funded organization that puts out standards to be used by the information security community.

## CWE and CVE

Two of the most popular of these are CWE and CVE, and they’re often confused by security practitioners. Here’s the simple distinction:

* [Common Weakness Enumeration (CWE)](https://cwe.mitre.org/) has to do with the vulnerability—not the instance within a product or system.
* [Common Vulnerabilities and Exposures (CVE)](https://www.cve.org/) has to do with the specific instance within a product or system—not the underlying flaw.

## CAPEC

The [Common Attack Pattern and Enumeration Classification (CAPEC)](https://capec.mitre.org/) site is an information
resource that identifies and documents attack patterns. It also provides information on mitigation techniques
for the attacks.

## MITRE ATT&CK

MITRE ATT&CK is a knowledge base of tactics and techniques used by adversaries (threat actors, attackers) to compromise
systems, created from a survey of publicly reported attacker activities. MITRE does not include every possible method
of attack, only those that have been publicly disclosed as actions observed by an advanced persistent threat (APT) as
defined by larger agencies. There will be some cases, especially in advanced attack scenarios, where
actions are not included in ATT&CK. For example, for an application-based attack. For those, check out
[OWASP]({{< relref "owasp" >}})

The goal of MITRE ATT&CK is to use the information collected and presented in the standard as a basis for
[threat modelling and analysis](https://tymyrddin.github.io/threat-models/).

On the [MITRE ATT&CK website](https://attack.mitre.org/), choose a threat, read the details about the threat, and how
the threat can be detected and mitigated.

## Caldera

MITRE is also developing [Caldera](https://caldera.mitre.org/), a C2 useful for getting started with pentesting. It contains several "Capture the Flag" tutorials.
