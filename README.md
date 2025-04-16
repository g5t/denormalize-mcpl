# Denormalized MCPL input/output components

Test components for use with `restage` in an attempt to fix its [normalization problem](https://github.com/g5t/restage/issues/11).

Per-ray weights are multiplied by the simulation ray total before saving.

Saved probabilities are divided by the number of rays to be read from their file.
