# LiveZEC GTA VI Giveaway: Official Draw & Verification

Welcome to the official public repository for the first **Road to Vice City** giveaway hosted by LiveZEC. This repository serves as a transparent, verifiable, and immutable record of the participants and the draw mechanism.

## 🏆 The Prize
One (1) $100 Gift Card for either the PlayStation or Xbox platform (to be used towards the purchase of GTA VI: Ultimate Edition, launching November 19, 2026). The prize cannot be exchanged for cash.

## 🔒 Locked Entry List & Verification
The entry period concluded on **September 10, 2026, at 11:59 PM (UTC)**. All entries have been meticulously verified by the LiveZEC core team. 

* **Total Valid Entries:** 54 (numbered 1 to 54)
* **Maximum per user:** Up to 6 entries (1 for social media actions + 5 for broadcasting a VOD using the LiveZEC overlay on software like OBS Studio).
* **Public File:** The complete `.txt` list of entries is available for download in this repository's **Releases** section.

To ensure no tampering can occur between the publication of the list and the actual draw, the cryptographic hash of the entry list file is locked and published below:

**SHA-256 Hash of the Entry List:**
> `e9f66cc64c1db75f337bdab3d46107949b62e3ad6f1225fa2e9721f46ca9dc38`

*Published BEFORE the draw block exists, ensuring absolute fairness. No one, including the LiveZEC team, can influence or predict the winner.*

## ⚙️ How the Draw Works (Provably Fair)
**Draw method: The Zcash blockchain picks the winner.**

We are utilizing a decentralized and public method. Anyone can verify the outcome using any standard Zcash block explorer. 

1. **The Target Block:** The winning number will be derived from the hash of the **FIRST Zcash block mined after September 14, 2026, 23:00 UTC**.
2. **The Extraction Method:** We will split the block hash into 2-character pairs, reading from **right to left**.
3. **The Winner:** The first pair containing two digits between `01` and `54` wins. If a pair contains letters or numbers above 54, we skip to the next pair.

<details>
<summary><b>🔍 Click here to see the Example Breakdown</b></summary>

If the block hash ends in `...A32B131`: 
* We split the end into pairs reading right to left: `31`, `B1`, `32`
* `31` ✓ (Valid number between 01 and 54)
* `B1` ✖ (Contains a letter, skipped)
* `32` ✓ (Valid, but `31` was found first)
* **Result:** The winner would be entry **#31**.

</details>

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

*No purchase necessary to enter. Must be 18 years or older to have participated.*

*This promotion is in no way sponsored, endorsed, administered by, or associated with Rockstar Games, Take-Two Interactive, X Corp., Sony, Microsoft, Netflix, or any of their affiliates. All game titles and trademarks are the property of their respective owners.*
</details>