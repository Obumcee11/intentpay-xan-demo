IntentPay – Private, Multi-chain Payments with Anoma

🔮 OVERVIEW
IntentPay is a prototype of an **intent-centric global payments app** powered by Anoma.  

Instead of dealing with chains, bridges, or wrapped tokens, users simply declare their intent:

> “Send 100 $XAN privately to Bob on Polygon.”

Anoma’s intent architecture resolves and routes the payment automatically.  

---

✨ Features
*Daily faucet* > demo users get 10,000 $XAN + 5,000 testUSDC.  
*Payment intents* > “Send X to Y” with optional conditions (amount, chain, privacy).  
*Privacy mode* > zk-proof toggle for sender/receiver data protection.  
*Multi-chain support* > auto-routes across Ethereum, Polygon, Cosmos, and more.  
*Solver simulation* > matches intents across networks and executes them.  

---

🧪 Example Flow
1. Alice claims faucet → receives 10,000 $XAN + 5,000 testUSDC.  
2. Alice submits an intent → “Send 250 $XAN to Bob on Polygon, private.”  
3. Solver finds the best route (swap $XAN → stablecoin if needed, bridge, then deliver).  
4. Bob receives 250 $XAN on Polygon.  
5. Both see confirmation — no bridges, no wrapping, no friction.  

---

 🛠 Tech Stack
*Frontend*: React (payment intent UI with privacy toggle).  
*Backend*: Node.js, Express (intent submission + solver logic).  
*Solver Engine*: mock auto-matcher, expandable into a full Anoma solver.  
*Database*: in-memory (upgrade path → Postgres for persistence).  

---

📦 Roadmap
- Add direct Anoma testnet integration.  
- Support **composable intents** (pay + swap + donate in one action).  
- Mobile-first UI for peer-to-peer payments.  
- Add NFT badges + leaderboard for active $XAN senders.  
- Integrate real-world stablecoins for hybrid payments ($XAN + USDC).  

---

⚡ Vision
IntentPay is a simple demo to show how **$XAN can power private, global, and frictionless payments** in an intent-centric economy.  

By moving beyond transactions into **intents**, we create a UX where money finally works like magic.  

---

🤝 Contribution
This repo is for **Anoma Intents Tuesday: Redux**.  
Forks, experiments, and design feedback are welcome.  
