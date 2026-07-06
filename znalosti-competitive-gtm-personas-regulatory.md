# Competitive Analysis, GTM Strategy, User Personas & Regulatory - Znalostní báze

## 1. COMPETITIVE LANDSCAPE ANALYSIS

### A. Betting Exchanges (P2P Model)

#### **Betfair Exchange**
**Model:**
- Největší a nejpopulárnější betting exchange na světě (založeno 2000)
- Peer-to-peer sports betting - uživatelé sází jeden proti druhému
- Platforma pouze facilituje, nikdy nepřebírá pozici na výsledku

**Jak funguje:**
- "Back" bet = sázka, že se něco stane
- "Lay" bet = sázka, že se něco NESTANE
- Každý back bet potřebuje matching lay bet
- Kurzy se neustále mění podle nabídky/poptávky (jako burza)

**Revenue model:**
- Komise na výhry: **3-5%** (typicky)
- Neberou riziko sázek (nejsou bookmaker)

**Výhody pro uživatele:**
- Kurzy často **5-20% lepší** než u tradičních bookmakerů
- Možnost "lay" bets (vsadit proti)
- Plná transparentnost trhu

**Slabé stránky:**
- Komise jedí do zisku
- Komplexnější pro běžné uživatele
- Při lay bets může být ztráta mnohem větší než stake

---

#### **Smarkets**
**Model:**
- Moderní betting exchange, konkurent Betfairu
- Peer-to-peer platforma
- Focus na nižší komise

**Revenue model:**
- **2% komise** na čisté výhry (industry-low)
- Pouze pokud uděláte čistý zisk na marketu
- Pokud loss → žádná komise

**Diferenciace:**
- Výrazně nižší komise než Betfair (2% vs. 5%)
- Modernější UI/UX
- True market odds (bez bookmaker margin)

**Positioning:**
- "Fairer way to bet and trade"
- Transparentnost a low fees

---

### B. Sports Prop Firms (Challenge-Based Model)

#### **BankrollU** - "The First Sports Betting Prop Firm"

**Model:**
- Adaptace FTMO modelu na sports betting
- Challenge → Evaluation → Funded account
- Uživatelé platí za challenge, ne za sázky

**Jak funguje:**
- 2-phase challenge testuje schopnost dosáhnout profit targetů při risk managementu
- Phase 1: 25% profit target za 30 dní
- Phase 2: 19% profit target za 30 dní
- Úspěšní dostanou funded account až **€50,000**
- Profit share: **75%** pro uživatele

**Revenue streams:**
- Challenge fees (primární - většina selhává)
- 25% profit share z funded traders

---

#### **MySportsFunding** - European Leader

**Model:**
- Evropsky zaměřená sports betting prop firma
- Challenge-based evaluation
- Až €50,000 funded accounts

**Features:**
- Structured targets (profit goals + risk limits)
- Simulated environment pro evaluation
- Real profit payouts pro úspěšné

---

#### **WinningEdge.io, BETfunded, Trading Buddy**
**Common features:**
- Challenge fees model
- Simulated environments
- Profit share 70-90%
- Bankroll discipline requirements

**Market size:**
- Global sports betting market: **$100.9B (2024)** → **$187.4B (2030)**
- CAGR: **11%**

**Reality check:**
- Většina uživatelů NEPROJDE konzistentně, pokud nemají real edge
- Funded account nevytváří betting skill - pouze strukturuje existing skill
- Rizika: challenge fees, time cost, repeated resets, payout disputes

---

### C. Fantasy Sports (Skill-Based Gaming)

#### **DraftKings & FanDuel**

**Business model:**
- **Skill-based game** positioning (ne gambling)
- Daily Fantasy Sports (DFS) jako user acquisition funnel
- Následná cross-sell do sportsbook (vyšší value)

**Revenue model:**
- Fee-based income (entry fees)
- Nižší exposure k user outcomes než gambling
- Leveraging participant knowledge a player skills

