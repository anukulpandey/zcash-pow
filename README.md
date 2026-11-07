# zcash-pow · proof of work

Everything I've built and contributed for Zcash, with links. Newest first inside each section.

Numbers are a snapshot from **2026-11-07**.

## 🛠 Tools I built

### zcash-faucet: testnet TAZ from your terminal
`npx zcash-faucet <testnet-address>`

- Code: https://github.com/anukulpandey/zcash-faucet
- npm: https://www.npmjs.com/package/zcash-faucet
- Live status page: https://zcash-faucet.vercel.app
- Usage from the chain: https://zcash-faucet.vercel.app/api/stats
- **47 drips** paid since 2026-10-31 · **5.6 TAZ** sent · **20.3 TAZ** donated back by 9 donors · **954 npm downloads** in its first month

### zcash-testnet-wallet: a working testnet wallet in one command
`npx zcash-testnet-wallet`

- Code: https://github.com/anukulpandey/zcash-testnet-wallet
- npm: https://www.npmjs.com/package/zcash-testnet-wallet
- Prebuilt zcash-devtool for macOS: [arm64](https://www.npmjs.com/package/zcash-testnet-wallet-darwin-arm64) · [x64](https://www.npmjs.com/package/zcash-testnet-wallet-darwin-x64)
- Verified end to end on testnet: wallet + address + QR, faucet funding, payment watcher (mined → confirmed from a viewing key)

## 🔧 Upstream contributions (Zcash repos)

- zcash-devtool: [Create the identity file's directory before writing it](https://github.com/zcash/zcash-devtool/pull/274) (#274)
- sapling-crypto: [zip32: Return None instead of overflowing depth in derive_child](https://github.com/zcash/sapling-crypto/pull/226) (#226)

## 📚 Docs and listings

- ZecHub, Zcash DevTool guide: [prebuilt quick-start option](https://github.com/ZecHub/zechub/pull/2628) (#2628)
- ZecHub, Testnet page: [CLI faucet + how to get a first address](https://github.com/ZecHub/zechub/pull/2629) (#2629)
- ZecHub, Faucets page: [add zcash-faucet](https://github.com/ZecHub/zechub/pull/2572) (#2572)
- awesome-zcash: [add zcash-testnet-wallet](https://github.com/web3privacy/awesome-zcash/pull/5) (#5) · [add zcash-faucet](https://github.com/web3privacy/awesome-zcash/pull/4) (#4)

## 💬 Zcash Community Forum (as [anuna](https://forum.zcashcommunity.com/u/anuna))

**Topics I started**
- [zcash-testnet-wallet: a working testnet wallet + address + QR + TAZ in one command](https://forum.zcashcommunity.com/t/zcash-testnet-wallet-a-working-testnet-wallet-address-qr-taz-in-one-command/59018) (2026-11-07)
- [zcash-faucet: testnet TAZ from your terminal with npx zcash-faucet](https://forum.zcashcommunity.com/t/zcash-faucet-testnet-taz-from-your-terminal-with-npx-zcash-faucet-address/58647) (2026-10-31)

**Helping in other threads**
- [We Need Support with a Testnet ZEC Faucet](https://forum.zcashcommunity.com/t/we-need-support-with-a-testnet-zec-faucet/57087/30)
- [Another faucet post, I know. This one mines its own TAZ](https://forum.zcashcommunity.com/t/another-faucet-post-i-know-this-one-mines-its-own-taz/56868/19)
- [Block explorer + Testnet infrastructure 2025](https://forum.zcashcommunity.com/t/block-explorer-testnet-infrastructure-2025/51451/39)
- [Free Society Hack, Mumbai, 4–5 Nov](https://forum.zcashcommunity.com/t/free-society-hack-mumbai-4-5-nov-partners-mentors-and-judges-wanted/58115/2)
- [Looking for a security reviewer: a zero-knowledge age gate with shielded testnet payments](https://forum.zcashcommunity.com/t/looking-for-a-security-reviewer-a-small-zero-knowledge-age-gate-with-shielded-testnet-payments/58606/4)
- [Zynova: a community-driven quest platform for the Zcash ecosystem](https://forum.zcashcommunity.com/t/zynova-a-community-driven-quest-platform-for-the-zcash-ecosystem/58652/2)
- [What are you building on Zcash?](https://forum.zcashcommunity.com/t/what-are-you-building-on-zcash/55172/45)

## 🧭 Next up

- Linux and Windows builds for zcash-testnet-wallet
- "Seen in mempool" stage for the payment watcher
- A second public testnet lightwalletd server
