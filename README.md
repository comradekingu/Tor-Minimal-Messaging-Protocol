### [TOR Minimal Messaging Protocol - TMMP](https://fu3x.github.io/Tor-Minimal-Messaging-Protocol)

#### [Repository](https://github.com/FU3X/TMMP)
#### [Roadmap](https://github.com/users/FU3X/projects/2)

#### About
This is an open source community maintained messaging protocol that routes everything through TOR, end to end encrypted, with the main focus of being incognito. Its completly decenteralized, and each host can have multiple contained rooms with seperate encryption. It will be light and minimal to keep away bugs and vulnerabilities.

#### To get started
```
git clone github.com/FU3X/TMMP
cd Tor-Minimal-Messaging-Protocol/
cargo build --release
cargo run
```

Within the program type:
```
/help
```

#### References
- https://github.com/MagicalBitcoin/libtor
- https://github.com/MagicalBitcoin/libtor-sys
- https://github.com/dgoulet-tor/arti
- https://github.com/torproject/tor
- https://flames-of-code.netlify.app/blog/rust-and-cmake/
- https://github.com/security-softwares/TorChat/blob/main/chat_client.py
- https://jordan-wright.com/blog/2014/10/06/creating-tor-hidden-services-with-python/
- https://www.thepythoncode.com/article/make-a-chat-room-application-in-python

#### Other details
This project will be rewritten in this repository as it faces completion (rewritten up to a few times to improve preformance). Hopefully it will also be rewritten in Rust, and/or an even faster langauge if one comes. If you can take on such task, YOU can be the one to determine that!

The TOR service and the files to run the hidden service will be packaged with each build of this program.

#### If you want to help
Make pull/merge requests to this repository, I will review, test your code, then decide.

#### [More Projects](https://fu3x.github.io)
