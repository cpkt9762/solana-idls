# solana-idls

Solana DEX 程序 IDL 文件收集。覆盖 Jupiter 路由的 90 个 DEX 协议，共 **105 个 IDL 文件**。

来源：Solscan API（链上 Anchor IDL）、`anchor idl fetch`、官方开源仓库、项目内嵌 IDL。

---

## 目录结构

```
idls/
├── raydium_amm.json
├── raydium_clmm.json
├── whirlpool.json
└── ...（105 个文件）
```

---

## Jupiter 路由 DEX — IDL 覆盖情况

### ✅ 已收录（47 个主程序）

#### AMM / Constant Product

| 文件 | 协议 | 程序 ID |
|------|------|---------|
| `raydium_amm.json` | Raydium AMM | `675kPX9MHTjS2zt1qfr1NYHuzeLXfQM9H24wFSUt1Mp8` |
| `raydium_cp.json` | Raydium CP-Swap | `CPMMoo8L3F4NbTegBCKVNunggL7H1ZpdTHKxQB5qKP1C` |
| `raydium_launchlab.json` | Raydium Launchlab | `LanMV9sAd7wArD4vJFi2qDdfnVhFxYSUg6eADduJ3uj` |
| `saber_decimals.json` | Saber (Decimals) | `DecZY86MU5Gj7kppfUCEmd4LbXXuyZH1yHaP2NTqdiZB` |
| `aldrin.json` | Aldrin V2 Pools | `AMM55ShdkoGRB5jVYPjWziwk8m5MpwyDgsMWHaMSQWH6` |
| `stabble_stable_swap.json` | Stabble Stable Swap | `swapNyd8XiQwJ6ianp9snpu4brUqFxadzvHebnAXjJZ` |
| `stabble_weighted_swap.json` | Stabble Weighted Swap | `swapFpHZwjELNnjvThjajtiVmkz3yPQEHjLtka2fwHW` |
| `woofi.json` | WooFi | `WooFif76YGRNjk1pA8wCsN67aQsD9f9iLsz4NcJ1AVb` |
| `bonkswap.json` | Bonkswap | `BSwp6bEBihVLdqJRKGgzjcGLHkcTuzmSo1TQkHepzH8p` |
| `guacswap.json` | Guacswap | `Gswppe6ERWKpUTXvRPfXdzHhiCyJvLadVvXGfdpBqcE1` |
| `omnipair.json` | Omnipair | `omnixgS8fnqHfCcTGKWj6JtKjzpJZ1Y5y9pyFkQDkYE` |
| `pancakeswap.json` | PancakeSwap | `HpNfyc2Saw7RKkQd8nEL4khUcuPhQ7WwY1B2qjx8jxFq` |
| `carrot.json` | Carrot | `CarrotwivhMpDnm27EHmRLeQ683Z1PufuqEmBZvD282s` |
| `byreal.json` | Byreal | `REALQqNEomY6cQGZJUGwywTBD2UmDT32rZcNnfxQ5N2` |

#### CLMM / 集中流动性

| 文件 | 协议 | 程序 ID |
|------|------|---------|
| `raydium_clmm.json` | Raydium CLMM | `CAMMCzo5YL8w4VFF8KVHrK22GGUsp5VTaW7grrKgrWqK` |
| `whirlpool.json` | Orca Whirlpool | `whirLbMiicVdio4qvUfM5KAg6Ct8VwpYzGff3uctyCc` |
| `stabble_clmm.json` | Stabble CLMM | `6dMXqGZ3ga2dikrYS9ovDXgHGh5RUsb2RTUj6hrQXhk6` |
| `crema.json` | Crema CLMM | `CLMM9tUoggJu2wagPkkqs9eFG4BWhVBZWkP1qv3Sp7tR` |
| `scale_vmm.json` | Scale VMM | `SCALEWoRSpVZpMRqHEcDfNvBh3nUSe34jDr9r689gLa` |
| `scale_amm.json` | Scale AMM | `SCALEwAvEK5gtkdHiFzXfPgtk2YwJxPDzaV3aDmR7tA` |

#### DLMM / 动态流动性