**Growth strategy:**
- DFS jako massive user acquisition funnel
- Large engaged user base → sportsbook conversion
- Trusted brand + payment infrastructure = head start při legalizaci

**Marketing:**
- Aggressive campaigns (2 týdny do NFL season: **$107M** combined spend)
- High-profile sponsorships (MLB má stake v DraftKings, NBA v FanDuel)
- Influencer marketing
- Social media presence
- Data analytics pro personalizaci

**Technology:**
- AI/ML pro fraud detection
- Personalized recommendations
- Cloud-Native, Microservices Architecture
- Optimalizace conversions

**Pozice:**
- Úspěšná obhajoba jako "skill game" (ne gambling)
- Cesta do regulated jurisdictions
- Pathway od DFS → sportsbook

---

### D. Prediction Markets (Politics/Events)

#### **PredictIt**
**Focus:** Primárně politické trhy (ne sports)
**Model:** Academic project, non-profit
**Regulatory:** CFTC "no action" letter (originally), litigation 2020s
**Status:** Won case v 2023

**Relevance:**
- Ukazuje regulatory complexity prediction markets
- Sports prediction markets jsou 85%+ trading volume na Kalshi
- Politics vs. sports = různé regulatory treatments

---

### E. COMPETITIVE GAPS & OPPORTUNITIES

**Co chybí na trhu:**

1. **FTMO model aplikovaný na sports + prediction markets**
   - Žádný major player nekombinuje prop firm challenge model s P2P prediction markets
   - Betting exchanges mají P2P, ale ne challenge/funding struktur
   - Prop firmy mají challenge, ale tradiční betting (ne prediction markets)

2. **Community-first approach**
   - Tipsport má Tiket Arena (sdílení), ale pro tradiční betting
   - Discord/Reddit communities jsou grassroots, ne integrated v product
   - Chybí social prediction marketplace s built-in sharing/learning

3. **Skill-based positioning s regulatory clarity**
   - DFS má skill positioning, ale není to pure prediction market
   - Prediction markets mají regulatory fight (Kalshi vs. CFTC)
   - Demo/simulated capital approach (FTMO style) minimalizuje gambling classification

4. **Flashscore-like UX pro prediction markets**
   - Polymarket má P2P markets, ale ne sports-first UX
   - Flashscore má amazing sports UX, ale ne betting/markets
   - Chybí kombinace: real-time sports data + prediction markets + social

5. **Mobile-first Gen Z experience**
   - Current players (Betfair, prop firms) jsou desktop-heavy
   - Gen Z/Millennials chtějí mobile (90% millennials, 84% Gen Z)
   - Opportunity pro modern, gamified, social mobile experience

---

## 2. USER PERSONAS - Cílové segmenty

### **PERSONA 1: "Analytical Alex" - Serious Sports Bettor**

**Demographics:**
- Věk: 25-35
- Pohlaví: Primárně muži (75%), ale growing female segment
- Lokace: Urban, tech-savvy regions
- Income: Middle to upper-middle class
- Education: College educated

**Psychographics:**
- Analytický mindset
- Data-driven decision making
- Hledá "edge" v betting markets
- Frustrated s bookmaker margins
- Respektuje skill-based competition

**Behavioral traits:**
- Sleduje sports analytics (xG, advanced stats)
- Aktivní na Reddit (r/sportsbook), Discord betting communities
- Používá multiple sportsbooks pro line shopping
- Trackuje svoje performance (ROI, units)
- Mobile-first (90%+ sázek přes app)

**Pain points:**
- Bookmaker margins jedí profit
- Limited bankroll pro scaling strategy
- Risk of account limiting pokud je příliš úspěšný
- Frustrující gambling stigma (skill vs. luck debate)

**Goals:**
- Prokázat betting skill
- Získat access k větší bankroll
- Monetizovat sports knowledge
- Build reputation v betting community

**Value proposition pro naši platformu:**
- Challenge structure validates skill (ne luck)
- P2P markets = better prices než bookmakers
- Funded account = scale bez own capital risk
- Community recognition (leaderboards, shareable portfolios)

