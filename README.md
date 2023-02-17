# Simple heartrate monitor

Connects to a Bluetooth LE heart rate monitor, receives samples from it, and
plots them in a graph.

This is currently not much more than example code, but it works nicely, thanks
to the excellent [bleak](https://github.com/hbldh/bleak/) library.

## Exaple usage

Find your device address with `hcitool lescan`.

Monitor it with:

```
$ ./heartrate 11:22:33:A1:B2:C3
```


## Why not using a fitness tracker on the mobile phone?

A fitness tracker on a phone is useful, but there are lots of silly things one
can do from one's computer that one can't do from a phone.

A heart rate monitor is, after all, just one more input device: use it as such!

Log your heart rate with your git commits!

Add your heart rate as a header in your emails!

Correlate heart rate information with your work activity tracker to find out
what tasks stress you the most!


## License

> This program is free software: you can redistribute it and/or modify
> it under the terms of the GNU General Public License as published by
> the Free Software Foundation, either version 3 of the License, or
> (at your option) any later version.
>
> This program is distributed in the hope that it will be useful,
> but WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
> GNU General Public License for more details.
>
> You should have received a copy of the GNU General Public License
> along with this program.  If not, see <http://www.gnu.org/licenses/>.


## Author

Enrico Zini <enrico@enricozini.org>

