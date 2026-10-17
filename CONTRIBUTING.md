# Contributing

Read the repository README, working instructions and existing task source before changing anything. Existing project-specific standards and approval rules take precedence over these defaults.

1. Search existing issues and pull requests before opening another. Describe the operating problem, expected result and acceptance checks. Use fictional examples.
2. For repositories that use pull requests, make one focused change on a branch. Follow the repository's release and merge rules.
3. Run the existing deterministic tests and affected module contract checks. Record what passed and what still needs a person to verify.
4. Preserve client-neutral cores, independent modules, versioned interfaces and explicit producer/consumer ownership. Link to an authoritative contract instead of copying it.
5. Update the relevant documentation and existing progress tracker with the change. Record architectural decisions when interfaces or ownership change.
6. Request AI review manually only when useful. Do not add an automatic paid reviewer or repeated review loop. CI tests remain automatic.
7. Keep credentials, personal records, client identifiers and confidential implementations out of public issues, examples and attachments. Use the private security contact for sensitive findings.

A maintainer owns release and deployment decisions. A merged change is not evidence of a successful deployment or operator acceptance.
