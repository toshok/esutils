esutils ([esutils](http://github.com/Constellation/esutils)) is
utility box for ECMAScript language tools.

### Functions

#### code.isDecimalDigit(code)

Return true if provided code is decimal digit.

#### code.isHexDigit(code)

Return true if provided code is hexadecimal digit.

#### code.isOctalDigit(code)

Return true if provided code is octal digit.

#### code.isWhiteSpace(code)

Return true if provided code is white space. White space characters are formally defined in ECMA262.

#### code.isLineTerminator(code)

Return true if provided code is line terminator. Line terminator characters are formally defined in ECMA262.

#### code.isIdentifierStart(code)

Return true if provided code can be the first character of ECMA262 Identifier. They are formally defined in ECMA262.

#### code.isIdentifierPart(code)

Return true if provided code can be the trailing character of ECMA262 Identifier. They are formally defined in ECMA262.

### keyword

#### keyword.isKeywordES5(id, strict)

Returns `true` if provided identifier string is a Keyword or Future Reserved Word
in ECMA262 edition 5.1. They are formally defined in ECMA262 sections
[7.6.1.1](http://es5.github.io/#x7.6.1.1) and [7.6.1.2](http://es5.github.io/#x7.6.1.2),
respectively. If the `strict` flag is truthy, this function additionally checks whether
`id` is a Keyword or Future Reserved Word under strict mode.

#### keyword.isKeywordES6(id, strict)

Returns `true` if provided identifier string is a Keyword or Future Reserved Word
in ECMA262 edition 6. They are formally defined in ECMA262 sections
[11.6.2.1](https://people.mozilla.org/~jorendorff/es6-draft.html#sec-keywords) and
[11.6.2.2](https://people.mozilla.org/~jorendorff/es6-draft.html#sec-future-reserved-words),
respectively. If the `strict` flag is truthy, this function additionally checks whether
`id` is a Keyword or Future Reserved Word under strict mode.

#### keyword.isReservedWordES5(id, strict)

Returns `true` if provided identifier string is a Reserved Word in ECMA262 edition 5.1.
They are formally defined in ECMA262 section [7.6.1](http://es5.github.io/#x7.6.1).
If the `strict` flag is truthy, this function additionally checks whether `id`
is a Reserved Word under strict mode.

#### keyword.isReservedWordES6(id, strict)

Returns `true` if provided identifier string is a Reserved Word in ECMA262 edition 6.
They are formally defined in ECMA262 section [11.6.2](https://people.mozilla.org/~jorendorff/es6-draft.html#sec-reserved-words).
If the `strict` flag is truthy, this function additionally checks whether `id`
is a Reserved Word under strict mode.

#### keyword.isRestrictedWord(id)

Return true if provided identifier string is one of restricted words under strict mode: "eval" or "arguments".
They are formally defined in ECMA262.

#### keyword.isIdentifierName(id)

Return true if provided identifier string can be IdentifierName.
They are formally defined in ECMA262.

### License

Copyright (C) 2013 [Yusuke Suzuki](http://github.com/Constellation)
 (twitter: [@Constellation](http://twitter.com/Constellation)) and other contributors.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

  * Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.

  * Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL <COPYRIGHT HOLDER> BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF
THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
