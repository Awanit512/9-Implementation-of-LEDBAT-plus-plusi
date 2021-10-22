# 9-Implementation-of-LEDBAT-plus-plusi
Brief: Low Extra Delay Background Transport (LEDBAT) is a popular Less than Best Effort
(LBE) TCP which Apple uses for its iOS updates and by BitTorrent applications. Recently,
there have been a few enhancements to LEDBAT, and one of the resulting algorithms has
been named LEDBAT++. It is a part of the Windows operating system. This project aims to
implement a model of LEDBAT++ in ns-3. LEDBAT is already implemented in ns-3 and is
available in the mainline.
Required experience: C and C++
Bonus experience: Knowledge of RTT and RTO calculations in TCP
Difficulty: Moderate
Recommended Reading:
● TCP examples of ns-3 (Path: ns-3.xx/examples/tcp/)
● ns-3 code for LEDBAT (Path: ns-3.xx/src/internet/model/tcp-ledbat{.h, .cc})
● LEDBAT: RFC 6817 (https://tools.ietf.org/html/rfc6817)
● LEDBAT++: Internet Draft (https://tools.ietf.org/html/draft-irtf-iccrg-ledbat-plus-plus-01)
