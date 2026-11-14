# Draw #3 — Result

> Frozen record of the third and final **Road to Vice City** draw (November 2026). Two prizes, two lists, one block.

## Parameters (to publish before the draw — November 12, 2026)

| | Draw A — GTA VI (@LiveZEC) | Draw B — PS5 (@ZcashBrazil) |
|---|---|---|
| Eligibility | Worldwide | Brazil residents with a Brazilian shipping address |
| Total valid entries (N) | `72` | `69` |
| Entry list | `entries-gta.txt` (Release `3.0`) | `entries-ps5.txt` (Release `3.0`) |
| Entry list SHA-256 | `8B640379FEB0CB330738A4A4890495E9195454BBE72FEE0CAB3CE87796A91AF9` | `2D53D1B106D945E372BE3491F715C3757D48CFD3E74C3090AE369D19A82CEF66` |

* **Target block:** FIRST Zcash block mined at or after **November 13, 2026, 18:00 UTC** (same block for both draws)
* **Extraction method:** split the block hash into 2-character pairs, reading right → left; first pair that is a number between `01` and that list's total wins. No valid pair → next block. 100+ entries → 3-character groups.
* **Order:** PS5 settled first, then GTA VI. If the same person wins both, they keep the PS5 and the GTA VI goes to the next entry on the GTA list belonging to a different person.

## ⚠️ Correction to the GTA VI list (published after the draw)

After the draw we found an error **made by the organizers** in `entries-gta.txt`: **@gordonesTV** was listed with **1 entry** when he was entitled to **5**.

* **Evidence:** form submission `KYXdA0g`, sent on 2026-11-11 22:01 UTC (before entries closed), answered *"Yes, I did"* to broadcasting with LiveZEC and linked the broadcast post (`x.com/gordonesTV/status/2120637170851459411`). Under the rules, that is 5 entries.
* **What changed:** 4 entries for @gordonesTV were added next to his existing one. No other name, order or entry changed. Entries from the old `#63` onward move up by 4 positions.
* **PS5 list:** not affected. @gordonesTV lives in Spain and is not eligible for the PS5.

| | Original list (locked) | Corrected list |
|---|---|---|
| File | `entries-gta.txt` (Release `3.0`) | `entries-gta-corrected.txt` (Release `3.1`) |
| Total entries (N) | `72` | `76` |
| @gordonesTV | `#62` | `#62`–`#66` |
| @keelvinTv | `#63`–`#67` | `#67`–`#71` |
| @jehfox91 | `#68`–`#72` | `#72`–`#76` |
| SHA-256 | `8B640379FEB0CB330738A4A4890495E9195454BBE72FEE0CAB3CE87796A91AF9` | `2648B3D4051C9A5390C3CB76A8EFFB59E7D291BB7107834214D1289DEC4DFD53` |

The block, the hash and the extraction method are the same. Only the GTA VI list changed.

## Outcome

* **Target block height:** `3569610`
* **Target block timestamp:** `2026-11-13 18:00:08 UTC`
* **Target block hash:** `00000000018d110948fda0628c839072cca6c60bf8ca9ffbfc50631ce4ec2f3d`
* **Block explorer link:** https://mainnet.zcashexplorer.app/blocks/3569610
* **Pairs read (right → left):** `3d` ✗ · `2f` ✗ · `ec` ✗ · `e4` ✗ · `1c` ✗ · **`63` ✓**

### Draw B — PS5
* **Valid range:** `01`–`69` → **`63`**
* **Winning entry (X.com handle):** `#63` — **@keelvinTv**

### Draw A — GTA VI
* **Valid range (corrected list):** `01`–`76` → **`63`**
* **Winning entry (X.com handle):** `#63` — **@gordonesTV**
* **Substitution:** not needed. @gordonesTV is a different person from the PS5 winner.

> **For the record:** with the original locked list (N = 72), `#63` belonged to @keelvinTv, who already had the PS5. The GTA VI would then have gone to `#68` — @jehfox91. The prize goes to @gordonesTV because of the organizers' error described above.
