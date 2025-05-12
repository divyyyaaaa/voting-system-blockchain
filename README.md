🗳️ Blockchain Voting System

A decentralized voting system built with Ethereum smart contracts and deployed via Remix IDE.


 ✅ Objective

- Enable secure, transparent, and tamper-proof elections.
- Ensure one-person-one-vote using wallet-based access.
- Allow public verification without relying on a central authority.



 ✅ Features

- Voter authentication by wallet address
- One vote per address enforcement
- Add/view candidates
- Live vote count tracking


✅ Application of Blockchain
 
 Feature                Why It Matters                                              

 Decentralization       Removes single point of control.                            
 Transparency           Public, verifiable vote ledger.                             
 Immutability           Votes can’t be changed or deleted.                          
 One-Vote Logic         Smart contract restricts duplicate voting.                  
 Auditability           Results visible and verifiable in real time.                
 Trustless Environment  Trust is coded into the protocol, not a central authority. 
 

 ✅ Smart Contract File

`voting.sol` – Contains:
- Candidate structure
- `addCandidate()`, `vote()`, and `getVotes()` logic
- `hasVoted` mapping to prevent duplicate votes



 ✅ License

MIT License