| 文件 | 协议 | 程序 ID |
|------|------|---------|
| `meteora_dlmm.json` | Meteora DLMM | `LBUZKhRxPF3XUpBCjp4YzTKgLccjZhTSDM9YuVaPwxo` |
| `saros_dlmm.json` | Saros DLMM | `1qbkdrr3z4ryLA7pZykqxvxWPoeifcVKo6ZG9CfkvVE` |

#### Dynamic AMM / Bonding Curve

| 文件 | 协议 | 程序 ID |
|------|------|---------|
| `meteora.json` | Meteora Dynamic AMM | `Eo7WjKq67rjJQSZxS6z3YkapzY3eMj6Xy8X5EQVn5UaB` |
| `meteora_damm_v2.json` | Meteora DAMM v2 | `cpamdpZCGKUy5JxQXB4dcpGPiikHawvSWAd6mEn1sGG` |
| `dynamic_bonding_curve.json` | Dynamic Bonding Curve | `dbcij3LWUppWqq96dh6gJWwBifmcGfLSB5D4DuSMaqN` |
| `pump_fun.json` | Pump.fun | `6EF8rrecthR5Dkzon8Nwu78hRvfCKubJ14M5uBEwF6P` |
| `pumpfun_amm.json` | Pump.fun AMM (PumpSwap) | `pAMMBay6oceH9fJKBRHGP5D4bD4sWpmSwMn52FMfXEA` |
| `virtuals.json` | Virtuals | `5U3EU2ubXtK84QcRjWVmYt9RaDyA8gKxdUrPFXmZyaki` |
| `moonit.json` | Moonit | `MoonCVVNZFSYkqNXP6bxHLPL6QQJiMagDL3qcqUQTrG` |
| `boop_fun.json` | Boop.fun | `boop8hVGQGqehUK2iVEMEnMrL5RbjywRzHKBmBE7ry4` |
| `defituna_fusionamm.json` | DefiTuna (FusionAMM) | `fUSioN9YKKSa3CUC2YUc4tPkHJ5Y6XW1yz8y6F7qWz9` |
| `perena.json` | Perena | `NUMERUNsFCP3kuNmWZuXtm1AaQCPj9uw6Guv2Ekoi5P` |
| `perena_star.json` | Perena Star | `save8RQVPMWNTzU18t3GBvBkN9hT7jsGjiCQ28FpD9H` |

#### CLOB / 订单簿

| 文件 | 协议 | 程序 ID |
|------|------|---------|
| `openbook_v2.json` | OpenBook V2 | `opnb2LAfJYbRMAHHvqjCwQxanZn7ReEHp1k81EohpZb` |
| `phoenix_v1.json` | Phoenix V1 | `PhoeNiXZ8ByJGLkxNfZRnkUfjvmuYqLR89jjFHGqdXY` |
| `plasma_amm.json` | Plasma AMM | — |
| `manifest.json` | Manifest | `MNFSTqtC93rEfYHB6hF82sKdZpUDFWkViLByLd1k1Ms` |

#### 永续合约 / Perps

| 文件 | 协议 | 程序 ID |
|------|------|---------|
| `perps.json` | Jupiter Perps | `PERPHjGBqRHArX4DySjwM6UJHiR3sWAatqfdBS2qQJu` |
| `drift.json` | Drift Protocol | — |

#### Sanctum / LST

| 文件 | 协议 | 程序 ID |
|------|------|---------|
| `sanctum_s_controller.json` | Sanctum S-Controller | `SP12tWFxD9oJsVWNavTTBZvMbA6gkAmxtVgxdqvyvhY` |
| `sanctum_inf.json` | Sanctum INF | `5ocnV1qiCgaQR8Jb8xWnVbApfaygJ8tNoZfgPwsgx9kx` |

#### GooseFX / Hylo / 其他 AMM

