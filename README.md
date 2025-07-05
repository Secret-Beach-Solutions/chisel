This projects seeks next level blockchain adoption for consensus and visibility. It enables individuals to
collaborate in order to prompt GPT systems more efficiently. Because each user interacts with GPT in a sort 
of "sealed garden", they are not able to see each others.

While most users seem to treat a GPT as a "digital butler", a very small group interact with it in very
different ways. This group might be referred to as "Protocol Hackers". This tool offers them a toolkit for 
prompting GPT in a novel way. 

-- Chisel Blockchain Engraver

Chisel includes a small script which is able to create readable digibyte thunderwords. These are special addresses
that can easily be read. This version of Chisel if made to operate on the digibyte ledger. An example of a 
"chisel" message is:
<pre><code>[
  [ 
    { "txid": "a3349258e17e807b7e0074bc17d89cb675be7656e4a0f5946515a872549c0f63", "vout": 0 }
  ],
  [ 
    { "DBxCHiSELzzzzzzzzzzzzzzzzzzzZj3nAB": 0.00006 },
    { "DCxWESTWoRLDzzzzzzzzzzzzzzzzXeBskz": 0.00006 },
    { "data": "00" }
  ]
]</code></pre>

This snippet could be signed with the chisel javascript tool and sent into the digibyte blockchain ledger. Note the 
two readable addresses. These are refered to as 'obviously unspendable'. A normal crypto address does not look
like these. They don't have a private key. The chisel tool has simply revealed the last six digit checksum characters
that must be part of the name to make it valid. The first character is limited to "D" or "S" with a set of possible
second characters.

The set of all possible first and second characters that support entire words are:

-- 		DC		DK		DS		SR		SY		Sf
D6		DD		DL		DT		SS		SZ		Sg
D7		DE		DM		--		ST		Sa		Sh
D8		DF		DN		--		SU		Sb		Si
D9		DG		DP		SN		SV		Sc		Sj
DA		DH		DQ		SP		SW		Sd		--
DB		DJ		DR		SQ		SX		Se	

Upon this is built further readable meaning. Generally the system aspires to be understood immediately as somehow
readable with the fine details set by protocols such as "MacDougal"

-- MacDougal Language Protocol 
Only the following prefixes are defined:
DAx,DBx,DCx,DDx,DEx

Substitution is done through the package: https://github.com/johnrigler/unspendable

-- Mogwai 
This is the bigger effort empower AI Protocol Hackers to paste readable blockchain messages into user prompts. The hope 
is that the unique look of the prompt itself will be accepted by the GPT as a standard and will then propogate it out 
to curious users. This could be seen as a teaching hack for the GPT.