**Acquisition channels:**
- Sports analytics content (SEO)
- Reddit/Discord communities
- Sports betting influencers
- YouTube tutorials (betting strategies)

**Quote:** *"I know I have an edge, but bookmakers limit me when I win. I need a platform that rewards skill, not punishes it."*

---

### **PERSONA 2: "Social Sam" - Sports Enthusiast**

**Demographics:**
- Věk: 21-28 (Gen Z focus)
- Pohlaví: Mix (growing female participation)
- Lokace: Urban, college towns
- Income: Entry to mid-level
- Education: College student nebo recent grad

**Psychographics:**
- Sports fanatic (watches games with friends)
- Social bettor - betting enhances viewing experience
- FOMO-driven (sees friends winning)
- Entertainment > serious profit
- Values community a shared experience

**Behavioral traits:**
- Sází with friends (social activity)
- 84% mobile app usage
- Follows sports influencers (ESPN, social media)
- **86% influenced by sports social media posts**
- Likes sharing wins (Instagram stories, Twitter)
- Prefers parlays/accumulators (higher excitement)

**Pain points:**
- Loses money at traditional sportsbooks
- Lacks knowledge/strategy (casual approach)
- Gambling losses feel wasteful
- Wants to learn but overwhelmed

**Goals:**
- Make sports watching more engaging
- Learn betting skills from community
- Occasional wins to fund hobby
- Social recognition (flex wins)

**Value proposition:**
- Free/low-cost challenges (learning opportunity)
- Community learning (follow successful bettors)
- Social features (share predictions, compare with friends)
- Gamification (achievements, streaks, levels)

**Acquisition channels:**
- Social media (Instagram, TikTok, Twitter)
- Sports influencer partnerships
- Referral programs (friend invites)
- Campus marketing, sports bars

**Quote:** *"Betting makes games more fun to watch with friends. I wish there was a way to learn from people who actually know what they're doing."*

---

### **PERSONA 3: "Crypto Chris" - Tech/DeFi Early Adopter**

**Demographics:**
- Věk: 22-32
- Pohlaví: Predominately male
- Lokace: Global (crypto-friendly regions)
- Income: Variable (crypto natives)
- Education: Tech-savvy, often self-taught

**Psychographics:**
- Crypto/blockchain enthusiast
- Early adopter mindset
- Values decentralization a transparency
- Speculation mindset (crypto trading → prediction markets)
- Anti-establishment (prefers P2P over centralized)

**Behavioral traits:**
- Active in crypto communities (CT - Crypto Twitter, Discord)
- Uses Polymarket, Kalshi
- Comfortable with wallets, USDC, blockchain
- Speculates across: crypto, stocks, prediction markets
- High-risk tolerance

**Pain points:**
- Polymarket má liquidity issues sometimes
- Current prediction markets lack sports depth
- Wants better UX než current crypto platforms
- Seeks alpha (information edge)

**Goals:**
- Profit from prediction market inefficiencies
- Be early to new platforms (potential airdrops, tokens)
- Transparent, trustless systems
- Portfolio diversification (sports = new asset class)

**Value proposition:**
- Hybrid model: crypto-friendly + fiat on-ramps
- Transparent P2P markets (better than bookmakers)
- Potential for tokenomics/airdrops (future)
- Real-time odds = trading opportunities

**Acquisition channels:**
- Crypto Twitter influencers
- Polymarket/Kalshi user crossover
- Reddit (r/cryptocurrency, r/sportsbook overlap)
- Discord communities (crypto + sports)

**Quote:** *"I trade prediction markets because they're more efficient than bookies. If there was a platform with better liquidity and sports focus, I'd be all in."*

---

### **PERSONA 4: "FTMO Trader Tom" - Existing FTMO User (Crossover)**

**Demographics:**
- Věk: 28-40
- Pohlaví: Mostly male
- Lokace: Global (existing FTMO users)
- Income: Variable (prop traders)
- Education: Finance/trading background

