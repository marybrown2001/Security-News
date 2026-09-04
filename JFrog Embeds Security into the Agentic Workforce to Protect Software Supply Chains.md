Liquid software giant JFrog has unveiled new platform capabilities designed to secure and govern the rapidly growing [agentic workforce](https://soc-news.com/jfrog-integrates-security-into-the-agentic-workforce/) security ecosystem across modern software engineering organizations. Unveiled at its annual swampUP conference, the new AgentSecOps framework turns the JFrog Platform into a single source of truth for both human-written and AI-generated software artifacts. The system ensures that autonomous coding agents—operating across environments like Claude Code, Cursor, VS Code, and GitHub Copilot—only consume, execute, and generate policy-compliant binaries and code components.

The technological shift addresses a pressing operational vulnerability created by the rise of agentic AI engineering. While traditional developer tools require human oversight to pull third-party packages, AI agents dynamically source external libraries, Model Context Protocol (MCP) servers, plugins, and AI models at machine speed. Without centralized guardrails, these autonomous agents risk injecting unvetted open-source dependencies, malicious packages, or intellectual property exposures directly into corporate software pipelines before traditional security tools can flag them.

**Introducing Agent Guard and Native Toolchain Interception**
-------------------------------------------------------------

A core component of the expansion is JFrog Agent Guard, a security mechanism that embeds governance policies directly inside developer tools and AI environments. Rather than attempting to scan code after an AI agent has generated it, Agent Guard enforces project-scoped allow and deny rules during the agent's reasoning and execution phases. This prevents coding assistants from bypassing enterprise compliance guidelines or pulling unapproved AI assets into development builds.

Additionally, the introduction of the JFrog Agent Plugin establishes a transparent, direct connection between autonomous agents and the enterprise's central artifact repository. By natively integrating across popular coding assistants, the plugin allows agents to resolve package dependencies automatically through JFrog Artifactory. Every asset pulled by an agent is pre-vetted, authenticated, and audited against corporate security standards, ensuring seamless developer velocity without sacrificing supply chain control.

**Automated Zero-Touch Remediation and Network-Level Defense**
--------------------------------------------------------------

To prevent autonomous coding agents from stalling when encountering vulnerable dependencies, JFrog has introduced Zero-Touch Remediation. Working in tandem with JFrog Curation and Compliant Version Selection, the platform automatically detects policy violations in real-time and swaps out risky packages for secure, verified versions. This self-healing pipeline ensures that AI agents continue building applications continuously while maintaining a pristine security baseline.

For network-level protection, the JFrog Traffic Controller blocks unauthorized public registry calls at the network edge, rerouting all dependency traffic through Artifactory. Developed in collaboration with leading Secure Access Service Edge (SASE) providers including Zscaler, Cloudflare, and Netskope, this network interception layer guarantees that no agent or developer tool can bypass organizational security controls to fetch unvetted components from public repositories.

**Unifying DevSecOps and AI Governance for Future Software Delivery**
---------------------------------------------------------------------

By unifying software artifacts, AI models, and agent-generated code under a single governance structure, JFrog establishes a scalable framework for managing autonomous software development. The platform simplifies audit readiness by automatically generating unified Software Bills of Materials (SBOMs) and AI Bills of Materials (AI-BOMs), giving security teams end-to-end visibility into every component deployed to production.

Yoav Landmann, Chief Technology Officer at JFrog, noted that securing the agentic workforce requires an intrinsic immune layer built directly into the software supply chain system of record. By immunizing what agents consume and controlling how they build and deploy, organizations can harness the speed of AI-driven engineering while maintaining rigorous compliance, security, and operational governance.

[**SOC News**](https://soc-news.com/) provides the latest updates, insights, and trends in cybersecurity and security operations.

Read related news - [https://soc-news.com/knowbe4-wins-key-italian-cybersecurity-accreditation/](https://soc-news.com/knowbe4-wins-key-italian-cybersecurity-accreditation/)
