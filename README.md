# Daedalus Simulator release packages

## Learning distribution: 1.4.0-learning-r1

This branch is reserved for the Linux x86_64 learning distribution. It is not a competition package and must not be used for competition evaluation.

- Distribution profile: `learning`
- Competition eligible: `false`
- Future truth included: `false`
- Supported maps: Shooting Range and Energy Mechanism
- Online truth: enabled by default and tied to each captured image by producer epoch, frame sequence, and capture timestamp. Set `DAEDALUS_LEARNING_TRUTH=0` to disable it.

The release assets are published under tag `1.4.0-learning-r1-linux`. Competition packages remain on their own tags and are not modified by this branch.