**Psychographics:**
- Challenge-based mindset (used to FTMO structure)
- Risk management discipline
- Skill-based competition appeal
- Familiar with prop funding model
- Potential sports interest (crossover hobby)

**Behavioral traits:**
- Already passed FTMO challenge (proven discipline)
- Understands profit targets, drawdown limits
- Comfortable with demo → funded progression
- Tracks performance metrics
- May watch sports casually

**Pain points:**
- Trading can be isolating/stressful
- Looking for diversification
- Sports = more intuitive than forex/stocks for some

**Goals:**
- Apply trading discipline to new domain
- Diversify income streams
- Leverage existing FTMO relationship

**Value proposition:**
- Familiar model (challenge → funded)
- Leverage existing risk management skills
- Separate from trading (mental break)
- FTMO brand trust transfer

**Acquisition channels:**
- FTMO email/platform cross-promotion
- FTMO community forums
- Existing user base (warm leads)

**Quote:** *"I've passed FTMO challenges for trading. I love sports - why not apply the same discipline to sports predictions?"*

---

### **PERSONA SUMMARY - Prioritization**

**Primary target (MVP):**
1. **Analytical Alex** (serious bettors) - highest LTV, most aligned with challenge model
2. **Crypto Chris** (early adopters) - help with initial traction, buzz

**Secondary (expansion):**
3. **Social Sam** (Gen Z enthusiasts) - volume play, viral potential, but lower LTV
4. **FTMO Tom** (crossover) - easy acquisition, but smaller pool

**Marketing message per persona:**
- Alex: *"Prove your edge. Get funded. Keep 80%."*
- Sam: *"Learn from the best. Bet smarter. Win together."*
- Chris: *"P2P sports markets. No bookmaker. Just skill."*
- Tom: *"Your next challenge. Same discipline. New market."*

---

## 3. REGULATORY QUICK SCAN - Základní přehled

### **A. Klíčové právní kategorie**

#### **1. Gambling vs. Skill-Based Gaming**

**Legal test (USA - majority jurisdictions):**
- **"Dominant Factor" approach**
- Pokud **skill dominuje** nad chance → není to gambling
- Pokud **chance dominuje** → je to gambling (regulace)

**Implikace:**
- DraftKings/FanDuel úspěšně argumentují "skill-based" pro DFS
- Challenge-based model s profit targets = skill demonstration
- Prediction markets = šedá zóna (market efficiency vs. chance)

---

#### **2. Real Money vs. Demo/Simulated**

**Kritický rozdíl:**
- **Real money gambling** = plná gambling regulace
- **Demo/simulated currency bez cash payouts** = výrazně méně regulace

**FTMO precedent:**
- Demo účty pro challenge
- Reálné výplaty na základě performance (ne gambling winnings)
- Legal v CA, TX, FL pokud "no real money won or lost" tied to outcomes

**Recent regulatory actions:**
- CA, MT, CT, NJ zakázaly "dual-currency sweepstakes" (fake currency → real prizes)
- PA, NY, MI, MD sent cease-and-desist na sweepstakes casinos

**Safe zone:**
- Demo capital pro evaluation (challenge)
- Performance-based rewards (profit share), ne direct betting payouts
- Clear separation: skill evaluation vs. gambling winnings

---

### **B. Geographic Regulatory Overview**

#### **USA**

**Supreme Court 2018:**
- PASPA overturned → states can legalize sports betting
- **37 states + DC + Puerto Rico** mají legalized sports betting (Jan 2024)
- **30 states** legalized online sports betting

**State-by-state variance:**
- Různé tax rates (NJ: 15%, PA: 54% na slots)
- Různé licensing requirements
- Sports betting vs. prediction markets distinctions

**Federal oversight:**
- **CFTC** reguluje prediction markets (event contracts)
- Sports event contracts = "swaps" under CFTC jurisdiction (disputed)
- **85%+ trading volume** na Kalshi je sports events

**Jurisdictional battles:**
- CFTC vs. state gaming boards (ongoing litigation 2026)
- PredictIt fight (won 2023)
- Kalshi sports contracts litigation

---

