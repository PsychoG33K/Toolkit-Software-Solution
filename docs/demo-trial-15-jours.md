# Demo / Trial 15 Jours

## Principle

The public ZIP does not include `license.json`.

At first launch, the product starts in locked mode and displays the machine code/hash required to request a trial licence.

## Flow

1. Client downloads the official ZIP from the controlled channel.
2. Client extracts the ZIP locally.
3. Client launches the application without `license.json`.
4. The application displays the licence request information and machine hash.
5. Client sends the hash to Toolkit Software Solution.
6. Toolkit Software Solution generates a Trial licence, usually valid for 15 days.
7. Client receives `license.json` separately.
8. Client places `license.json` next to the application executable.
9. The application unlocks according to the licence features and expiry date.

## Offline Trial Limitation

In V1, trial validation is offline. A strongly motivated user may attempt to manipulate the system clock, but an incorrect system clock may also break HTTPS, certificate validation or external AI/API services.

A future version may add local anti-rollback checks and/or server-side activation.
