# DES in Laminar Performance Debugging

Test results will be written on commit logs.

## Testing Environment
- Input of seed.txt : 3
- Number of repetitions : 1000000
- Expected output : 119991455
- Machine : ELC1 (Xeon E5405)

## Conventions

### General

- Two spaces indentation (Except on static variables.)
- Comments in `//!**` indicate that it was added in translation.

### Variables

- input : `x`
- copy of input (for array access etc.) : `w`
- output : `y`
- copy of output (for array access etc.) : `z`
- random seed : `seed`
- sum : `sum`

### Naming

- Actors : Following the StreamIt diagram notation.
- Splitjoins : `__split_<StreamItSplitJoinName>`, `__join_<StreamItSplitJoinName>` respectively.
