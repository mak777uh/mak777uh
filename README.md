# Ilya Vladimirov

Independent researcher. I check claims and publish what the check found. Sometimes the answer is
"not confirmed", and I publish that too. No institution, no degrees, no token.

## What I actually do

1. Take a claim that matters (a payout, a contract invariant, a statement in a paper).
2. Check it against the primary source: a transaction hash, deployed bytecode, or a pinned commit.
3. Write down the result, the exact commands to reproduce it, and what the check does not prove.

## Start here

| | |
|---|---|
| **All work, one folder per direction** | [mak777uh/cases](https://github.com/mak777uh/cases) |
| **Newest case: three payouts checked on chain** | [cases/201](https://github.com/mak777uh/cases/tree/main/cases/201-flapjax-payout-verification) |
| **Code: open pull request with tests** | [specter-diy #447](https://github.com/cryptoadvance/specter-diy/pull/447) |
| **Research record (preprint, DOI)** | [10.5281/zenodo.23648667](https://doi.org/10.5281/zenodo.23648667) |
| **Verification portfolio** | [mak777uh/audits](https://github.com/mak777uh/audits) |

## How to check that I am not making this up

Every case links to something you can open yourself. Three examples:

- **Payouts**: three FLAPJAX transfers, each with a tx hash and a block number. Read the receipt, compare the
  recipient and amount. Nothing else is needed.
- **Code**: a pull request against a real project, 3 files, +365/−8, with 11 tests. Read the diff.
- **Claims**: an issue thread where I compared a paper's sentence with its Lean formalisation and concluded
  they differ. The maintainer agreed the distinction is real. Verdict: not confirmed.

## What is not here

No claims about life, consciousness or intelligence. No peer-reviewed publication yet. No financial product,
no fund, no advice.

---

На русском, коротко: проверяю чужие утверждения (выплаты, контракты, формулировки в статьях), пишу что
получилось и как это перепроверить. Работа лежит в [mak777uh/cases](https://github.com/mak777uh/cases),
по одной папке на направление. Где не смог разобраться, так и написано.
