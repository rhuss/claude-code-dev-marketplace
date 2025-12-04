# rhuss' Claude Code Plugin Marketplace

This repository contains custom Claude Code plugins for security, development, and automation workflows.

## Available Plugins

### 🔒 threat-model-assessment

Turn security requirements into actionable code assessments. Provide a threat description and your code repositories, and the plugin analyzes your implementation to identify what's in place and what's missing.

**How it works:**
1. Paste a security requirement from your threat model
2. Specify your code repositories (local or Git URLs)
3. AI analyzes the code to assess current security controls
4. Receive detailed findings with file references and gap analysis
5. Optionally auto-generate JIRA tickets for remediation work

**Perfect for:**
- Architects validating security designs against actual implementation
- Developers ensuring security requirements are properly coded
- Security teams conducting compliance assessments
- Anyone who needs to verify code matches security requirements

[→ View Plugin Documentation](https://github.com/rhuss/cc-threat-model-assessment)

### 📋 superpowers-sdd

Specification-Driven Development with Process Discipline for Claude Code. This plugin extends the superpowers framework with skills and workflows for specification-driven development, ensuring code is built according to well-defined specifications.

**How it works:**
1. Define specifications before writing code
2. Use built-in skills to guide the development process
3. Apply process discipline with quality gates
4. Ensure code matches specifications through structured workflows

**Perfect for:**
- Teams practicing specification-driven development
- Projects requiring formal specification documentation
- Developers who want structured development workflows
- Organizations implementing quality gates in their development process

[→ View Plugin Documentation](https://github.com/rhuss/cc-superpowers-sdd)

### 🎯 slidev

Create developer-focused technical presentations using Slidev with enforced evidence-based design guardrails. Complete workflow from brainstorming to LaTeX handouts.

**How it works:**
1. Initialize presentation with /slidev:init
2. Interactive brainstorming with web research
3. Auto-generate structured outline
4. Create modular slides with enforced quality (≤6 elements, <50 words)
5. Add multi-platform diagrams (Mermaid, PlantUML, Excalidraw)
6. Generate presenter notes and LaTeX handouts
7. Export to PDF/PPTX

**Perfect for:**
- Conference talks and tech meetups
- Internal technical demos and architecture reviews
- Developer training and workshops
- Open source presentations with Git collaboration

[→ View Plugin Documentation](https://github.com/rhuss/cc-slidev)

## Installation

**Step 1:** Add this marketplace to Claude Code:

```
/plugin marketplace add rhuss/cc-rhuss-marketplace
```

**Step 2:** Install any plugin from the marketplace:

```
/plugin install <plugin-name>@cc-rhuss-marketplace
```

**Step 3:** Invoke the plugin using its slash command:

```
/<plugin-name>
```

**Example** (installing threat-model-assessment):
```
/plugin install threat-model-assessment@cc-rhuss-marketplace
/threat-model-assessment
```

## Contributing

This is a personal plugin marketplace, but suggestions and improvements are welcome!

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

MIT License - see individual plugin directories for specific licensing.

## Author

Roland Huß (@rhuss)

## Resources

- [Claude Code Documentation](https://docs.claude.com/claude-code)
- [Plugin Development Guide](https://docs.claude.com/claude-code/plugins)
- [Skill Framework Reference](https://docs.claude.com/claude-code/skills)
