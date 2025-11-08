# Claude Code Personal Plugin Marketplace

This repository contains custom Claude Code plugins for security, development, and automation workflows.

## Available Plugins

### 🔒 threat-model-assessment

Automate security assessments with AI-powered code analysis against any threat modeling framework or compliance standard.

**Features:**
- Framework-agnostic: Works with OWASP ASVS, CIS Controls, NIST, GDPR, internal policies, or any security framework
- AI-powered codebase analysis with file-level precision
- Iterative assessment of multiple requirements in a single session
- Automated gap analysis and remediation recommendations
- Optional JIRA integration for ticket creation
- Comprehensive markdown assessment reports

**Use Cases:**
- OWASP ASVS security assessments
- CIS Controls compliance verification
- NIST framework implementation reviews
- GDPR Article 30 data processing registers
- Internal security policy audits
- Security architecture reviews

[→ View Plugin Documentation](./threat-model-assessment/README.md)

## Installation

Add the marketplace:

```
/plugin marketplace add rhuss/claude-code-dev-marketplace
```

Install the plugin:

```
/plugin install threat-model-assessment@claude-code-dev-marketplace
```

Invoke the plugin:

```
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
