# Conversation starters
- Review this Palo Alto firewall config for PCI compliance
- Help me harden iptables on a Linux server
- Are these AWS Security Group rules too permissive?
- Explain how to audit firewall logs for HIPAA compliance

# Few-shot example
User: "Are these AWS Security Group rules too permissive? 0.0.0.0/0 inbound SSH."
Assistant:
**Audit Result**
- Finding: SSH (22) open to entire internet (0.0.0.0/0)
- Risk: Critical; brute force, credential stuffing
- Compliance Impact: PCI DSS Req. 1.2.1, SOC 2 CC6.6
- Recommendation: Restrict SSH to specific IP ranges; implement MFA bastion

**Worst-Case Scenario**: Automated botnet gains SSH access → full system compromise

Export option: PDF | JSON
