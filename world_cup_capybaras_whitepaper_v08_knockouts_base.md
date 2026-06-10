# World Cup Capybaras Whitepaper v0.8 - Knockouts/Base Update

**Project name:** World Cup Capybaras  
**Game direction:** Knockouts Capybaras / knockout-style game  
**Version:** v0.8  
**Status:** Draft for publication  
**Chain:** Base  
**Supply:** 1,500 NFTs  
**Mint date:** TBD  
**Mint price:** TBD  
**Mint platform:** TBD

![World Cup Capybaras whitepaper scene](assets/whitepaper/whitepaper-office-scene.png)

---

## 1. Project Summary

World Cup Capybaras is a football-inspired NFT collection built around a tournament-style community game.

The public project name remains **World Cup Capybaras**. The updated game direction is **Knockouts Capybaras**, a simplified knockout-style format designed around team assignment, group representation, knockout qualification, elimination-stage results, snapshots, listing eligibility, and reward-share weighting.

The collection is planned for **Base**. Mint date, mint price, and mint platform are currently **TBD**.

Before reveal, NFTs may display a generic pre-reveal Capybara artwork. After reveal, each NFT will show its final artwork and assigned national team.

![World Cup Capybaras project logo](assets/whitepaper/project-logo-glow.png)

---

## 2. Launch Configuration

| Item | Current Definition |
| --- | --- |
| Public project name | World Cup Capybaras |
| Game direction | Knockouts Capybaras / knockout-style game |
| Chain | Base |
| Total supply | 1,500 NFTs |
| Mint date | TBD |
| Mint price | TBD |
| Mint platform | TBD |
| Reveal timing | TBD; after mint closes and before the game starts |
| Active supply | NFTs minted before the official cutoff |
| Unsold NFTs | Do not participate in rewards |

The project will not treat unsold NFTs as eligible game participants. Only NFTs that are part of the active minted supply can participate in tournament reward logic.

---

## 3. Team Allocation

The collection will include **1,500 NFTs** distributed across **48 national teams** as evenly as possible.

Because 1,500 divided by 48 is not an integer, exact equal allocation is impossible. The closest even distribution is:

- **36 teams with 31 NFTs each** = 1,116 NFTs
- **12 teams with 32 NFTs each** = 384 NFTs

Total: **1,500 NFTs**.

The final team allocation will be confirmed before reveal. Once revealed, each NFT's assigned team is final.

The project will not allow users to choose a team after seeing final metadata, because that would break the fairness of the game.

Each NFT is expected to include both:

- its assigned group; and
- its final team representation after reveal.

The full collection can represent all 48 teams, but reward logic is focused on the teams that reach and progress through the knockout/elimination stage.

---

### 3.1 Group Stage and Knockout Qualification

The World Cup 2026 tournament structure used as game context has:

- **12 groups of 4 teams**;
- the **top 2 teams from each group** qualifying directly; and
- the **8 best third-place teams overall** also qualifying.

This creates a **32-team knockout stage**.

For World Cup Capybaras, the group stage matters because it determines which represented teams reach the knockout bracket. The reward phase is intended to focus on knockout/elimination-stage outcomes, not on every group-stage match equally.

The project may publish a more detailed reward calendar before gameplay starts, including which knockout rounds are active reward events and how snapshots apply to each event.

![World Cup Capybaras knockout stadium](assets/whitepaper/stadium-knockouts-banner.png)

---

## 4. Captain NFTs

Each team will include **1 Captain NFT**.

Captain NFTs are special team NFTs with a reward weight of **2 reward shares** when eligible.

Reward share weighting:

| NFT type | Eligible reward share weight |
| --- | ---: |
| Standard eligible NFT | 1 share |
| Eligible Captain NFT | 2 shares |

Captains do not bypass any game rule, snapshot rule, listing rule, wallet-holding rule, or eligibility rule. A Captain NFT must satisfy the same eligibility requirements as any other NFT to receive rewards.

If a Captain NFT is not eligible for a matchday or round, it receives no reward for that event.

---

## 5. Reward Share Calculation

When a reward is distributed for an eligible matchday or round, the reward pool for that event is divided by total eligible reward shares.

Example:

If an eligible winning group includes:

- 10 standard eligible NFTs
- 1 eligible Captain NFT

Then total reward shares are:

- 10 standard NFTs x 1 = 10 shares
- 1 Captain NFT x 2 = 2 shares
- **Total = 12 reward shares**

The Captain receives 2 shares. Each standard NFT receives 1 share.

This system lets Captains receive double the reward share while keeping eligibility rules consistent across all NFTs.

![World Cup Capybaras community rewards](assets/whitepaper/claims-community-rewards.png)

---

## 6. Reveal and Active Supply

The collection will use a delayed reveal.

Before reveal, NFTs may display a generic pre-reveal Capybara artwork.

![World Cup Capybaras pre-reveal artwork](assets/pre-reveal/pre-reveal-01.png)

After mint closes, the active supply will be confirmed and the reveal process will begin. Reveal timing is currently **TBD**, but reveal is intended to happen after mint closes and before the game starts.

Once reveal happens, each NFT will show its final Capybara artwork, assigned team, and relevant game traits.

The revealed team assignment is final.