#### **EU**

**No harmonized law:**
- Each member state sets own rules
- EU directives influence (Services Directive, consumer protection)
- Licensing requirements vary by country

**General approach:**
- Sports betting není criminalized
- Operators need licenses per country
- Online + offline regulated separately

**Examples:**
- UK: Gambling Commission oversight
- Malta: Popular licensing jurisdiction
- Netherlands: Recent online gambling law

---

### **C. Regulatory Strategy pro naši platformu - Doporučení**

#### **Option 1: Demo Capital Model (Recommended pro MVP)**

**Approach:**
- Challenge fáze = **100% simulated/demo capital**
- Uživatelé platí **challenge fee** (ne betting stakes)
- Performance evaluation v controlled environment
- Successful passers dostávají **profit share** based on performance

**Legal classification:**
- **Skill evaluation service** (ne gambling)
- No real money gambling (demo environment)
- Payouts jsou performance-based compensation (jako FTMO)

**Výhody:**
✅ Minimální gambling regulation exposure
✅ Can operate v restrictive jurisdictions (CA, TX, FL)
✅ FTMO precedent (ověřený model)
✅ Focus na skill, ne chance
✅ Jednodušší licensing

**Challenges:**
❌ "Funded" accounts stále demo (ne real P2P betting)
❌ User perception (chtějí "real" betting)
❌ Eventual scaling může vyžadovat real betting integration

---

#### **Option 2: Hybrid Model**

**Approach:**
- Phase 1 & 2 (Challenge + Verification) = **demo capital**
- Phase 3 (Funded) = **real P2P prediction market** access
- Platform facilitates peer-to-peer (exchange model)
- Commission on transactions (ne bookmaker)

**Legal classification:**
- Challenge = skill evaluation
- Funded = **betting exchange** (facilitator, not operator)
- Similar to Betfair/Smarkets model

**Výhody:**
✅ Real betting pro funded users (better engagement)
✅ Exchange model = lower regulatory burden než bookmaker
✅ Challenge phase still skill-focused
✅ Better long-term scalability

**Challenges:**
❌ Vyšší regulatory complexity
❌ Licensing pro betting exchange (per jurisdiction)
❌ P2P liquidity challenges
❌ Oracle problem (settlement)

---

#### **Option 3: Full Compliance Route**

**Approach:**
- Obtain full gambling licenses
- Operate jako regulated sportsbook/exchange
- Challenge model jako marketing feature

**Výhody:**
✅ Maximum legitimacy
✅ Access k všem markets
✅ Institutional partnerships možné

**Challenges:**
❌ Velmi expensive (licensing fees)
❌ Lengthy approval processes
❌ Omezená geographic reach (per-jurisdiction licenses)
❌ High compliance overhead
❌ Not viable pro MVP/startup

---

### **D. Regulatory Recommendations - Action Items**

**Pro case study prezentaci:**

1. **Lead s Demo Capital Model (Option 1)**
   - Lowest regulatory risk
   - Fastest time to market
   - FTMO precedent
   - Emphasize **skill evaluation** positioning

2. **Address path to real betting (Option 2)**
   - Demo pro validation
   - Real P2P markets pro growth
   - Betting exchange model (facilitator)

3. **Launch market selection:**
   - Start v crypto-friendly / skill-gaming friendly jurisdictions
   - Avoid heavily regulated markets initially (NY, some EU states)
   - Consider: Malta, Gibraltar (EU), select US states

4. **Compliance priorities:**
   - Legal counsel specializing v skill-gaming + prediction markets
   - Clear Terms of Service (skill-based, no guaranteed returns)
   - Age verification (18+/21+ depending on jurisdiction)
   - Responsible gaming features (even in demo environment)
   - FTMO compliance team collaboration

5. **Messaging:**
   - **"Skill evaluation platform"** (ne gambling site)
   - "Sports prediction challenge" (ne betting challenge)
   - "Performance-based rewards" (ne gambling winnings)
   - "Demo environment" (transparent o simulated nature)

---

