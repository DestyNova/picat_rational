## picat-fixedpoint

A tiny library for doing fixed-point (i.e. arbitrary-precision rational) in Picat. I found it handy for at least one Project Euler puzzle requiring many floating point digits.

Operations supported: new_fixedpoint, add, sub, mul, divf, floor_fixed, stringify. Maybe others in future.

I was hoping to override the built-in operators (`+` etc) but it's either not possible in Picat, or I didn't read the manual properly... open an issue / PR if you know how because that would be much nicer.