| 文件 | 协议 | 程序 ID |
|------|------|---------|
| `goosefx_gamma.json` | GooseFX GAMMA | `GAMMA7meSFWaBXF25oSUgmGRwaW6sCMFLmBNiMSdbHVT` |
| `goosefx_ssl.json` | GooseFX SSL | — |
| `hylo_exchange.json` | Hylo Exchange | `HYEXCHtHkBagdStcJCp3xbbb9B7sdMdWXFNj6mdsG4hn` |
| `hylo_stability_pool.json` | Hylo Stability Pool | `HysTabVUfmQBFcmzu1ctRd1Y1fxd66RBpboy1bmtDSQQ` |
| `m_swap.json` | M Swap | `MSwapi3WhNKMUGm9YrxGhypgUEt7wYQH3ZgG32XoWzH` |
| `trends.json` | Trends | `CURVEmPpijXDTNdqrA9PGP1io2rkgiVXH26xdXVGLLfz` |
| `riptide.json` | Riptide | `riptK81hDxhe5pW5jSzSM9iRA8azgEgLJ4dXkPtBS7j` |
| `voltr.json` | Voltr | `vVoLTRjQmtFpiYoegx285Ze4gsLJ8ZxgFKVcuvmG1a8` |
| `helium_network.json` | Helium Network | `treaf4wWBBty3fHdyBpo35Mz84M8k3heKXmjmi9vFt5` |
| `metadao.json` | MetaDAO (Futarchy AMM) | `FUTARELBfJfQ8RDGhg1wdhddq1odMAJUePHFuBYfUxKq` |
| `mango_v4.json` | Mango V4 | — |

---

### ❌ 无 IDL（43 个）

#### Native 程序（非 Anchor，无标准 IDL 格式）

| 协议 | 程序 ID | 说明 |
|------|---------|------|
| Saber | `SSwpkEEcbUqx4vtoEByFjSkhKdCT862DNVb52nZg1UZ` | 原生 Rust，非 Anchor |
| Mercurial | `MERLuDFBMmsHnsBPZw2sDQZHvXFMwp8EdjudcU2HKky` | 原生 Rust，非 Anchor |
| Token Swap (SPL) | `SwaPpA9LAaLfeLi3a68M4DjnLqgtticKg6CnyNwgAC8` | SPL 原生程序 |
| Orca V1 | `DjVE6JNiYqPL2QXyCUUh8rNjHrbz9hXHNYt99MQ59qw1` | 已废弃，原生程序 |
| Orca V2 (Legacy) | `9W959DqEETiGZocYWCQPaJ6sBmUzgfxXfqGeTEdp3aQP` | 已废弃，非 Anchor |
| Invariant | `HyaB3W9q6XdA5xwpU4XnSZV94htfmbmqJXZcEbRaJutt` | 未发布 Anchor IDL |

#### 闭源程序（链上无 IDL，无公开源码）