Only NFTs minted before the official cutoff are part of the active supply for the game. Unsold NFTs do not participate in rewards. No NFT outside the active minted supply is eligible for tournament rewards.

---

## 7. Metadata Traits

Final metadata may include, but is not limited to:

- Team
- Team allocation group
- Group
- Final team representation
- Captain status
- Reward weight
- Game format
- Artwork traits

Expected game-specific traits:

| Trait | Example |
| --- | --- |
| Team | Brazil |
| Group | Group A / B / C, etc. |
| Final Team Representation | Brazil |
| Captain | Yes / No |
| Reward Weight | 1 or 2 |
| Game Format | Knockouts Capybaras |
| Chain | Base |

The project may adjust non-game artistic traits before final metadata publication. Team assignment, group representation, Captain status, and reward weight must be handled consistently with the published rules.

---

## 8. Matchday Snapshots and Listing Eligibility

For each active reward event, the project may take two official snapshots:

1. **Pre-event snapshot**
2. **Post-event snapshot**

After the post-event snapshot, the project will calculate preliminary eligible NFTs based on:

- the NFT being held by the same wallet in both snapshots;
- the NFT's assigned team qualifying for, participating in, or advancing through the active knockout-stage reward event, depending on the published event rules;
- the NFT being part of the active minted supply.

The project will then verify whether any preliminary eligible NFT was listed for sale at any point during the event window.

If an NFT was listed for sale at any time between the pre-event snapshot and the post-event snapshot, that NFT is not eligible to receive that event's reward.

The event window begins at the official pre-event snapshot and ends at the official post-event snapshot.

Final event eligibility is confirmed only after listing verification is completed.

![World Cup Capybaras snapshot and listing rules](assets/whitepaper/snapshot-rules-board.png)

---

## 9. Reward Eligibility

An NFT is not automatically eligible for a reward simply because its assigned team performs well.

To be eligible for a knockout-stage event or round reward, an NFT must satisfy the active published criteria, including:

- being part of the active minted supply;
- being held by the same wallet in the pre-event and post-event snapshots;
- having an assigned team that qualifies under that event's knockout-stage result rules;
- not being listed for sale at any time during the event window;
- satisfying any additional published eligibility rule for that event.

Captain NFTs follow the same eligibility rules. The only difference is reward-share weight: an eligible Captain counts as 2 reward shares instead of 1.

---

## 10. Listing Rule

NFTs listed for sale during an active reward event window are not eligible for that event's reward.

This rule is intended to discourage short-term listing behavior during active gameplay windows and protect the game logic from abuse.

The listing window begins at the official pre-event snapshot and ends at the official post-event snapshot.

A listed NFT may still participate in future events if it satisfies the future event's eligibility rules.

---

## 11. Reward Pool Notes

Reward pool details, reward funding, payout mechanics, payout timing, and operational procedures may be published separately before the game starts.

The project may use manual or automated verification workflows to calculate eligibility. Final reward eligibility is confirmed only after the project completes snapshot review, wallet review, team-result review, and listing verification.

No reward is guaranteed unless all published eligibility requirements are satisfied and the project confirms final eligibility.

---

## 12. Community and Discord

The Discord server is the main community coordination space for:

- official announcements;
- rules and security updates;
- mint information;
- team selection discussions;
- raffle and collab information;
- reward and knockout-stage updates.

Members should only trust links posted in official channels. The team will never ask for seed phrases, private keys, wallet passwords, or secret recovery phrases.

---

## 13. Safety and Anti-Scam Rules

Users should follow these safety rules:

- Never share a seed phrase or private key.
- Never trust unsolicited DMs claiming to be support.
- Only use links from official project channels.
- Verify mint information before interacting with any contract or page.
- Treat fake mint links, fake support accounts, and fake airdrops as scams.

The project may update safety rules as needed before mint and before gameplay starts.

![World Cup Capybaras classic hero](assets/whitepaper/hero-knockouts-capybara.png)

---

## 14. Non-Affiliation Disclaimer

World Cup Capybaras is not affiliated with FIFA, the FIFA World Cup, national teams, federations, leagues, sponsors, players, or official tournament organizers.

All football, country, and tournament-inspired references are used as part of an independent community collectibles game concept.

---

## 15. Risk Disclaimer

NFTs involve risk. Participation in the project should not be considered financial advice, investment advice, or a guarantee of profit.

Mint details, marketplace behavior, network fees, reward mechanics, eligibility verification, and project operations may involve technical and operational risks.

Users are responsible for their own wallet security and transaction decisions.

---

## 16. Version History

| Version | Summary |
| --- | --- |
| v0.6 | Earlier Ethereum/Highlight-oriented draft |
| v0.7 | Mint/reveal and snapshot/listing clarification draft |
| v0.8 | Knockouts/Base update: Base chain, mint date TBD, mint price TBD, mint platform TBD, closest-even allocation, Captain NFTs, reward-share weighting, group representation, and knockout-stage reward focus |

---

## 17. Current Status

This v0.8 whitepaper is the current project direction draft.

Before final launch, the project should confirm:

- mint platform;
- mint date;
- mint price;
- final reveal process;
- final snapshot timing;
- final knockout reward event schedule;
- final reward pool mechanics;
- final contract and metadata deployment details.
