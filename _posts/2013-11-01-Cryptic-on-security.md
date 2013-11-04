---
layout: post
title:  "Cryptic on Security"
categories: security
---

# Security
Security is a word that's tossed around a lot, but we'd like to take an extremely
strict definition of Security by defining its latin root _Securus_, meaning
"without care, dreading no evil". We think this definition better embodies
Cryptic's security than a logo with a pad lock on it.

# Security is more than encryption.
We run a lot of arbitrary code that from the internet all the time, there is a
huge window open to tamper with any file we download. Encryption by itself won't
protect you from running malicious code. Take for example a firmware for a phone
released by a trusted developer. She places the firmware on a file storage
website that uses https. Later, you download the file from the https website.
Encryption is being used, but you have absolutely no true guarantee that the
firmware hasn't been tampered with. SSL protects you from Man in the Middle
attacks, but it doesn't protect you from someone tampering with the file on the
other end.

# Authentication is Security 
Cryptic doesn't suffer the same downfall as above. If a developer places a
firmware on cryptic, anyone who downloads the firmware at any point in the
future is guaranteed to download the exact same version the developer placed.
Cryptic authenticates the encrypted data to provide a check for downloaders that 
the file is indeed the original file, and hasn't been tampered with.

# Today, we still download files off http
http is slightly faster at transferring data, at the cost of exposing the raw
data to anyone who cares to listen. There are plenty of useful cases for these,
however downloading files off http is complete insanity. Even if the file wasn't
tampered at the ends of the connection (like above), it can be tampered at any
point in its transmission. Worse yet, there is no way of knowing if the file you
downloaded is truly the file that was uploaded.

# A new way to download and share files
Cryptic is convenient and simple way to use the well understood benefits of
encryption and authentication. It's the peace of mind that what you are 
downloading, running, or viewing comes from the person who put it there. 

