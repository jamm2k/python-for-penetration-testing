Vigenere cipher python implementation

    How it works?

        A   B   C   D   E   F   G   H   I   J   K   L   M   N   O   P   Q   R   S   T   U   V   W   X   Y   Z
        0   1   2   3   4   5   6   7   8   9   10  11  12  13  14  15  16  17  18  19  20  21  22  23  24  25

        KEY = SENHA

        S = 18  E = 4   N = 13   H = 7   A = 0

        CRIPTOGRAFIA
        SENHASENHASE

        C + S = 2 + 18 = 20 = U
        R + E = 17 + 4 = 21 = V
        I + N = 8 + 13 = 21 = V
        P + H = 15 + 7 = 22 = W
        T + A = 19 + 0 = 19 = T
        O + S = 14 + 18 = 32 = 26 + 6 = 6 = G
        G + E = 6 + 4 = 10 = K
        R + N = 17 + 13 = 26 + 4 = 4 = E
        A + H = 0 + 7 = H
        F + A = 5 + 0 = F
        I + S = 8 + 18 = 26 = 0 = A
        A + E = 0 + 4 = E

        PLAINTEXT = CRIPTOGRAFIA
        CIPHERTEXT = UVVWTGKEHFAE
        KEY = SENHA

    
    
    vigenere.py:
        commands:

            ./vigenere.py [plain text (.txt)] [key (string)] [mode (enc/dec)]

            or

            python2 ./vigenere.py [plain text/encrypted text (.txt)] [key (string)] [mode (enc/dec)]

        examples:

            python2 ./vigenere.py ./vigenere-decrypted.txt testesenha enc >> encrypted-text-testesenha.txt
            python2 ./vigenere.py ./vigenere-encrypted-testesenha.txt testesenha dec