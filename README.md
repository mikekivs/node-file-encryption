# Node Files Encryption

An interactive CLI app that can encrypt/decrypt files in a directory using node.

Lib files: [Node Encryption](https://github.com/bbstilson/node-encryption/).

### Usage
Navigate into the nfe folder.

    > cd node-file-encryption
Run nfe.

    > node nfe
On the prompt enter the action you want to perform, specify the directory and password.

    Enter [option directory::password] to proceed (option = encrypt|decrypt)

### Encrypting
    Enter [option directory::password] to proceed (option = encrypt|decrypt)
    > encrypt ../foo::p@ssW0rd
      Encrypt success => ../foo/foo.txt
      Encrypt success => ../foo/bar/bar.txt
      Encrypt success => ../foo/bar/nay/nay.txt


### Decrypting
    Enter [option directory::password] to proceed (option = encrypt|decrypt)
    > decrypt ../foo::p@ssW0rd
      Decryption success => ../foo/foo.txt
      Decryption success => ../foo/bar/bar.txt
      Decryption success => ../foo/bar/nay/nay.txt