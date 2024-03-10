# Jouleverse Governance Stage 0

Jouleverse治理系统。Stage 0 先以多签钱包+github文档的方式模拟(repo: Jouleverse/open-meetings/governance-sim。未来逐步开发全链上治理合约等(repo: Jouleverse/governance)。

投票权(veJ, 全称voting-escrow Joule)由向多签钱包中质押的WJ (wrapped Joule)进行Proof-of-Stake证明。每1万枚WJ质押，可换取1个投票权(veJ)。

质押锁定期为最后一次权力行动（包括补充质押、参与投票等涉及veJ的变动或权力行使的行为）当日，向后顺延1年。为防范治理攻击，不允许提前解质押。

---

投票权PoS合约地址：0xB17b6812f3Ed0eb0Df6e9F1D308C975B5daa8dC3

CGC投票权质押登记表：https://docs.qq.com/form/page/DTEdBb2Jjb2dpTUVt

---

质押流程：
1. 确保你的地址已经获得了JTI认证。
2. 将足额的WJ（整数万，不接受零头）放到该认证地址上。
3. 用该认证地址向投票权PoS合约地址转入 N 万枚WJ。
4. 填写《CGC投票权质押登记表》。
5. 通知审核人（教链或Koant）审核质押登记，确认无误后更新github，公示投票权。

投票权公示：（表格更新日期：2024/3/10）

微信身份 | JTI可信认证编号 | 登记投票权数量 | 投票权委托情况 | 实际投票权数量 | 最后行动日
-|-|-|-|-|-
Koant | 3 | 10 | - | 10 | 2024/3/10
火星 | 29 | 20 | - | 20 | 2024/3/10
狮子猫 | 109 | 5 | - | 5 | 2024/3/10

---

投票流程：


