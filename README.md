# 👁️ SITG Oracle (Skin-In-The-Game Verifier)
**"Don't trust the tweet. Verify the wallet."**

> **Built for OKX Onchain OS Hackathon**
> **Tech Stack:** OpenClaw (NLP Intent Parsing) | OKX Onchain OS (Wallet Forensics) | GPT-5.4

## 🚨 The Broken Social Layer of Web3
The Web3 ecosystem suffers from a massive asymmetry between **Social Sentiment** and **Onchain Reality**. 
Influencers and KOLs often broadcast extreme bullish sentiment ("Diamond hands! 💎", "Buying the dip!") to their followers, while simultaneously dumping their bags on retail via decentralized exchanges.

Currently, retail investors have no automated way to cross-reference a Twitter/X post with the actual on-chain execution of the person posting it. **Social signals are weaponized; onchain truth is hidden in the noise.**

## ⚖️ Enter SITG Oracle (利益相关验证器)
SITG (Skin-In-The-Game) Oracle is not a trading bot. It is an **AI-driven forensic agent**. 
It acts as an automated lie detector for Web3, bridging the gap between Natural Language Processing (analyzing what is said) and Onchain Data (analyzing what is done).

If you shill it, you better hold it.

### ⚙️ How It Works (The 5-Step Forensic Pipeline)
1. **Social Ingestion:** The user inputs a social media URL (e.g., a KOL's tweet about $PEPE).
2. **Intent Parsing (via Claw):** The NLP engine extracts the target entity (Token: $PEPE) and classifies the sentiment/claim (Claim: Strong Buy / Holding).
3. **Identity Resolution:** The agent maps the social profile to known on-chain entities via ENS or public address databases.
4. **Onchain OS Execution:** The core engine calls OKX Onchain OS APIs to fetch the wallet's actual asset flow, DEX swaps, and transfer history for the target token over the last 48 hours.
5. **The Verdict (SITG Score):** The agent compares the social claim against the on-chain reality and outputs a verifiable "Skin-In-The-Game" score.

---

## 💻 Live Terminal Demo (Forensic Output)

```yaml
[OKX Onchain OS] > _SITG Oracle_ (Forensic Mode)
=============================================================
[TARGET] URL: [twitter.com/crypto_whale/status/123456](https://twitter.com/crypto_whale/status/123456)...
[TARGET] KOL: @Crypto_Whale (Resolved: whale.eth)
=============================================================
> NLP SENTIMENT ANALYSIS:
  - Entity Detected: $PEPE
  - Social Claim   : EXTREMELY BULLISH ("Buying the dip! Never selling!")

> ONCHAIN OS VERIFICATION (Last 48 Hours):
  - Wallet Analyzed: 0x8F3...9aB2
  - Buy Volume     : 0 ETH
  - Sell/Transfer  : 45 ETH (Dumping via OKX DEX)

[!] CONCLUSION     : 🚨 SEVERE MISMATCH DETECTED 🚨
[!] SITG SCORE     : 0 / 100 (Exit Scam Alert / Paper Hands)
=============================================================
[SYSTEM] "Don't trust the tweet. Verify the wallet." Awaiting next URL...
