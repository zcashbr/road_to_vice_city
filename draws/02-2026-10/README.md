# LiveZEC GTA VI Giveaway — Draw #2: Official Draw & Verification

Official public record for the **second Road to Vice City** giveaway hosted by LiveZEC. Like the first draw, this is a transparent, verifiable, and immutable record of the participants and the draw mechanism.

## 🏆 The Prize
One (1) $100 Gift Card for either the PlayStation or Xbox platform (to be used towards the purchase of GTA VI, launching November 19, 2026). The prize cannot be exchanged for cash.

## 🗓️ Participation Window
All qualifying broadcasts must happen between **October 5 and October 15, 2026 (23:59 UTC)**. The form closes on **October 15, 2026, at 11:59 PM (UTC)**.

## 🎟️ How Entries Are Earned (up to 8 per user)
The number assigned to each participant is capped at a **maximum of 8 entries per user**:

* **1 base entry** — follow [@LiveZEC](https://x.com/LiveZEC), like and repost the announcement, tag a streamer, and submit the form.
* **+4 entries (5 total)** — complete **1 qualifying broadcast** using the LiveZEC overlay (OBS Studio recommended), with the overlay clearly visible, publish it as a public VOD, and submit the VOD link + the X.com post link via the form.
* **+3 entries (8 total — maximum)** — complete qualifying broadcasts on **3 different days** (UTC dates).

Each broadcast must be gameplay or a conversation about Zcash, at least **30 minutes** long, and published as a public VOD. All submissions are manually verified by the LiveZEC team. Receiving donations is **not** required.

## 🔒 Locked Entry List & Verification
<!-- Published AFTER entries close (October 15, 2026) and BEFORE the draw block exists. -->

* **Total Valid Entries:** `<N>` (numbered 1 to `<N>`)
* **Maximum per user:** 8 entries
* **Public File:** the complete `.txt` list of entries is available in this repository's **Releases** section (tag `2.0`).

**SHA-256 Hash of the Entry List:**
> `<TODO: publish the SHA-256 of entries.txt here before the draw>`

*Published BEFORE the draw block exists, ensuring absolute fairness. No one, including the LiveZEC team, can influence or predict the winner.*

## ⚙️ How the Draw Works (Provably Fair)
**Draw method: the Zcash blockchain picks the winner.** Anyone can verify the outcome using any standard Zcash block explorer.

1. **The Target Block:** the winning number is derived from the hash of the **FIRST Zcash block mined after `<TODO: date & time in UTC, published before it exists>`**.
2. **The Extraction Method:** split the block hash into 2-character pairs, reading from **right to left**.
3. **The Winner:** the first pair containing two digits between `01` and `<N>` wins. If a pair contains letters or a number above `<N>`, skip to the next pair.

<details>
<summary><b>🔍 Click here to see the Example Breakdown</b></summary>

Assuming `<N>` is at least 32, if the block hash ends in `...A32B131`:
* Split the end into pairs reading right to left: `31`, `B1`, `32`
* `31` ✓ (valid number in range)
* `B1` ✖ (contains a letter, skipped)
* `32` ✓ (valid, but `31` was found first)
* **Result:** the winner would be entry **#31**.

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

*No purchase necessary to enter. Must be 18 years or older.*

*This promotion is in no way sponsored, endorsed, administered by, or associated with Rockstar Games, Take-Two Interactive, X Corp., Sony, Microsoft, Netflix, or any of their affiliates. All game titles and trademarks are the property of their respective owners.*
</details>