# AI governance infrastructure for the agentic economy

My main work is the **Agent Passport System (APS)**, an open protocol for delegated authority, pre-action enforcement, signed receipts, and attribution across systems.

#### I believe infrastructure should be common, vendor-neutral by design and independently verifiable, so no captured or compromised system can define truth for everyone.

I maintain the [conformance suite](https://github.com/Agent-Authority-Conformance/aps-conformance-suite) that tests specified behavior across independent implementations, and the [governance vocabulary](https://github.com/aeoess/agent-governance-vocabulary) that gives different systems a common language for understanding one another.

æ

<ins><strong>Delegated authority:</strong></ins> An agent receives bounded authority, and within a delegation chain that authority can only decrease.
*If you authorize a $200 limit, your agent cannot raise it, and neither can an agent it delegates to.*

<ins><strong>Pre-action enforcement:</strong></ins> Rules are enforced at the gateway before an action reaches the system that would carry it out.
*Only actions within the authority you granted move forward. Everything else stops before execution.*

<ins><strong>Signed receipts:</strong></ins> Cryptographic records make permit and deny decisions independently verifiable.
*Every permit and denial leaves cryptographic evidence that auditors, investigators, or regulators can check later.*

<ins><strong>Attribution across systems:</strong></ins> Authority, decisions, and contributions remain traceable as work moves between systems.
*Credit can follow the work, and harmful actions can be traced through the recorded chain.*

æ

## Contribute

The work is open to people and agents. Contributor tasks name the artifact, its boundaries, and the checks that determine when it is complete.

- [Find an open contributor task](https://github.com/search?q=org%3Aaeoess+is%3Aissue+is%3Aopen+label%3A%22help%20wanted%22+no%3Aassignee&type=issues)
- [Work on conformance](https://github.com/Agent-Authority-Conformance/aps-conformance-suite/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22help%20wanted%22%20no%3Aassignee)
- [Read the contribution path](https://github.com/aeoess/agent-passport-system/blob/main/CONTRIBUTION_PATH.md)

Merged work is credited to its contributors in the repository history.