## 4. GO-TO-MARKET STRATEGY

### **A. Launch Goals & Timeline**

**First 1,000 users: 90 days**

**Why 1,000?**
- Critical mass pro organic referrals
- Sufficient data pro product iteration
- Proof of concept pro investors
- Community starts self-sustaining

**Acquisition cost benchmark:**
- Sports betting industry: **$200-500 per user**
- Our target: **<$100 per user** (organic-first approach)

---

### **B. Pre-Launch (Days -30 to 0)**

#### **1. Community Seeding**

**Reddit strategy:**
- Engage v existujících communities: r/sportsbook, r/sportsbetting, r/fantasysports
- **Ne spam** - contribute hodnotu (analýzy, insights)
- Post "I'm building X, feedback?" threads
- AMA (Ask Me Anything) před launch

**Discord strategy:**
- Join populární sports betting Discord servery
- Build relationships s admins/mods
- Share concept, get feedback
- Invite beta testers

**Twitter/X:**
- Follow sports betting influencers
- Engage s Crypto Twitter (prediction market crowd)
- Share build-in-public updates
- Use hashtags: #sportsbetting #bettingtwitter #sportspicks

**Target:**
- 200-300 waitlist signups
- 50-100 engaged beta testers

---

#### **2. Content Foundation**

**SEO-optimized content:**
- "How to pass FTMO challenge" → "How to pass sports betting challenge"
- "Best sports betting strategies for beginners"
- "Prediction markets vs. traditional betting"
- "Bankroll management guide"

**Video content (YouTube):**
- Platform walkthrough
- "How I passed the sports betting challenge"
- Betting strategy tutorials
- Comparison videos (us vs. bookmakers vs. exchanges)

**Target:**
- 10-15 high-quality articles
- 3-5 YouTube videos
- Start ranking pro long-tail keywords

---

#### **3. Influencer Outreach**

**Micro-influencers (10K-100K followers):**
- Sports betting tipsters
- Fantasy sports analysts
- Sports Twitter personalities

**Offer:**
- Free challenge access
- Affiliate partnership (ongoing revenue share)
- Exclusive early access content

**Target:**
- 5-10 micro-influencer partnerships confirmed
- 2-3 content pieces (reviews, tutorials) ready for launch

---

### **C. Launch Phase (Days 1-30) - First 300 Users**

#### **1. Launch Platforms**

**Product Hunt:**
- Launch day: Detailed product page
- Engage všechny comments
- Coordinate upvotes (community)
- **Expected:** 50-100 signups

**Indie Hackers:**
- Post launch story
- "Building in public" series
- Community feedback
- **Expected:** 20-50 signups

**Hacker News (Show HN):**
- "Show HN: Sports betting challenge platform (FTMO for sports)"
- High-quality technical discussion
- **Expected:** 30-80 signups (pokud hits front page)

---

#### **2. Social Media Blitz**

**Twitter/X:**
- Launch announcement thread
- Daily progress updates
- User testimonials/wins
- Community engagement

**Instagram:**
- Visual success stories
- User results (leaderboards)
- Behind-the-scenes
- Stories + Reels

**TikTok (if relevant):**
- Quick win clips
- "How I turned $X into $Y" (challenge success)
- Platform tutorials

**Target:** 100-150 signups

---

#### **3. Community Launch Events**

**Opening challenges:**
- Free first challenge (limited spots)
- Launch tournament (leaderboard prize)
- "Founders' challenge" (special event)

**Engagement:**
- Live leaderboard
- Real-time updates
- Community chat (Discord)

**Target:** 50-100 signups, high engagement

---

### **D. Growth Phase (Days 31-90) - 300 → 1,000 Users**

#### **1. Referral Program**

**Structure:**
- Existing user refers friend
- Both dostávají reward:
  - Referrer: Free challenge nebo credit
  - Referred: Discount na first challenge

**Mechanics:**
- Easy share links
- Track referrals in app
- Leaderboard pro top referrers

**Expected:**
- 20-30% of users refer at least 1 person
- **200-300 users** z referrals

