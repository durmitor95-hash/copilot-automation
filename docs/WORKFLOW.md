# GitHub Actions Workflow Objekti

## Workflow za Bug Triage

Ovaj workflow automatski trijaž bugs:

```yaml
- Trigger: Kad se issue labela sa 'bug'
- Akcija: Auto-assign kome treba
- Status: Označava kao 'triage-needed'

- Trigger: Kad se kreira novi PR
- Akcija: Dodaje 'review-needed' labelu
- Status: Postavlja initial review status
