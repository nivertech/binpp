binpp - Erlang Binary Pretty Printer
===================================

Example usage:

    1> Bin.
    <<12,242,207,49,82,69,45,130,212,69,80,88,8,81,23,36,86,7,
      68,19,133,97,51,216,56,145,88,8,81,...>>
    2> binpp:pprint(Bin).
    0C F2 CF 31 52 45 2D 82 D4 45 50 58 08 51 17 24  .òÏ1RE-ÔEPX.Q.$
    56 07 44 13 85 61 33 D8 38 91 58 08 51 17 24 56  V.D.a3Ø8X.Q.$V
    0A 14 20 4E 24 16 09 60 F4 0A 15 11 01 30 13 89  .. N$..`ô....0.
    05 81 0F 09 15 C5 61 33 D8 54 91 52 5D 81 17 24  ....Åa3ØTR].$
    11 14 60 23 D1 3D 55 80                          ..`#Ñ=U
    ok
    3> binpp:format(Bin, bin).
    "00001100 11110010 11001111 00110001 01010010 01000101 00101101 10000010
     11010100 01000101 01010000 01011000 00001000 01010001 00010111 00100100
     01010110 00000111 01000100 00010011 10000101 01100001 00110011 11011000
     00111000 10010001 01011000 00001000 01010001 00010111 00100100 01010110
     00001010 00010100 00100000 01001110 00100100 00010110 00001001 01100000
     11110100 00001010 00010101 00010001 00000001 00110000 00010011 10001001
     00000101 10000001 00001111 00001001 00010101 11000101 01100001 00110011
     11011000 01010100 10010001 01010010 01011101 10000001 00010111 00100100
     00010001 00010100 01100000 00100011 11010001 00111101 01010101 10000000"

That's all folks!
