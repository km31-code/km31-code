## Krish Malik

CS + Economics at Georgetown (3.96). Building production systems 
at the intersection of AI infrastructure, autonomous decision-making, 
and data pipelines.

### Work
 
**Alluviam** — Founding Engineer. A Rust/Datalog policy engine that intercepts AI agent tool calls, evaluates them against enterprise access policies, and produces cryptographic audit proofs of every allow/deny decision.
 
**The Petition Co.** — CTO and sole engineer. An OCR-to-voter-match pipeline that reads handwritten government petition sheets against state voter files: 15,000+ documents a week against 10M+ records, in production for paying clients across 14 states.
 
### Projects
 
**[Continuum](https://github.com/km31-code/continuum)** — An intent-native OS layer on Fedora Silverblue. The primary object is a task, not an app or a window. A Rust daemon validates every AI-proposed action against intent-scoped capabilities and executes it through a reversible transaction with a hash-chained receipt, so the model can never cause a side effect directly. The compositor is wlroots, written from scratch in C.

**[Jeff](https://github.com/km31-code/jeff)** — The Continuum thesis on hardware people already own. A Tauri desktop coworker for macOS with workspace awareness, a voice overlay, and proactive task interruption: it watches what you are working on and speaks up when it has something useful, rather than waiting to be opened like an app.
 
**[AMCS](https://github.com/km31-code/amcs)** — An autonomous risk controller that detects market regime shifts and cuts exposure before drawdowns deepen. Deployed on Fly.io and running unattended, with kill switches, loss limits, and a confidence gate that vetoes any action the model is not certain about.
 
**[Expense Heist](https://github.com/km31-code/expense-heist)** — A red-team simulation of a corporate spend policy. A model generates attempts to disguise a purchase past the policy, a two-layer defense judges each one, and anything that gets through is compiled into a deterministic rule the next round has to beat. Builders Cup finalist, Codex track.

### Stack
Python · Rust · TypeScript · Java · C++ · SQL  
Next.js · React · Celery · Tauri · Node.js  
MongoDB · PostgreSQL · Redis · AWS · Docker  
PyTorch · Hugging Face · OCR · Vector Search

[LinkedIn](https://linkedin.com/in/2028krishmalik) · km1897@georgetown.edu