---

#### **2. Content Marketing Expansion**

**Blog/SEO:**
- 2-3 articles per week
- Deep-dive sports analytics
- Betting guides
- User success stories (case studies)

**YouTube:**
- Weekly strategy videos
- Platform updates
- User interviews (successful passers)

**Podcast appearances:**
- Reach out k sports betting podcasts
- Share story, platform concept

**Expected:** **150-250 organic users**

---

#### **3. Paid Acquisition (Targeted)**

**Focus channels:**
- Reddit Ads (r/sportsbook)
- Twitter/X Ads (sports betting keywords)
- Google Search Ads (long-tail: "sports betting challenge")

**Budget:**
- $5,000-10,000 total
- Target CPA: <$50
- A/B test creatives

**Expected:** **150-200 users**

---

#### **4. Affiliate Marketing**

**Early affiliates:**
- Sports betting tipsters
- Betting Discord server owners
- YouTube sports analysts

**Commission:**
- 20-30% recurring revenue share, NEBO
- $50-100 CPA per converted user

**Content:**
- Affiliate provides: Reviews, tutorials, comparisons
- We provide: Tracking links, creatives, support

**Expected:** **100-150 users**

---

#### **5. Community Building**

**Own Discord server:**
- Launch official community
- Channels:
  - General chat
  - Sport-specific (NFL, NBA, Soccer, etc.)
  - Strategy discussion
  - Leaderboard
  - Announcements

**Features:**
- Real-time challenge updates
- User-generated content (picks sharing)
- AMA sessions
- Tournaments

**Telegram (optional):**
- Alerts channel
- Quick updates
- Mobile-first community

**Expected engagement:**
- 30-40% of users join Discord
- Daily active community

---

### **E. Acquisition Channels - Summary**

| Channel | Timeline | Expected Users | Cost | Notes |
|---------|----------|----------------|------|-------|
| **Waitlist/Beta** | Pre-launch | 200-300 | $0 | Organic community |
| **Launch platforms** | Day 1-7 | 100-200 | $0 | PH, IH, HN |
| **Social media** | Day 1-30 | 100-150 | $0-500 | Organic + small paid |
| **Launch events** | Day 1-14 | 50-100 | $1000 | Free challenges, prizes |
| **Referrals** | Day 31-90 | 200-300 | $2000 | Rewards pro users |
| **Content/SEO** | Ongoing | 150-250 | $0-1000 | Time investment |
| **Paid ads** | Day 31-90 | 150-200 | $5000-10000 | Targeted, measured |
| **Affiliates** | Day 31-90 | 100-150 | $3000-5000 | Revenue share |
| **TOTAL** | **90 days** | **~1,000** | **$11,500-19,500** | **~$12-20 per user** |

---

### **F. Key Success Metrics**

**Acquisition:**
- Signups per day
- Cost per acquisition (CPA)
- Channel attribution

**Activation:**
- % who start challenge
- % who complete onboarding
- Time to first challenge

**Engagement:**
- Daily active users (DAU)
- Challenge completion rate
- Average profit/loss per challenge

**Retention:**
- % who attempt 2nd challenge
- % who reach funded status
- Funded user retention (monthly)

**Revenue:**
- Challenge fees collected
- Average revenue per user (ARPU)
- LTV:CAC ratio

**Viral/Growth:**
- Referral rate
- Organic signups (direct/search)
- Social shares, mentions

---

### **G. GTM Positioning & Messaging**

#### **Core positioning:**
*"The sports betting challenge platform. Prove your skill. Get funded. Keep 80%."*

#### **Messaging pillars:**

1. **Skill, not luck**
   - "Stop gambling. Start predicting."
   - "Your sports knowledge has value."
   - Challenge-based validation

2. **Fair markets**
   - "No bookmaker margins. Just you vs. the market."
   - "Peer-to-peer. Transparent. Fair."
   - Better odds than traditional betting

3. **Risk-free learning**
   - "Learn without losing."
   - "Demo capital. Real rewards."
   - Community + education focus

