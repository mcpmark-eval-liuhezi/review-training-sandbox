# Review Checklist

Every checklist item needs an owner before merge.

## Correctness

- The change does what the description says it does.
- Automated tests cover the new behavior.
- No debug logging or commented-out code remains.

## Readability

- Names are descriptive and consistent with the surrounding code.
- Public interfaces have up-to-date documentation.

## Safety

- No secrets or credentials are committed.
- Rollback is possible without manual data surgery.

## Ownership

- Every unresolved thread has been answered by its author.
- The checklist above has been walked through item by item.
