# TookEffect × CircleCI demo

Disposable public repository for a controlled TookEffect verification trial with CircleCI.

This repository contains no TookEffect product source code, credentials, private configuration, or customer data.

The demo flow is intentionally narrow:

1. CircleCI observes a pull request and its exact head commit SHA.
2. CircleCI (or a tester) submits that claim to the TookEffect Lab trial.
3. TookEffect Core independently reads GitHub as the authoritative provider.
4. TookEffect returns `APPLIED`, `NOT_APPLIED`, or `AMBIGUOUS` with Evidence and a signed Receipt.

The trial is Observe-Only. TookEffect does not merge, close, or otherwise mutate the pull request through this demo.
