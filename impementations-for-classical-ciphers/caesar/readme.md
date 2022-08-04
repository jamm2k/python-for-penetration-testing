Caesar cipher python implementation

caesar.py:
    commands:

        ./caesar.py [plain text (.txt)] [key (number)] [mode (enc/dec)]

        or

        python2 ./caesar.py [plain text (.txt)] [key (number)] [mode (enc/dec)]

    examples:

        python2 ./caesar.py ./caesar-decrypted.txt 18 enc >> encrypted-text.txt
        python2 ./caesar.py ./caesar-encrypted.txt 15 dec

caesar-brute.py:

    commands:
        python2 ./caesar-brute.py [encrypted text (.txt)]

    examples:
        python2 ./caesar-brute.py caesar-decrypted.txt
    