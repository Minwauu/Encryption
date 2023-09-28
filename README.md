# Encryption

## Symmetric and asymmetric encryption

- Encryption is the process of encoding a message so that it can be read only by the sender and the intended recipient.
- Caesar cipher - shift of spaces = key.
- Both types of encryption require keys to be used by both parties and they still ultimately work to decrypt the messages. The differences are that in symmetric encryption, both the sender and receiver share the same private key which is used to encrypt and decrypt the data. However, a key exchange must occur which makes it very vulnerable to interception. In asymmetric encryption, 4 different keys are used. Each device has a pair of keys, a public and private key. Before the message is sent, it is encrypted by the sender using the recipient’s public key which can only be decrypted by the corresponding private key. This makes it more secure than symmetric encryption.
![image](https://github.com/Minwauu/Encryption/assets/110039102/95c83458-fa69-4171-af7e-bfd5cd7b447e)



## Reeves questions answers
 - The key must be sent across a network and is vulnerable to interception
 - A will have a private key known only to A, A will also have a public key, which is mathematically realted to the private key. It is called a public key as anyone can access it. B will also have a private key and a related public key. For A to send a secure message to B, A will first encrypt the message using B's public key. As the private and public keys are related, the message can only be decrypted by using B's private key.As no-one else knows B's private key, even if the message is intercepted, it could not be decrypted.
 - The message being sent has a publicly known hashing algorithm applied to it to create what is known as a hash. The hashing algorithm changes the original data, for example by carrying out modulo arithmetic on the binary equivalents of the original data. 
- A firewall is a method of preventing data from entering onto your computer or LAn from an external computer, you can use two network cards - one that sends and receives data from the external connection and one that sends and receives data from the LAN. Software can be used to examine the contents
- Firewall, proxy server, physical security - e.g locked room, usernames and passwords
- install virus protection software, regularly update virus protection software, remove your computer from external networks.

## PDF page 355 answers

- Symmetric encryption is not considered to be as secure as asymmetric encryption as it requires a key to be exchanged across a network which can make it vulnerable to interception. In asymmetric encryption, there are 4 different keys with a pair given to each party that can't be ecnrypted and decrypted without them. // Encryption uses a key. If both parties know the key the message can be encrypted and then decrypted. However, if someone intercepts the key then they will be able to decrypt the message. Asymmetric encryption gets round this through the use of public and private keys. Private keys remain private and do not need to be known to both parties.
- Each device has a public and private key. The sender's message is encrypted with their public key and it can only be decrypted by the recipient's private key. // 
  A will have a private key known only to A
  A will also have a public key, which is mathematically related to the private key. It is called a public key and anyone can access it.
  B will also have a private key and a related public key.
  For A to send a secure message to B, A will first encrypt the message.
- The message being sent has a publicly known hashing algorithm applied to it to create what is known as a hash. The hashing algorithm changes the original data, for example by carrying out modulo arithmetic on the binary equivalents of the original data. 
- A firewall is a method of preventing data from entering onto your computer or LAN from an external computer.
- 3 measures that a user can take to prevent unauthorised access to computer systems are firewalls/proxy servers, physical security, usernames and passwords.
