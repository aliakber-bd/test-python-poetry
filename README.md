# Test Python Project (POETRY)

Tests component locator support for POETRY package manager.

## Vulnerable Dependencies
- `Django==2.2.0` - Multiple CVEs
- `requests==2.20.0` - Known vulnerabilities
- `pyyaml==5.1` - Security issues

## Expected Behavior
When Blackduck Detect runs:
1. Detects POETRY package manager
2. Finds vulnerable components in pyproject.toml
3. Component locator should process (not skip) POETRY manager
4. Locates components in pyproject.toml file
