================================================================================
          DONUTSMP COMPLETE 23-MODULE ECONOMY SCRIPT PACK (v1.0.0)
                           By OrbitOmen & StuffStock
================================================================================

This pack includes 23 high-performance, modular Skript modules designed to create
a complete, high-tier multiplayer SMP & Factions economy.

--------------------------------------------------------------------------------
1. PACK CONTENTS (23 SCRIPT MODULES)
--------------------------------------------------------------------------------
  01. economy_core.sk     - Master transaction engine, wallet math & safety checks
  02. auction_house.sk    - Player auction house GUI (/ah) with search & expired bin
  03. baltop.sk           - Paginated balance leaderboards with cached performance
  04. bank.sk             - Virtual banking vaults with interest & death protection
  05. banknotes.sk        - Signed, physical paper currency banknotes (/withdraw)
  06. blackmarket.sk      - Rotating timed contraband merchant GUI with rare loot
  07. bounties.sk         - Player head-hunting bounties with assassin kill rewards
  08. chestshops.sk       - Sign-driven chest shops with left-click buy / right-click sell
  09. clanbank.sk         - Shared clan & faction treasury banking repository
  10. dailyrewards.sk     - Consecutive login streak bonuses with scaled multipliers
  11. delivery.sk         - Offline player mail, parcel gifting & courier boxes
  12. dynamic_sell.sk     - Algorithmic supply/demand shop (/sell hand, /sell all)
  13. gambling.sk         - 50/50 PvP coinflip wagering listings with animation
  14. jackpot.sk          - Hourly server-wide lottery jackpot pot with ticket odds
  15. jobs.sk             - Career professions (Miner, Woodcutter, Farmer, Hunter)
  16. orders.sk           - Wholesale purchase buy orders & B2B bulk trading
  17. rankup.sk           - In-game currency rank advancement ladder (/rankup)
  18. salvage.sk          - Disenchant & recycle unwanted armor into raw minerals
  19. scratchcards.sk     - Consumable lottery scratch cards with up to 10x payouts
  20. sellchests.sk       - Smart containers that auto-sell placed contents
  21. shop.sk             - Interactive multi-category server shop GUI (/shop)
  22. stockmarket.sk      - Fluctuating virtual company shares with dividend payouts
  23. trade.sk            - Dual-sided shift-click trading window with confirmation

--------------------------------------------------------------------------------
2. INSTALLATION GUIDE
--------------------------------------------------------------------------------
1. Ensure your server has Skript installed:
   - Paper / Purpur / Spigot 1.20+
   - Skript 2.8+ (https://github.com/SkriptLang/Skript)
   - Optional: Vault + EssentialsX / economy bridge if using Vault sync.

2. Open your server directory:
   plugins/Skript/scripts/

3. Extract the contents of this zip (the 'economy/' folder containing the .sk files)
   directly into plugins/Skript/scripts/.

4. Recommended load order:
   Load the core first:
     /sk reload economy/economy_core
   Then reload all remaining modules:
     /sk reload economy/

--------------------------------------------------------------------------------
3. SUPPORT & CONFIGURATION
--------------------------------------------------------------------------------
Every script contains an 'options:' block at the top of the file where you can
tweak currency prefixes, taxes, interest rates, cooldowns, and permissions.
================================================================================
