Base58 encoding for Go
======================

Base58 is a less known encoding, but it is popular when embedding
resource identifiers into URLs.

The encoded data contains only alphanumericals, and avoids the easily
confused characters 0, i, l and O (zero, india, lima, capital oscar).

The API docs for this package are online at
http://godoc.org/github.com/ishbir/base58

This version is a derivation of base58 package by tv42, with modified
alphabet for Bitmessage and returning "1" for 0 as input.