| 协议 | 程序 ID |
|------|---------|
| TesseraV | `TessVdML9pBGgG9yGks7o4HewRaXVAMuoVj4x83GLQH` |
| Scorch | `ojh19ojaKduoJZuaJADhcVGp4xt1TcdAvZmpVsCorch` |
| Obric V2 | `obriQD1zbpyLz95G5n7nJe6a4DPjpFwa5XYPoNm113y` |
| Obsidian | `HBVw6bZtcCaezhcBrmfyXBSBRWCdv72271xQ4GPvms2z` |
| Heaven | `HEAVENoP2qxoeuF8Dj2oT1GHEnu49U5mJYkdeC8BAX2o` |
| ZeroFi | `ZERor4xhbUycZ6gb9ntrhqscUcZmAbQDjEAtCf4hbZY` |
| BisonFi | `BiSoNHVpsVZW2F7rx2eQ59yQwKxzU5NvBcmKshCSUypi` |
| Gavel | `srAMMzfVHVAtgSJc8iH6CfKzuWuUTzLHVCE81QU1rgi` |
| GoonFi | `goonERTdGsjnkZqWuVjs73BZ3Pb9qoCUdBUL17BnS5j` |
| GoonFi V2 | `goonuddtQRrWqqn5nFyczVKaie28f3kDkHWkHtURSLE` |
| Aldrin V2 | `CURVGoZn8zycx6FXwwevgBTB2gVvdbGTEpvMJDbgs2t4` |
| Saros (AMM) | `SSwapUtytfBdBn1b9NUGG6foMVPtcWgpRU32HToDUZr` |
| FluxBeam | `FLUXubRmkEi2q6K3Y9kBPg9248ggaZVsoSFhtJHSrm1X` |
| Cropper | `H8W3ctz92svYg6mkn1UtGfu2aQr2fnUFHM1RhScEtQDt` |
| DexLab | `DSwpgjMvXhtGn6BsbqmacdBZyfLj6jSWf3HJpdJtmg6N` |
| xOrca | `StaKE6XNKVVhG8Qu9hDJBqCW3eRe7MDGLz17nJZetLT` |
| Sanctum (Pool Router) | `SPoo1Ku8WFXoNDMHPsrGSTSG1Y47rzgn41SLUNakuHy` |
| Sanctum Router | `SPMBzsVUuoHA4Jm6KunbsotaahvVikZs1JyTW6iJvbn` |
| Sanctum Staking | `stkitrT1Uoy18Dk1fTrgPw8W6MVzoCfYoAFT4MLsmhq` |
| Penguin | `PSwapMdSai8tjrEXcxFeQth87xC4rRsa4VA5mhGhXkP` |
| Quantum | `QuaNtZsgYRe5Z9Bk4LZ4cTD9tbkVoyCNf1R2BN9bBDv` |
| AlphaQ | `ALPHAQmeA7bjrVuccPsYPiCvsi428SNwte66Srvs4pHA` |
| Aquifer | `AQU1FRd7papthgdrwPTTq5JacJh8YtwEXaBfKU3bTz45` |
| WhaleStreet | `FW6zUqn4iKRaeopwwhwsquTY6ABWLLgjxtrC3VPnaWBf` |
| SolFi | `SoLFiHG9TfgtdUXUjWAxi3LtvYuFyDLVhBWxdMZxyCe` |
| SolFi V2 | `SV2EYYJyRz2YhfXwXnhNAevDEui5Q6yrfyo13WtupPF` |
| Solayer | `endoLNCKTqDn8gSVnN2hDdpgACUPWHZTwoYnnMybpAT` |
| Solayer (endoSOL) | `endoLNCKTqDn8gSVnN2hDdpgACUPWHZTwoYnnMybpAT` |
| StepN (Doarswap) | `Dooar9JkhdZ7J3LHN3A7YCuoGRUggXhQaG4kijfLGU2j` |
| TaurusFi | `9VX8EKBg6vM6tA68xaDsPkbrx26XConZjkQmhVApUptc` |
| LemmingsFi | `BQEJZUB4CzoT6UhRffoCkqCyqQNrCPCSGHcPEmsdbEsX` |
| HumidiFi | `9H6tua7jkLhdm3w8BvgpTn5LZNU7g4ZynDmCiNN3q6Rp` |
| OneDEX | `DEXYosS6oEGvk8uCDayvwEZz4qEyDJRf9nFgYCaqPMTm` |
| RunnerRodeo | `runnrXXdsSRkdueCRYxKDvSWfv6nAnrG5dcM29qj1HA` |
| VaultLiquidUnstake | `2rU1oCHtQ7WJUvy15tKtFvxdYNNSc3id7AzUcjeFSddo` |
| Jupiter Lend Earn | `jup3YeL8QhtSx1e253b2FDvsMNC87fDrgQZivbrndc9` |
| Jupiter RFQ V2 | `fd3nMFYTQjX1yr5ER8u7tPdHJB7qt8RpDpNtLQX2Br5` |

---

## 额外组件 IDL

项目集成相关的子程序/组件 IDL，不在 Jupiter 路由 DEX 列表内，但逆向分析时有参考价值。

### Meteora 组件

| 文件 | 说明 |
|------|------|
| `meteora_damm_v1.json` | Meteora DAMM V1 |
| `meteora_damm_v2_sdk.json` | Meteora DAMM V2（SDK 版本） |
| `meteora_dynamic_amm.json` | Meteora Dynamic AMM |
| `meteora_vault.json` | Meteora Dynamic Vault |
| `meteora_alpha_vault.json` | Meteora Alpha Vault |
| `meteora_locker.json` | Meteora Locker |
| `meteora_m3m3.json` | Meteora M3M3 (Stake-for-Fee) |

### Jupiter 核心

