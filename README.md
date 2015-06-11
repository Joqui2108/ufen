# ufen
The ultimate file encryptor/decryptor tool built in NodeJS.

***

## Usage
To encrypt:

~~~
./encrypt {fileToEncrypt} {password} {outputFile}
~~~


To decrypt:

~~~
./decrypt {fileToDecrypt} {password} {outputFile}
~~~

When decrypting, if password is incorrect, it will generate and empty file.

***

## TODO
* Find some nicer way to decrypt files.
* Being able to output the salt and iv in another file, instead of the encrypted file.
* Add graphical interface.

## KNOWK ISSUES
* Unable to decrypt big files (32 bit limit maybe)
