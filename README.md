## picat-rational

A tiny library for doing arbitrary-precision rational arithmetic in [Picat](http://picat-lang.org). I found it handy for at least one Project Euler puzzle requiring many floating point digits.

Operations supported: new_rational, add, sub, mul, divf, floor_rational, stringify. Maybe others in future. See `test.pi` for some basic usage examples.

I was hoping to override the built-in operators (`+` etc) but it's either not possible in Picat, or I didn't read the manual properly... open an issue / PR if you know how because that would be much nicer.
