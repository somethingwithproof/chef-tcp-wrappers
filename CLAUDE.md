# CLAUDE.md

DEPRECATED: Chef cookbook for TCP Wrappers access control.

## Stack
- Ruby / Chef 18.0+
- Test Kitchen + Docker/Dokken

## Lint & Test
```bash
cookstyle .
kitchen test
```

## Notes
- Marked deprecated - use firewalld or nftables instead
- TCP Wrappers removed from many modern distributions
- Includes migration guide to firewalld/iptables in README
- Custom resource for managing hosts.allow/hosts.deny rules
