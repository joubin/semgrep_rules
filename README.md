# semgrep_rules

This is my personal code review repository. 

To run each rule

```bash
semgrep --config {rule}.yml --include '*/**/*.yaml' --include '*/**/*.yml' --include '*/**/*.java' --include '*/**/*.tf' --include '*/**/*.py' --include '*/**/*.sh' --exclude '*/.git/*' --output semgrep-crypto-results.json --json
```