cereal - A C++11 library for serialization
==========================================

Fork of [USCiLab/cereal](https://github.com/USCiLab/cereal) intended for use with [Rivanna2](https://github.com/solarcaratuva/Rivanna2).

## Changes

### [cereal/types/bitset.hpp](include/cereal/types/bitset.hpp)
- No type information is encoded
- This reduces the size of the serialized output by 1 byte
