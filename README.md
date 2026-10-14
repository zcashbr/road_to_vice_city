# Road to Vice City — Official Draws & Verification

Public, verifiable, and immutable record of the **Road to Vice City** giveaways hosted by LiveZEC. Each draw keeps its own frozen record — rules, entry list, published hash, and result — so anyone can independently verify the outcome.

## 📜 Draws

| # | Period | Max entries/user | Status | Record |
|---|--------|------------------|--------|--------|
| 1 | September 2026 | 6 | Concluded | [`draws/01-2026-09`](draws/01-2026-09/README.md) · Release `1.0` |
| 2 | October 2026 | 8 | In progress | [`draws/02-2026-10`](draws/02-2026-10/README.md) · Release `2.0` |

Each draw folder contains:
* `README.md` — the exact rules published for that draw
* `entries.sha256` — SHA-256 of the final entry list, locked before the draw
* `result.md` — target block, winning number, and winner once drawn

The full `.txt` entry list for each draw is attached to its matching **Release** (tag `1.0`, `2.0`, …).

## ⚙️ The Draw Method (common to all draws)
**The Zcash blockchain picks the winner.** Anyone can verify using any standard Zcash block explorer.

1. **Target block** — the first Zcash block mined after a date/time announced *before* that block exists.
2. **Extraction** — split the block hash into 2-character pairs, reading **right to left**.
3. **Winner** — the first pair that is a valid entry number (between `01` and the total number of entries) wins; pairs with letters or out-of-range numbers are skipped.

The entry list hash and the target block time are always published **before** the block is mined, so no one — including the LiveZEC team — can influence or predict the winner.

## 🔎 How to Verify a Draw
1. Download that draw's `entries.txt` from its Release and check its SHA-256 matches the one published in the draw's `README.md` / `result.md`.
2. Look up the target block on a Zcash explorer and read its hash.
3. Apply the extraction method above — you should land on the same winning number recorded in `result.md`.

---

<details>
<summary><b>⚠️ Security Notice & Anti-Scam Policy (Click to expand)</b></summary>

LiveZEC will **NEVER**, under ANY circumstances:
* Request payment, cryptocurrency, or a "release fee" to deliver a prize.
* Ask for your recovery phrases (seed phrases), private keys, passwords, or wallet access.
* Contact participants through any account other than the official **@LiveZEC** on X.com.

For any inquiries, please contact the official LiveZEC account via direct message (DM) on X.com.
</details>

<details>
<summary><b>⚖️ Legal Disclaimer (Click to expand)</b></summary>

*No purchase necessary to enter. Must be 18 years or older.*

*This promotion is in no way sponsored, endorsed, administered by, or associated with Rockstar Games, Take-Two Interactive, X Corp., Sony, Microsoft, Netflix, or any of their affiliates. All game titles and trademarks are the property of their respective owners.*
</details>