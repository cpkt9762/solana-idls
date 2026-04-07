# solana-idls

Solana DEX / DeFi 程序 IDL 收集。覆盖 Jupiter 路由的主要协议及生态基础设施，共 **152 个 IDL 文件**。

**来源**：
- 🔗 Solscan API（链上 Anchor IDL）
- 📦 官方开源仓库（GitHub）
- 🔍 IDLGuesser（闭源 Anchor 程序静态分析）
- 🗂 [solores](https://github.com/solana-labs/solores) IDL 库

---

## 目录

```
idls/          ← 152 个 IDL JSON 文件
README.md
```

---

## AMM / Constant Product

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `raydium_amm.json` | Raydium AMM V4 | `675kPX9MHTjS2zt1qfr1NYHuzeLXfQM9H24wFSUt1Mp8` | 16 |
| `raydium_cp.json` | Raydium CP-Swap | `CPMMoo8L3F4NbTegBCKVNunggL7H1ZpdTHKxQB5qKP1C` | 10 |
| `aldrin_v1.json` | Aldrin V1 AMM | `AMM55ShdkoGRB5jVYPjWziwk8m5MpwyDgsMWHaMSQWH6` | 16 |
| `aldrin_v1_pools.json` | Aldrin V1 Pools (SDK) | — | 16 |
| `aldrin_v2.json` | Aldrin V2 AMM | `CURVGoZn8zycx6FXwwevgBTB2gVvdbGTEpvMJDbgs2t4` | 18 |
| `aldrin_farming.json` | Aldrin Farming | `DFarMhaRkdYqhK5jZsexMftaJuWHrY7VzAfkXx5ZmxqZ` | 17 |
| `aldrin_dtwap.json` | Aldrin DTWAP | `G8m1KG1Po42eTPaQBVkU486sVAYU4hKwaueBPCe4Nrm4` | 7 |
| `meteora_damm.json` | Meteora Dynamic AMM | `Eo7WjKq67rjJQSZxS6z3YkapzY3eMj6Xy8X5EQVn5UaB` | 26 |
| `meteora_damm_v1.json` | Meteora DAMM V1 | `Eo7WjKq67rjJQSZxS6z3YkapzY3eMj6Xy8X5EQVn5UaB` | 26 |
| `meteora_damm_v2.json` | Meteora DAMM V2 | `cpamdpZCGKUy5JxQXB4dcpGPiikHawvSWAd6mEn1sGG` | 38 |
| `meteora_cpmm.json` | Meteora CP-AMM | `cpamdpZCGKUy5JxQXB4dcpGPiikHawvSWAd6mEn1sGG` | 38 |
| `meteora_dynamic_amm.json` | Meteora Dynamic AMM (SDK) | `Eo7WjKq67rjJQSZxS6z3YkapzY3eMj6Xy8X5EQVn5UaB` | 26 |
| `cropper.json` | Cropper Finance | `H8W3ctz92svYg6mkn1UtGfu2aQr2fnUFHM1RhScEtQDt` | 66 |
| `saber.json` | Saber Stable Swap | `SSwpkEEcbUqx4vtoEByFjSkhKdCT862DNVb52nZg1UZ` | 1 |
| `saber_decimals.json` | Saber Decimals | `DecZY86MU5Gj7kppfUCEmd4LbXXuyZH1yHaP2NTqdiZB` | 3 |
| `mercurial.json` | Mercurial Stable Swap | `MERLuDFBMmsHnsBPZw2sDQZHvXFMwp8EdjudcU2HKky` | 1 |
| `woofi.json` | WooFi | `WooFif76YGRNjk1pA8wCsN67aQsD9f9iLsz4NcJ1AVb` | 41 |
| `penguin.json` | Penguin Finance | `PSwapMdSai8tjrEXcxFeQth87xC4rRsa4VA5mhGhXkP` | 6 |
| `bonkswap.json` | Bonkswap | `BSwp6bEBihVLdqJRKGgzjcGLHkcTuzmSo1TQkHepzH8p` | 19 |
| `pancake_swap.json` | PancakeSwap | `HpNfyc2Saw7RKkQd8nEL4khUcuPhQ7WwY1B2qjx8jxFq` | 27 |
| `guacswap.json` | Guacswap | `Gswppe6ERWKpUTXvRPfXdzHhiCyJvLadVvXGfdpBqcE1` | 20 |
| `omnipair.json` | Omnipair | `omnixgS8fnqHfCcTGKWj6JtKjzpJZ1Y5y9pyFkQDkYE` | 19 |
| `carrot.json` | Carrot | `CarrotwivhMpDnm27EHmRLeQ683Z1PufuqEmBZvD282s` | 42 |
| `byreal.json` | Byreal | `REALQqNEomY6cQGZJUGwywTBD2UmDT32rZcNnfxQ5N2` | 29 |
| `byreal_clmm.json` | Byreal CLMM | `REALQqNEomY6cQGZJUGwywTBD2UmDT32rZcNnfxQ5N2` | 29 |
| `saros.json` | Saros AMM | `SSwapUtytfBdBn1b9NUGG6foMVPtcWgpRU32HToDUZr` | 1 |
| `goonfi.json` | GoonFi | `goonERTdGsjnkZqWuVjs73BZ3Pb9qoCUdBUL17BnS5j` | 2 |
| `scorch.json` | Scorch | `ojh19ojaKduoJZuaJADhcVGp4xt1TcdAvZmpVsCorch` | 1 |
| `tesserav.json` | TesseraV | `TessVdML9pBGgG9yGks7o4HewRaXVAMuoVj4x83GLQH` | 1 |
| `obsidian.json` | Obsidian | `HBVw6bZtcCaezhcBrmfyXBSBRWCdv72271xQ4GPvms2z` | 1 |
| `zerofi.json` | ZeroFi | `ZERor4xhbUycZ6gb9ntrhqscUcZmAbQDjEAtCf4hbZY` | 1 |
| `bisonfi.json` | BisonFi | `BiSoNHVpsVZW2F7rx2eQ59yQwKxzU5NvBcmKshCSUypi` | 1 |
| `alphaq.json` | AlphaQ | `ALPHAQmeA7bjrVuccPsYPiCvsi428SNwte66Srvs4pHA` | 1 |
| `aquifer.json` | Aquifer | `AQU1FRd7papthgdrwPTTq5JacJh8YtwEXaBfKU3bTz45` | 1 |
| `humidifi.json` | HumidiFi | `9H6tua7jkLhdm3w8BvgpTn5LZNU7g4ZynDmCiNN3q6Rp` | 1 |
| `quantum.json` | Quantum | `QuaNtZsgYRe5Z9Bk4LZ4cTD9tbkVoyCNf1R2BN9bBDv` | 1 |
| `solfi.json` | SolFi | `SoLFiHG9TfgtdUXUjWAxi3LtvYuFyDLVhBWxdMZxyCe` | 1 |
| `marco_polo.json` | Marco Polo | `9tKE7Mbmj4mxDjWatikzGAtkoWosiiZX9y6J4Hfm2R8H` | 1 |
| `whalestreet_v2.json` | WhaleStreet | `FW6zUqn4iKRaeopwwhwsquTY6ABWLLgjxtrC3VPnaWBf` | 1 |
| `okx_dex.json` | OKX DEX | `6m2CDdhRgxpH4WjvdzxAYbGxwdGUz5MziiL5jek2kBma` | 18 |
| `okx_dex_v3.json` | OKX DEX V3 | `proVF4pMXVaYqmy4NjniPh4pqKNfMmsihgd4wdkCX3u` | 17 |
| `obric_v2_full.json` | Obric V2 (完整版) | `obriQD1zbpyLz95G5n7nJe6a4DPjpFwa5XYPoNm113y` | 12 |

---

## CLMM / 集中流动性

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `raydium_clmm.json` | Raydium CLMM | `CAMMCzo5YL8w4VFF8KVHrK22GGUsp5VTaW7grrKgrWqK` | 25 |
| `whirlpool.json` | Orca Whirlpool | `whirLbMiicVdio4qvUfM5KAg6Ct8VwpYzGff3uctyCc` | 66 |
| `stabble_clmm.json` | Stabble CLMM | `6dMXqGZ3ga2dikrYS9ovDXgHGh5RUsb2RTUj6hrQXhk6` | 21 |
| `crema.json` / `crema_clmm_v2.json` | Crema CLMM | `CLMM9tUoggJu2wagPkkqs9eFG4BWhVBZWkP1qv3Sp7tR` | 29 |
| `cykura.json` / `cyclos_core.json` | Cykura (Cyclos Core) | `cysPXAjehMpVKUapzbMCCnpFxUFFryEWEaLgnb9NrR8` | 24 |
| `scale_vmm.json` | Scale VMM | `SCALEWoRSpVZpMRqHEcDfNvBh3nUSe34jDr9r689gLa` | 11 |
| `scale_amm.json` | Scale AMM | `SCALEwAvEK5gtkdHiFzXfPgtk2YwJxPDzaV3aDmR7tA` | 10 |
| `lifinity_v1.json` | Lifinity V1 | `EewxydAPCCVuNEyrVN68PuSYdQ7wKn27V9Gjeoi8dy3S` | 3 |
| `lifinity_v2.json` | Lifinity V2 | `2wT8Yq49kHgDzXuPxZSaeLaH1qbmGXtEyPy64bL7aD3c` | 3 |
| `invariant.json` | Invariant | `HyaB3W9q6XdA5xwpU4XnSZV94htfmbmqJXZcEbRaJutt` | 3 |
| `heaven.json` / `heaven_dex.json` | Heaven DEX | `HEAVENoP2qxoeuF8Dj2oT1GHEnu49U5mJYkdeC8BAX2o` | 54 / 33 |
| `orca_v2.json` | Orca V2 (Legacy) | `9W959DqEETiGZocYWCQPaJ6sBmUzgfxXfqGeTEdp3aQP` | 1 |
| `hylo_exchange.json` / `hylo_exchange_v2.json` | Hylo Exchange | `HYEXCHtHkBagdStcJCp3xbbb9B7sdMdWXFNj6mdsG4hn` | 27 |

---

## DLMM / 动态流动性

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `meteora_dlmm.json` | Meteora DLMM | `LBUZKhRxPF3XUpBCjp4YzTKgLccjZhTSDM9YuVaPwxo` | 74 |
| `saros_dlmm.json` | Saros DLMM | `1qbkdrr3z4ryLA7pZykqxvxWPoeifcVKo6ZG9CfkvVE` | 17 |
| `saros_dlmm_rewarder.json` | Saros DLMM Rewarder | `mdmavMvJpF4ZcLJNg6VSjuKVMiBo5uKwERTg1ZB9yUH` | 13 |

---

## Bonding Curve / Launch

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `dynamic_bonding_curve.json` | Meteora Dynamic Bonding Curve | `dbcij3LWUppWqq96dh6gJWwBifmcGfLSB5D4DuSMaqN` | 28 |
| `pump_fun.json` | Pump.fun | `6EF8rrecthR5Dkzon8Nwu78hRvfCKubJ14M5uBEwF6P` | 29 |
| `pumpfun_amm.json` | Pump.fun AMM (PumpSwap) | `pAMMBay6oceH9fJKBRHGP5D4bD4sWpmSwMn52FMfXEA` | 25 |
| `pump_fun_fees.json` | Pump.fun Fees | `pfeeUxB6jkeY1Hxd7CsFCAjcbHA9rWtchMGdZ6VojVZ` | 10 |
| `dumpfun.json` | DumpFun | `DumpFunGAgW6kPHzWMA3Nnqecyrd6SGnLZvNGp2aHwEa` | 5 |
| `moonit.json` | Moonit | `MoonCVVNZFSYkqNXP6bxHLPL6QQJiMagDL3qcqUQTrG` | 6 |
| `boop_fun.json` | Boop.fun | `boop8hVGQGqehUK2iVEMEnMrL5RbjywRzHKBmBE7ry4` | 29 |
| `virtuals.json` | Virtuals | `5U3EU2ubXtK84QcRjWVmYt9RaDyA8gKxdUrPFXmZyaki` | 8 |
| `raydium_launchlab.json` | Raydium Launchlab | `LanMV9sAd7wArD4vJFi2qDdfnVhFxYSUg6eADduJ3uj` | 23 |
| `defituna_fusionamm.json` | DefiTuna (FusionAMM) | `fUSioN9YKKSa3CUC2YUc4tPkHJ5Y6XW1yz8y6F7qWz9` | 35 |
| `perena.json` | Perena | `NUMERUNsFCP3kuNmWZuXtm1AaQCPj9uw6Guv2Ekoi5P` | 22 |
| `perena_star.json` | Perena Star | `save8RQVPMWNTzU18t3GBvBkN9hT7jsGjiCQ28FpD9H` | 32 |
| `trends.json` | Trends | `CURVEmPpijXDTNdqrA9PGP1io2rkgiVXH26xdXVGLLfz` | 5 |
| `runner_rodeo.json` ✦ | RunnerRodeo | `runnrXXdsSRkdueCRYxKDvSWfv6nAnrG5dcM29qj1HA` | 13 |
| `onedex.json` ✦ | 1DEX | `DEXYosS6oEGvk8uCDayvwEZz4qEyDJRf9nFgYCaqPMTm` | 10 |
| `lemmingsfi.json` ✦ | LemmingsFi | `BQEJZUB4CzoT6UhRffoCkqCyqQNrCPCSGHcPEmsdbEsX` | 14 |
| `vault_liquid_unstake.json` ✦ | VaultLiquidUnstake | `2rU1oCHtQ7WJUvy15tKtFvxdYNNSc3id7AzUcjeFSddo` | 15 |

---

## CLOB / 订单簿

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `openbook_v2.json` | OpenBook V2 | `opnb2LAfJYbRMAHHvqjCwQxanZn7ReEHp1k81EohpZb` | 29 |
| `openbook_v1.json` | OpenBook V1 | — | 29 |
| `openbook_twap.json` | OpenBook TWAP | — | 11 |
| `phoenix_v1.json` | Phoenix V1 | `PhoeNiXZ8ByJGLkxNfZRnkUfjvmuYqLR89jjFHGqdXY` | 28 |
| `manifest.json` | Manifest | `MNFSTqtC93rEfYHB6hF82sKdZpUDFWkViLByLd1k1Ms` | 15 |
| `manifest_wrapper.json` | Manifest Wrapper | `wMNFSTkir3HgyZTsB7uqu3i7FA73grFCptPXgrZjksL` | 8 |
| `plasma_amm.json` / `plasma_gavel.json` | Plasma / Gavel | `srAMMzfVHVAtgSJc8iH6CfKzuWuUTzLHVCE81QU1rgi` | 10 |
| `serum_v3.json` | Serum V3 | `9xQeWvG816bUx9EPjHmaT23yvVM2ZWbrrpZb9PusVFin` | 18 |
| `stabble_stable_swap.json` | Stabble Stable Swap | `swapNyd8XiQwJ6ianp9snpu4brUqFxadzvHebnAXjJZ` | 19 |
| `stabble_weighted_swap.json` | Stabble Weighted Swap | `swapFpHZwjELNnjvThjajtiVmkz3yPQEHjLtka2fwHW` | 13 |
| `m_swap.json` / `m_swap_v2.json` | M Swap | `MSwapi3WhNKMUGm9YrxGhypgUEt7wYQH3ZgG32XoWzH` | 8 |

---

## 永续合约 / Perps

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `perps.json` / `jupiter_perps.json` | Jupiter Perps | `PERPHjGBqRHArX4DySjwM6UJHiR3sWAatqfdBS2qQJu` | 59 |
| `drift.json` / `drift_v2.json` | Drift Protocol V2 | `dRiftyHA39MWEi3m9aunc5MzRF1JYuBsbn6VPcn33UH` | 249 |

---

## 预测市场 / Governance

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `futarchy.json` | MetaDAO Futarchy | `FUTARELBfJfQ8RDGhg1wdhddq1odMAJUePHFuBYfUxKq` | 18 |

---

## 借贷 / Yield

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `kamino.json` | Kamino Lending | `KLend2g3cP87fffoy8q1mQqGKjrxjC8boSyAYavgmjD` | 32 |
| `voltr.json` | Voltr | `vVoLTRjQmtFpiYoegx285Ze4gsLJ8ZxgFKVcuvmG1a8` | 26 |
| `defituna.json` | DefiTuna | `fUSioN9YKKSa3CUC2YUc4tPkHJ5Y6XW1yz8y6F7qWz9` | 32 |
| `hylo_stability_pool.json` | Hylo Stability Pool | `HysTabVUfmQBFcmzu1ctRd1Y1fxd66RBpboy1bmtDSQQ` | 9 |

---

## Jupiter 核心

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `jupiter_aggregator_v6.json` | Jupiter Aggregator V6 | `JUP6LkbZbjS1jKKwapdHNy74zcZ3tLUZoi5QNyVTaV4` | 14 |
| `jupiter_aggregator.json` | Jupiter Aggregator (旧) | `JUP6LkbZbjS1jKKwapdHNy74zcZ3tLUZoi5QNyVTaV4` | 14 |
| `jupiter_dex_interfaces.json` | Jupiter DEX Interfaces | — | 80 |
| `jupiter_cpi.json` | Jupiter CPI | — | 44 |
| `jupiter_core.json` | Jupiter Core | — | 49 |
| `dca.json` | Jupiter DCA | — | 10 |
| `jupiter_lend.json` | Jupiter Lend Earn | `jup3YeL8QhtSx1e253b2FDvsMNC87fDrgQZivbrndc9` | 1 |
| `jupiter_lend_lending.json` | Jupiter Lend — Lending | `jup3YeL8QhtSx1e253b2FDvsMNC87fDrgQZivbrndc9` | 16 |
| `jupiter_lend_flashloan.json` | Jupiter Lend — Flashloan | `jupgfSgfuAXv4B6R2Uxu85Z1qdzgju79s6MfZekN6XS` | 7 |
| `jupiter_lend_liquidity.json` | Jupiter Lend — Liquidity | `jupeiUmn818Jg1ekPURTpr4mFo29p46vygyykFJ3wZC` | 24 |
| `jupiter_lend_vaults.json` | Jupiter Lend — Vaults | `jupr81YtYssSyPt8jbnGuiWon5f6x9TcDEFxYe3Bdzi` | 27 |
| `jupiter_lend_oracle.json` | Jupiter Lend — Oracle | `jupnw4B6Eqs7ft6rxpzYLJZYSnrpRgPcr589n5Kv4oc` | 8 |

---

## LST / Liquid Staking / Sanctum

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `sanctum_inf.json` | Sanctum INF Controller | `5ocnV1qiCgaQR8Jb8xWnVbApfaygJ8tNoZfgPwsgx9kx` | 27 |
| `sanctum_infinity.json` | Sanctum Infinity | `5ocnV1qiCgaQR8Jb8xWnVbApfaygJ8tNoZfgPwsgx9kx` | 23 |
| `sanctum_s_controller.json` | Sanctum S-Controller | `SP12tWFxD9oJsVWNavTTBZvMbA6gkAmxtVgxdqvyvhY` | 23 |
| `sanctum_flat_fee.json` | Sanctum Flat Fee | `f1tUoNEKrDp1oeGn4zxr7bh41eN6VcfHjfrL3ZqQday` | 10 |
| `sanctum_generic_calc.json` | Sanctum Generic Calculator | — | 5 |
| `sanctum_marinade_calc.json` | Sanctum Marinade Calculator | — | 0 |
| `sanctum_spl_calc.json` | Sanctum SPL Calculator | — | 0 |
| `stakedex.json` | Stakedex | `stkitrT1Uoy18Dk1fTrgPw8W6MVzoCfYoAFT4MLsmhq` | 9 |
| `stakedex_deposit_sol.json` | Stakedex — Deposit SOL | — | 5 |
| `stakedex_deposit_stake.json` | Stakedex — Deposit Stake | — | 6 |
| `stakedex_withdraw_sol.json` | Stakedex — Withdraw SOL | — | 1 |
| `stakedex_withdraw_stake.json` | Stakedex — Withdraw Stake | — | 5 |
| `marinade.json` / `marinade_finance.json` | Marinade Finance | `MarBmsSgKXdrN1egZf5sqe1TMai9K1rChYNDJgjq7aD` | 21 |
| `vault_liquid_unstake.json` ✦ | VaultLiquidUnstake | `2rU1oCHtQ7WJUvy15tKtFvxdYNNSc3id7AzUcjeFSddo` | 15 |
| `helium_network.json` | Helium Network | `treaf4wWBBty3fHdyBpo35Mz84M8k3heKXmjmi9vFt5` | 3 |
| `helium_treasury.json` | Helium Treasury | `treaf4wWBBty3fHdyBpo35Mz84M8k3heKXmjmi9vFt5` | 3 |

---

## Meteora 组件

| 文件 | 程序 ID | 指令数 |
|------|---------|--------|
| `meteora_alpha_vault.json` | `SNPmGgnywBvvrAKMLundzG6StojyHTHDLu7T4sdhP4k` | 25 |
| `meteora_vault.json` | `24Uqj9JCLxUeoC3hGfh5W3s9FM9uCHDS2SG3LYwBpyTi` | 14 |
| `meteora_locker.json` | `LocpQgucEQHbqNABEYvBvwoxCPsSbG91A1QaQhQQqjn` | 11 |
| `meteora_m3m3.json` | `FEESngU3neckdwib9X3KWqdL7Mjmqk9XNp3uh5JbP4KP` | 11 |
| `meteora_damm_v2_sdk.json` | `cpamdpZCGKUy5JxQXB4dcpGPiikHawvSWAd6mEn1sGG` | 35 |

---

## 其他 / 基础设施

| 文件 | 程序 | 程序 ID | 指令数 |
|------|------|---------|--------|
| `mango_v4.json` | Mango V4 | — | 105 |
| `metadao.json` | MetaDAO | — | 19 |
| `goosefx_gamma.json` | GooseFX GAMMA | `GAMMA7meSFWaBXF25oSUgmGRwaW6sCMFLmBNiMSdbHVT` | 27 |
| `goosefx_ssl.json` | GooseFX SSL | — | 6 |
| `goosefx_controller.json` | GooseFX Controller | — | 3 |
| `riptide.json` | Riptide | — | 16 |
| `okx_dex.json` | OKX DEX | `6m2CDdhRgxpH4WjvdzxAYbGxwdGUz5MziiL5jek2kBma` | 18 |
| `okx_dex_v3.json` | OKX DEX V3 | `proVF4pMXVaYqmy4NjniPh4pqKNfMmsihgd4wdkCX3u` | 17 |
| `merkle_distributor.json` | Merkle Distributor | — | 10 |
| `govern.json` | Govern (Tribeca) | — | 10 |
| `scale_vmm.json` | Scale VMM | `SCALEWoRSpVZpMRqHEcDfNvBh3nUSe34jDr9r689gLa` | 11 |
| `gamma_swap_amm_v3.json` | Raydium CLMM V3 (copy) | `CAMMCzo5YL8w4VFF8KVHrK22GGUsp5VTaW7grrKgrWqK` | 23 |
| `gamma_swap_dlmm.json` | Meteora DLMM (copy) | `LBUZKhRxPF3XUpBCjp4YzTKgLccjZhTSDM9YuVaPwxo` | 44 |

---

## 统计

| 项目 | 数量 |
|------|------|
| **IDL 文件总数** | **152** |
| Jupiter 路由 DEX 程序覆盖 | 47 → **~75** / 90 |
| 平均指令数 | ~18 |

> ✦ 标注的文件由 [IDLGuesser](https://github.com/sec3-service/IDLGuesser) 从闭源 Anchor 程序静态分析生成，指令名称正确但部分 args 类型可能不完整。

---

## IDL 来源说明

| 来源 | 特点 |
|------|------|
| **链上 Anchor IDL**（Solscan / anchor-cli） | 程序部署方发布，最权威 |
| **官方开源仓库** | 与链上一致，含完整类型信息 |
| **[solores](https://github.com/solana-labs/solores) 库** | 社区整理，覆盖面广 |
| **IDLGuesser** ✦ | 闭源程序静态分析，指令名准确，部分 args/accounts 可能缺失 |

---

## 相关项目

- [solana-idl-parsers](https://github.com/cpkt9762/solana-idl-parsers) — 基于这些 IDL 生成 Rust SDK
- [IDLGuesser](https://github.com/sec3-service/IDLGuesser) — 闭源 Anchor 程序 IDL 提取工具
- [solores](https://github.com/solana-labs/solores) — Solana IDL → Rust 客户端生成器
