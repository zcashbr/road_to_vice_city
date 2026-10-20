# LiveZEC and ZcashBrazil — Road to Vice City 3/3: Official Draw & Verification

Official public record for the **third and final** Road to Vice City giveaway. Like draws #1 and #2, this is a transparent, verifiable, and immutable record of the participants and the draw mechanism.

This draw has **two prizes drawn from two separate lists**:

| Draw | Host | Who can enter | Prize |
|---|---|---|---|
| **A — GTA VI** | [@LiveZEC](https://x.com/LiveZEC) | Worldwide | One **$100** gift card (PlayStation or Xbox) |
| **B — PS5** | [@ZcashBrazil](https://x.com/ZcashBrazil) | **Brazil residents with a shipping address in Brazil only** | One **PlayStation 5** console, purchased by the ZcashBrasil team |

## 🏆 Prizes

* **Draw A (GTA VI):** one (1) $100 gift card for PlayStation or Xbox, to be used towards GTA VI (launching November 19, 2026). Cannot be exchanged for cash.
* **Draw B (PS5):** one (1) PlayStation 5 console, purchased and shipped by the ZcashBrasil team **to an address in Brazil only**. Cannot be exchanged for cash or shipped outside Brazil.

## 🗓️ Key Dates

| Step | Date |
|---|---|
| Entries and qualifying streams/videos open | **October 20, 2026** |
| Entries close | **November 11, 2026, 23:59 UTC**  |
| Numbered lists + SHA-256 published | **November 12, 2026** |
| Draw block | first Zcash block with timestamp **≥ November 13, 2026, 18:00 UTC**  |

## 🎟️ How Entries Are Earned (max. 5 per person in each draw)

* **1 entry** — follow [@LiveZEC](https://x.com/LiveZEC) and [@ZcashBrazil](https://x.com/ZcashBrazil), like and repost the announcement post, tag a streamer in the comments of that post, and submit the form (link in bio).
* **5 entries total (maximum)** — all of the above + **one stream or video of 20 minutes or more** with the LiveZEC overlay **clearly visible**, made between **October 20, 2026 and the close of entries**, published with a **public link** submitted via the form.

General rules:

* Maximum of **5 entries per person in each draw**. The same actions count for both draws: a Brazil resident who opts into the PS5 draw appears on both lists with the same number of entries.
* **One account per person.** Duplicate or fake accounts are disqualified.
* **No donation required**, and receiving donations is not required.
* All submissions are **manually verified**. Actions undone before verification (unfollowing, deleting the repost, deleting the video) void the corresponding entries.
* If someone submits the form more than once, the submissions are combined, up to the 5-entry cap.

## 🔒 Locked Entry Lists & Verification

After entries close, the team publishes **two lists** in this repository (Release tag `3.0`):

* `entries-gta.txt` — Draw A, numbered 1 to **N<sub>GTA</sub>**
* `entries-ps5.txt` — Draw B, numbered 1 to **N<sub>PS5</sub>**

Each participant gets **consecutive** numbers (e.g. someone with 5 entries holds 5 numbers in a row), in the order of their first valid form submission.

The SHA-256 hashes of both lists are published in [`entries.sha256`](entries.sha256) and [`result.md`](result.md) **before the draw block exists**. No one, including the LiveZEC/ZcashBrasil team, can influence or predict the outcome.

## ⚙️ How the Draw Works (Provably Fair)

**The Zcash blockchain picks the winners** — same method as draws #1 and #2. Anyone can verify using any standard Zcash block explorer.

1. **The Target Block:** the winning numbers are derived from the hash of the **FIRST Zcash block mined at or after November 13, 2026, 18:00 UTC** (the lowest-height block with a timestamp ≥ 18:00:00 UTC). The same block is used for both draws.
2. **The Extraction Method:** split the block hash into 2-character pairs, reading from **right to left**.
3. **The Winners:**
   * **Draw A (GTA VI):** the first pair containing two digits between `01` and `N_GTA` wins.
   * **Draw B (PS5):** the first pair containing two digits between `01` and `N_PS5` wins.

   If a pair contains letters or a number above that list's total, skip to the next pair.

**If no pair in the whole hash is valid for a list**, that draw uses the hash of the next block (height + 1), with the same method.
**If a list has 100 entries or more**, that draw reads 3-character groups instead of pairs (`001` to `N`), still right to left.

<details>
<summary><b>🔍 Click here to see the Example Breakdown</b></summary>

Using the draw #2 block hash purely as an example, with a hypothetical list of 48 entries:

```
hash = 00000000005b6f801e859de064c9d09c868eb1c95cfc08511237dbadaf5fdb73
```

* Split the end into pairs reading right to left: `73`, `db`, `5f`, `af`, `ad`, `db`, `37`
* `73` ✖ (above 48) → `db` ✖ → `5f` ✖ → `af` ✖ → `ad` ✖ → `db` ✖ (letters)
* `37` ✓ (valid number in range)
* **Result:** the winner would be entry **#37** — the same as the official draw #2 result.


</details>

## 🔁 Substitution Rules (applied in this order)

1. **The PS5 is settled first.** If the PS5 winner has no shipping address in Brazil, does not reply in time, or does not meet these rules, the prize goes to the **next entry on the PS5 list** that belongs to a **different person**.
2. **Then the GTA VI.** If the GTA VI winner is the **same person** who got the PS5, they keep the PS5 and the GTA VI goes to the **next entry on the GTA list** that belongs to a **different person**.
3. The same applies to the GTA VI if its winner does not reply in time or does not meet these rules.

"Next entry" means the following number on the list (+1), wrapping to 1 after the last one, skipping numbers held by the person being replaced.

## 📬 Prize Delivery

* Winners are announced **only** by the official accounts [@LiveZEC](https://x.com/LiveZEC) (GTA VI) and [@ZcashBrazil](https://x.com/ZcashBrazil) (PS5).
* Each winner has **7 calendar days** after the announcement to reply by DM from the account that entered. After that, the substitution rules apply.
* **PS5:** the winner provides their full name and Brazilian shipping address **only via DM with @ZcashBrazil**, after being announced. This data is used solely for shipping.
* **GTA VI:** delivered digitally, as in previous draws.

---

<details>
<summary><b>⚠️ Security Notice & Anti-Scam Policy (Click to expand)</b></summary>

LiveZEC and ZcashBrasil will **NEVER**, under ANY circumstances:
* Request payment, cryptocurrency, a "release fee", or shipping costs to deliver a prize.
* Ask for your recovery phrases (seed phrases), private keys, passwords, or wallet access.
* Contact participants through any account other than the official **@LiveZEC** or **@ZcashBrazil** on X.com.

For any inquiries, DM @LiveZEC or @ZcashBrazil on X.com.
</details>

<details>
<summary><b>⚖️ Legal Disclaimer (Click to expand)</b></summary>

*No purchase necessary to enter. Must be 18 years or older. Draw B (PS5) is limited to Brazil residents with a shipping address in Brazil.*

*This promotion is in no way sponsored, endorsed, administered by, or associated with Rockstar Games, Take-Two Interactive, X Corp., Sony Interactive Entertainment, Microsoft, or any of their affiliates. All game titles, consoles, and trademarks are the property of their respective owners.*
</details>