| 文件 | 说明 |
|------|------|
| `jupiter_aggregator.json` | Jupiter Aggregator（旧版） |
| `jupiter_aggregator_v6.json` | Jupiter Aggregator V6 |
| `jupiter_dex_interfaces.json` | Jupiter DEX 接口定义 |
| `jupiter_cpi.json` | Jupiter CPI 接口 |
| `jupiter_core.json` | Jupiter Core |
| `jupiter_lend_lending.json` | Jupiter Lend — Lending |
| `jupiter_lend_flashloan.json` | Jupiter Lend — Flashloan |
| `jupiter_lend_liquidity.json` | Jupiter Lend — Liquidity |
| `jupiter_lend_vaults.json` | Jupiter Lend — Vaults |
| `jupiter_lend_oracle.json` | Jupiter Lend — Oracle |
| `dca.json` | Jupiter DCA |

### Raydium 组件

| 文件 | 说明 |
|------|------|
| `raydium_idl_amm.json` | Raydium AMM（raydium-idl 官方）|
| `gamma_swap_amm_v3.json` | Raydium CLMM V3（gamma-swap）|
| `gamma_swap_dlmm.json` | Meteora DLMM（gamma-swap 副本）|

### Sanctum 组件

| 文件 | 说明 |
|------|------|
| `sanctum_flat_fee.json` | Sanctum Flat Fee Pricing |
| `sanctum_generic_calc.json` | Sanctum Generic Pool Calculator |
| `sanctum_marinade_calc.json` | Sanctum Marinade Calculator |
| `sanctum_spl_calc.json` | Sanctum SPL Calculator |

### Kamino

| 文件 | 说明 |
|------|------|
| `kamino.json` | Kamino Lending |

### Staked SOL / LST

| 文件 | 说明 |
|------|------|
| `stakedex.json` | Stakedex Interface |
| `stakedex_deposit_sol.json` | Stakedex Deposit SOL |
| `stakedex_deposit_stake.json` | Stakedex Deposit Stake |
| `stakedex_withdraw_sol.json` | Stakedex Withdraw SOL |
| `stakedex_withdraw_stake.json` | Stakedex Withdraw Stake |
| `marinade.json` | Marinade Finance |

### 其他

| 文件 | 说明 |
|------|------|
| `openbook_v1.json` | OpenBook V1（Drift 集成版）|
| `openbook_twap.json` | OpenBook TWAP（MetaDAO）|
| `manifest_wrapper.json` | Manifest Wrapper |
| `plasma_amm.json` | Plasma（Ellipsis Labs）|
| `aldrin_v1_pools.json` | Aldrin V1 Pools |
| `aldrin_farming.json` | Aldrin Farming |
| `aldrin_dtwap.json` | Aldrin DTWAP |
| `crema_clmm_v2.json` | Crema CLMM V2 |
| `cykura.json` | Cykura (Cyclos Core) |
| `goosefx_controller.json` | GooseFX Controller |
| `hylo_exchange_v2.json` | Hylo Exchange（SDK 版本）|
| `hylo_stability_pool_v2.json` | Hylo Stability Pool（SDK 版本）|
| `saros_dlmm_rewarder.json` | Saros DLMM Rewarder |
| `mango_v4.json` | Mango V4 |
| `merkle_distributor.json` | Merkle Distributor |
| `govern.json` | Govern（Tribeca）|
| `m_swap_v2.json` | M Swap V2 |

---

## 统计

| 项目 | 数量 |
|------|------|
| IDL 文件总数 | **105** |
| Jupiter 路由 DEX 覆盖 | **47 / 90** |
| 覆盖率 | **52%** |
| 无 IDL（闭源/非Anchor） | **43 / 90** |

## IDL 获取方式

| 来源 | 数量 | 说明 |
|------|------|------|
| Solscan API（链上 Anchor IDL） | ~35 | `anchor idl fetch` / Solscan `anchor_idl` 端点 |
| 官方开源仓库 | ~50 | 从 GitHub 开源 SDK/程序仓库提取 |
| anchor-cli | 1 | `anchor idl fetch` CLI 直接获取 |
| 项目内嵌 IDL | ~19 | Jupiter 项目自身 `amm/`、`markets-cache/` 等目录 |
