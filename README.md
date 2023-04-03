# Diffie-Hellman Key Exchange for 4 Parties (Java)

	The Diffie-Hellman key exchange is a cryptographic protocol that allows multiple parties to establish a shared secret key over an insecure channel. In this README file, we will explain how to implement a four-party Diffie-Hellman key exchange using Java.
  
Algorithm Overview

+	Initialize global parameters (prime number p and generator g).
+	Each party generates a private key (a, b, c, d), and calculates the corresponding public key.
+	The parties exchange their public keys.
+	Each party calculates the shared secret using the public keys of the other parties and their own private key.
+	The shared secret is now established and can be used for secure communication.

