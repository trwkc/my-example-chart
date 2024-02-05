# Helm Chart 101
This repository is an example of my understanding of creating and upgrading a version of a chart.

### Scenario
- Create Chart (I want to create Phpmyadmin connect to MySql and try to insert data.)
  - Phpmyadmin
  - MySql
- Upgrade Chart (The data must not be lost.)

## How to run
```bash
# Check values
helm install --dry-run --debug my-example .

# Run
helm install --debug my-example .
```
