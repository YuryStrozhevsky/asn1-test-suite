## Description

In 2012 I wrote my [article](http://www.strozhevsky.com/free_docs/asn1_in_simple_words.pdf) about ASN.1. Right after I finished it I recognized that there are no really free ASN.1:2008 test suites. Because of (IMHO) there are many errors/mistakes/misunderstandings in existing ASN.1 coders/decoders. The test suite I am placing here is intended to be a "helper" for better ASN.1:2008 understanding and further implementation of coders/decoders. As a "test plant" for my test suite I made a freely available [C++ ASN.1:2008 coder/decoder](https://github.com/YuryStrozhevsky/C-plus-plus-ASN.1-2008-coder-decoder). All *.xml files in my test suite are output from my [coder/decoder](https://github.com/YuryStrozhevsky/C-plus-plus-ASN.1-2008-coder-decoder).

## Usage

1. Read "pdf/free_asn1_testsuite.pdf" file
2. Use "suite/*.ber" files for testing decoding functionality;
3. Use "suite/*.xml" file as a suspected output from decoding;
4. With my [coder/decoder](https://github.com/YuryStrozhevsky/C-plus-plus-ASN.1-2008-coder-decoder) you can use "suite/*.xml" files also as an input for testing encoding functionality;

## License

MIT License

Copyright (c) 2014-2018, [Yury Strozhevsky](http://www.strozhevsky.com/)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