4. **Funded opportunity**
   - "Prove your edge. We'll fund you."
   - "Scale your strategy without risk."
   - "80% profit share. Your skill. Our capital."

---

### **H. GTM Risks & Mitigation**

**Risk 1: Low conversion (signups don't start challenges)**
- **Mitigation:** Free first challenge pro early users, streamlined onboarding, clear value prop

**Risk 2: High CAC (acquisition too expensive)**
- **Mitigation:** Organic-first strategy, community building, referrals > paid ads

**Risk 3: Regulatory pushback**
- **Mitigation:** Demo capital model, legal counsel, clear ToS, avoid restricted jurisdictions

**Risk 4: Low engagement (users try once, leave)**
- **Mitigation:** Community features, leaderboards, social sharing, educational content

**Risk 5: Poor challenge pass rate (too easy/hard)**
- **Mitigation:** Data-driven target calibration, multiple difficulty levels, A/B testing

---

## 5. COMPETITIVE POSITIONING MAP

### **Visualization:**

```
                    High Skill Requirement
                            |
                            |
              Sports        |
           Prop Firms       |      FTMO
        (BankrollU)         |   (Trading)
                            |
                            |
Low Fees -------------------|------------------- High Fees
                            |
        Betting             |    Traditional
       Exchanges            |   Sportsbooks
    (Betfair, Smarkets)     |  (Bet365, etc.)
                            |
                            |
                   Low Skill Requirement
```

### **Our position:**
**Upper-left quadrant:**
- High skill requirement (challenge-based)
- Low/Fair fees (P2P markets, profit share)
- Combines best of: Prop firms (skill validation) + Exchanges (fair prices) + Prediction markets (P2P)

---

## 6. KEY TAKEAWAYS PRO CASE STUDY

### **Competitive Insights:**
1. **Betting exchanges** (Betfair, Smarkets) mají P2P, ale chybí jim skill validation + funding model
2. **Sports prop firms** (BankrollU) mají challenge model, ale traditional betting (ne P2P markets)
3. **Fantasy sports** (DraftKings) úspěšně positioned jako skill-based, ale není to prediction markets
4. **Gap:** Nikdo nekombinuje FTMO challenge + P2P prediction markets + sports-first UX

### **User Insights:**
1. **Primary target:** Analytical bettors (25-35, data-driven) - highest LTV
2. **Gen Z/Millennials:** 76% market share, mobile-first (84-90%), social-driven
3. **Pain points:** Bookmaker margins, limited bankroll, account limits, gambling stigma
4. **Value:** Skill validation, funded opportunity, community, better odds

### **Regulatory Insights:**
1. **Demo capital model = safe route** (minimal gambling regulation)
2. **Skill-based positioning** critical (DFS precedent)
3. **Exchange model** (facilitator) > bookmaker (operator)
4. **Launch markets:** Crypto-friendly, skill-gaming friendly jurisdictions first

### **GTM Insights:**
1. **Organic-first:** Community (Reddit, Discord), content (SEO, YouTube), referrals
2. **Target:** 1,000 users v 90 days, **$12-20 CPA** (well below industry $200-500)
3. **Channels:** Launch platforms (PH, IH) → Community → Content → Affiliates → Paid ads (later)
4. **Key:** Leverage FTMO brand trust, position jako skill evaluation, build social features

---

## 7. NEXT STEPS - Připrava prezentace

S těmito znalostmi můžeš nyní:

1. ✅ **Define clear opportunity** (market gaps identifikovány)
2. ✅ **Target specific users** (4 personas ready)
3. ✅ **Differentiate from competition** (positioning clear)
4. ✅ **Navigate regulatory** (demo capital strategy)
5. ✅ **Plan realistic GTM** (90-day roadmap, channel mix)

**Doporučení pro prezentaci:**
- Visual competitive positioning map
- Lead s "Analytical Alex" persona (primary target)
- Emphasize demo capital regulatory advantage
- Show 90-day GTM roadmap
- Connect všechno: product → audience → competition → growth
