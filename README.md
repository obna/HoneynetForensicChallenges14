# HoneynetForensicChallenges14
https://www.honeynet.org/challenges/forensic-challenge-14-weird-python/


Ref: https://www.honeynet.org/challenges/forensic-challenge-14-weird-python/
(i) scenarios (why investigate)
Your boss John went to a BYOD conference lately. Yeah, he’s that kind of security guy… After some mumble about targeted attacks happening during the event, your team finally got their hands on a PCAP with his traffic. Your colleague Pete Galloway investigated the incident. Yesterday, he casually mentioned that he found some weird Python bytecode, but couldn’t make much sense out of “random” payloads yet. Today, Pete didn’t come to work. Five minutes ago, he sent a company-wide mail with a total of four words: “Fuck you, I quit.“. What has happened!?

(ii) digital evidence
pcapng, python byte code

(iii) tools
VirtualBox, Wireshark, uncompile 2

Uncompyle 2 is a Python 2.7 byte-code decompiler, written in Python 2.7. It converts Python byte-code back into equivalent Python source code, accepting byte-code from Python version 2.7 only. The generated source code is highly readable
