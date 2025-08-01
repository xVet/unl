# UNL

This directory contains the data for the UNL (Unique Node List) of the XRPL (XRP Ledger).

## Example Source File

We use a YAML file to define the list of validators using the following format:

```yaml
nodes:
  - id: nHBgyVGAEhgU6GoEqoriKmkNBjzhy6WJhX9Z7cZ71yJbv28dzvVN
    name: v2.xrpl-commons.org
  - id: nHU4bLE3EmSqNwfL4AP1UZeTNPrSPPP6FXLKXo2uqfHuvBQxDVKd
    name: ripple.com
```

The `id` field is the public key of the validator, and the `name` field is a human-readable name for the validator. Only the `id` field is required, but it is recommended to include the `name` field for clarity.

## Editing the UNL

To suggest an update to this list, make a Pull Request. If approved, the next build of the UNL will include these changes.

