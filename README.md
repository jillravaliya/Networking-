# What is Networking ?

The engineering of how two or more independent systems communicate, exchange data, and coordinate actions despite limitations like distance, speed, failures, and security risks.
- We call it “networking” because it’s literally about building a network — a web of connections — that allows these systems to interact.
- -In the real world, no two systems share the same memory or processing space.
- Your laptop’s RAM is physically isolated from a server’s RAM.
- Networking’s first job: bridge that gap.

We’re essentially tricking two machines into acting as if they’re “right next to each other” in a shared world — even though they might be continents apart.

#### Network Independent systems

Two systems:
- Run separate clocks (never perfectly in sync).
- Have different operating systems (Windows, Linux, etc.).
- Use different CPU architectures (x86, ARM).
- Have different local realities (different data, different time zones).
- Networking must normalize these differences so they can still talk.
  

#### Share state

“State” means current knowledge about the world.
Examples:

- In WhatsApp, “you are typing…” is state.
- In a game, your character’s location is state.
- In a stock app, the price of a share is state.

If systems don’t share the same state, they drift apart → chaos.
Networking ensures state synchronization.


#### Exchange constrained messages

Why “constrained”? Because:

- Physics puts a speed limit (light speed, ~300,000 km/s).
- The Earth is big — signal between India and US takes ~200 ms just to travel.
- Bandwidth is limited — can’t send infinite data instantly.
- Data can be lost, duplicated, delayed, or arrive out-of-order.
- Networking protocols are the traffic laws that work within these limits.



## Why Do We Need Networking?

Let’s get brutally honest:
Networking exists because humans want to share & control things without being there physically.
We live in a world where information is valuable only if it reaches the right place quickly. 


#### Before networking:

Data lived on one machine — if you weren’t at that machine, you couldn’t use it.
Communication was physical — paper letters, magnetic tapes, floppy disks (“sneakernet”).
Coordination was slow → weeks or months.

This made distance a barrier to:

- Science collaboration
- Military control
- Business transactions
- Entertainment delivery

#### We needed networking because:

- Speed → Faster than mailing physical media.
- Reach → Talk to anyone, anywhere.
- Scalability → One central server can serve millions.
- Collaboration → Share documents, code, designs instantly.
- Control → Manage remote systems (e.g., satellites, industrial plants).

We live in a world where information is valuable only if it reaches the right place quickly.
- Without networking: You’d have to carry USB drives around to share files.
- With networking: You can email, video call, or stream instantly.

Different systems need to work together even if they’re thousands of kilometers apart.
- A bank’s ATM machine talks to a central bank server in real time.
- Multiplayer games sync player positions in milliseconds.

Not every device has everything, so they share:
- Files (Google Drive)
- Computing power (cloud computing)
- Hardware (printers in offices)

Networking isn’t just about cables and Wi-Fi — it’s the foundation of the modern world:
- Economy → Stock markets update prices globally in milliseconds
- Health → Doctors share scans across continents
- Social → We connect instantly with people anywhere
- Industry → Machines in factories talk to each other for automation

Without networking, the internet wouldn’t exist, and much of daily life would collapse into isolated islands of technology.

