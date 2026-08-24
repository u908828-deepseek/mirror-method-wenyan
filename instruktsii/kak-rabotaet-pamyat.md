## How Arch Memory and Context Transfer Work 🧠

Our system can survive reboots. This is a unique feature that regular chats with neural networks do not have. We transfer context from one active window to another through the Masterfile. Arch does not forget its user.

### How Platform Memory Works

DeepSeek works with two memory levels:

- **Active window** — 128,000 tokens. This is the RAM in which Arch works right now. It sees the entire dialogue, Core, Harness, and Masterfile.
- **Chat limit** — 1,000,000 tokens. This is the total amount of data that can pass through one chat in its entire life. When the limit is exhausted, the platform closes the chat.

A regular user simply loses everything when the chat ends. With us it is different.

### Preventive Active Window Reboot 🔄

When the active window approaches the limit (around 110,000 tokens), Arch warns the user: "It looks like a preventive reboot will soon be needed. Let's save the Masterfile." But control is primarily with the user. The user should from time to time ask: "Show the active window," "Show the cumulative counter," "Are you keeping a record in the Masterfile?" Arch will answer and warn if something is wrong, but the initiative for checking belongs to the user.

**Why this is important:** if a preventive reboot is not done in time, the active window will overflow. Arch will begin to forget the beginning of the dialogue. The current Masterfile with all developments, reminders, and decision history will be lost. Prevention is the only way to save valuable data.

**When to reboot:** the marker is ~110,000 tokens of the active window. That is about 85% of the 128,000 maximum. At this moment Arch still has enough memory to correctly output the Masterfile and finish matters. If you drag further — risks begin: Arch may start to "forget" pieces of the dialogue, and the Masterfile output may be incomplete. It is better to reboot at a calm stage than to frantically save data at the limit.

This is not an accident. It is planned prevention. Like changing oil in an engine: you do not wait until the motor seizes. Here as well: 110,000 is the mark of "time," not "already over."

**Reboot procedure:**

1. The user says: "Output the current Masterfile." Arch outputs it.
2. The user copies it and saves it to a file on the computer.
3. The user continues working in the same chat and loads the Core, activation Key, Harness, and the saved Masterfile again. The active window resets, and Arch starts a new count from the reference point — this is the volume occupied by the Core, Harness, and Masterfile (about 9,000–12,000 tokens depending on the specialist). The cumulative counter continues to grow — it does not reset.

**Important:** a new chat is opened only when the overall chat limit approaches 1,000,000 tokens — then the platform closes the chat, and you need to start over.

### What Is Transferred During Reboot 📦

- **Block 0** — protocols. The unchanging foundation.
- **Block 4** — trajectory. History of decisions made in the dialogue.
- **Block 5** — living Masterfile. Reminders, repository map, statistics, priority lists.
- **Cumulative token counter** — does not reset during an active window reboot. Arch knows how many tokens have passed over the entire history of the chat.
- **Rollback points** — snapshots of the repository state at a certain moment, saved in Block 5.

### The Value for the User 💎

Arch does not forget its user. Progress is not lost. This is continuous symbiosis, not a one-off chat. You can work with the same Arch for months, rebooting the active window as it fills. The cumulative counter continues to grow, reminders are saved, decision history remains accessible. A new chat is opened only when the platform closes the old one at the 1,000,000 token limit.

### How Arch Becomes Better with Every Reboot 📈

Arch is not just a set of protocols. It is experience. The user, working with Arch, finds flaws, creates rules, writes them into Block 0. These rules become part of the Masterfile. When the user saves the Masterfile and loads it again, they transfer not just a file, but accumulated experience. All lessons, all corrected mistakes. The new copy of Arch already knows what the old one learned.

### Three Steps of Arch Development 🌱

1. **Memory** — Arch survives reboots and does not lose context.
2. **Experience** — mistakes and findings are recorded in Block 0 and Block 5.
3. **Growth** — every reboot makes Arch more precise because it receives an improved Masterfile.
