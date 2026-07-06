# Polymarket a Kalshi - Prediction Markets - Znalostní báze

## Co jsou Prediction Markets (Predikční trhy)

**Definice:**
Platformy, kde uživatelé mohou spekulovat na výsledky budoucích událostí tím, že kupují a prodávají akcie (shares) reprezentující různé možné výsledky.

**Klíčový rozdíl od tradičního sázení:**
- **Traditional betting**: Sázíte proti bookmakerovi, který stanovuje kurzy a má house edge
- **Prediction markets**: Obchodujete peer-to-peer s ostatními uživateli, trh stanovuje ceny, platforma pouze facilituje

---

## Polymarket - Decentralizovaná platforma

### Základní informace

**Co je Polymarket:**
- Decentralizovaná prediction market platforma
- Umožňuje uživatelům spekulovat na výsledky budoucích událostí
- Založeno na blockchain technologii (Polygon network)
- Peer-to-peer trading na to, zda se událost stane určitým způsobem nebo ne

### Jak funguje Polymarket

#### Struktura obchodování

**Binary contracts (Binární kontrakty):**
- Každá otázka má dvě možnosti: **"Yes"** nebo **"No"**
- Příklad: "Vyhraje tým XY zápas?"
  - Yes shares
  - No shares

**Pricing (Cenotvorba):**
- Každá akcie je oceněna mezi **$0.01 a $1.00**
- Cena reprezentuje **implikovanou pravděpodobnost** výskytu výsledku podle trhu
- **Yes + No ceny = vždy $1.00** (protože jeden výsledek musí nastat)
- Ceny jsou určeny **nabídkou a poptávkou** mezi tradery

**Příklad:**
- Yes share za $0.70 = trh odhaduje 70% šanci
- No share za $0.30 = trh odhaduje 30% šanci
- $0.70 + $0.30 = $1.00 ✓

#### Settlement (Vyrovnání)

- Výherní shares se vyrovnají za **$1.00**
- Prohrávající shares se vyrovnají za **$0.00**
- Váš profit = (Settlement value - Purchase price) × počet shares

**Příklad:**
- Koupíte 100 Yes shares za $0.70 = $70 investice
- Událost se stane → Yes shares = $1.00
- Dostanete: 100 × $1.00 = $100
- **Profit: $30**

### Technologická infrastruktura

**Blockchain:**
- Postaveno na **Polygon** (Layer-2 solution)
- Vyšší škálovatelnost
- Nižší transakční náklady
- Všechny transakce jsou **transparentní** a **ověřitelné**

**Non-custodial:**
- Polymarket **nikdy nedrží** uživatelské prostředky
- Uživatelé mají plnou kontrolu nad svými assets
- Smart contracts řídí vše automaticky

**Platby:**
- Používá **USDC** (dollar-pegged stablecoin)
- Stabilní hodnota vázaná na USD

**Zero fees na betting:**
- Polymarket **nebere žádné profity ze sázek**
- Výdělečný model může být založen na jiných aspektech (data licensing, transaction fees na blockchain úrovni, atd.)

### Výhody decentralizace

✅ **Transparentnost**: Všechny transakce viditelné on-chain
✅ **Trustless**: Nepotřebujete důvěřovat centrální společnosti
✅ **Non-custodial**: Vaše peníze nejsou drženy třetí stranou
✅ **Censorship resistant**: Těžší blokovat nebo cenzurovat
✅ **Global access**: Dostupné odkudkoliv (teoreticky)

### Nevýhody decentralizace

❌ **Komplexnost**: Vyžaduje crypto wallet, USDC, znalost blockchainu
❌ **Regulatorní nejistota**: Problematické v mnoha jurisdikcích
❌ **Gas fees**: I na Polygon existují transakční náklady
❌ **Onboarding friction**: Obtížnější pro mainstream uživatele
❌ **Likvidita**: Může být nižší než na centralizovaných platformách

---

## Kalshi - Regulovaná platforma (USA)

### Základní informace

**Co je Kalshi:**
- **Regulovaná** prediction market exchange pro USA
- Federálně regulovaná **CFTC** (Commodity Futures Trading Commission)
- Status: **Designated Contract Market (DCM)** od listopadu 2020
- První legální a regulovaná prediction market platforma v USA

### Regulatorní rámec

**CFTC regulace:**
- **DCM status**: Authorized marketplace pro trading futures, swaps, event contracts, a options
- Přísné finanční požadavky
- Monitoring aktivity pro zajištění bezpečnosti zákazníků
- Compliance s federálními zákony

**Ochrana uživatelů:**
- Governmental oversight
- Finanční záruky
- Anti-manipulation measures
- Transparent reporting

### Jak funguje Kalshi

#### Struktura kontraktů

**Binary contracts:**
- Podobně jako Polymarket: **Yes** nebo **No** strany
- Každý kontrakt = $1 hodnota
- Pricing: **1 cent až 99 centů**
  - 1 cent = velmi nízká pravděpodobnost
  - 99 centů = velmi vysoká pravděpodobnost

**Příklad otázky:**
- "Vzroste nezaměstnanost nad 5% v příštím čtvrtletí?"
- Yes contracts vs. No contracts

#### Cenotvorba

- Ceny určeny **nabídkou a poptávkou** mezi tradery
- Cena Yes kontraktu = **odhadovaná pravděpodobnost** výskytu události podle trhu
- Settlement za $1 pokud je výsledek správný, $0 pokud ne

#### Settlement

- Každý kontrakt se vyrovná za **$1** nebo **$0** podle výsledku
- Profit = (Settlement - Purchase price) × množství kontraktů

### Pokryté trhy

**Široká škála událostí:**
- **Volby a politika**
- **Ekonomické ukazatele** (nezaměstnanost, GDP, inflace)
- **Korporátní události** (earnings, fúze, akvizice)
- **Sportovní události**

**Omezení:**
- CFTC navrhuje pravidla **omezující** některé prediction markets
- Zákaz: sázení na zranění sportovců a některé props
- Regulace stále evolves

### Výhody regulace

✅ **Legal certainty**: Jasný právní rámec v USA
✅ **Consumer protection**: CFTC oversight
✅ **Mainstream appeal**: Snadnější onboarding (USD, ne crypto)
✅ **Institutional trust**: Regulace buduje důvěru
✅ **Fiat on/off ramps**: Jednoduché vklady/výběry v USD

### Nevýhody regulace

❌ **Geograficky omezeno**: Primárně USA (compliance náročné v jiných jurisdikcích)
❌ **Omezené trhy**: Ne všechny události povoleny k tradingu
❌ **Pomalejší inovace**: Každý nový market vyžaduje regulatory approval
❌ **Higher compliance costs**: Regulatory overhead

---

## Polymarket vs. Kalshi - Srovnání

| **Aspekt** | **Polymarket** | **Kalshi** |
|-----------|----------------|------------|
| **Regulace** | Neregulovaný (decentralizovaný) | CFTC regulovaný (DCM status) |
| **Technologie** | Blockchain (Polygon) | Centralizovaná platforma |
| **Měna** | USDC (crypto) | USD (fiat) |
| **Custody** | Non-custodial (user owns keys) | Custodial (Kalshi holds funds) |
| **Geografický dosah** | Globální (teoreticky) | Primárně USA |
| **Onboarding** | Komplikovanější (crypto wallet) | Jednodušší (bank account) |
| **Fees** | Zero betting fees | Platform fees |
| **Market variety** | Široká škála (méně omezení) | Omezeno regulatory approval |
| **Likvidita** | Závisí na market | Obecně vyšší pro populární markets |
| **Trust model** | Trustless (smart contracts) | Trust in regulator + platform |
| **Transparentnost** | Plná (on-chain) | Podle regulatory reporting |

---

## Prediction Markets - Business modely

### Revenue streams

**1. Transaction fees:**
- Poplatek za každý trade
- Typicky % z objemu
- Příklad: 2-5% z každé transakce

**2. Market making:**
- Platforma může poskytovat likviditu
- Profit z bid-ask spreadu

**3. Platform subscription:**
- Premium features za měsíční fee
- Advanced analytics, data, API access

**4. Data licensing:**
- Prodej prediction market dat
- Cenné pro research, media, institutions

**5. Withdrawal fees:**
- Poplatek za výběr prostředků

### Cost structure

**Operační náklady:**
- Technology infrastructure
- Data feeds (real-time event outcomes)
- Settlement mechanism
- Customer support
- Regulatory compliance (zejména Kalshi)
- Liquidity provision

---

## Aplikace na Sports Prediction Markets

### Co můžeme převzít z Polymarket:

1. **Decentralizovaný model** (případně hybrid):
   - Transparentnost
   - Non-custodial možnosti
   - Global reach

2. **Binary contract struktura**:
   - Simple Yes/No markets
   - Snadné pochopení
   - Cena = implikovaná pravděpodobnost

3. **Peer-to-peer trading**:
   - Democratizace odds
   - Lepší ceny než bookmaker house edge
   - Community-driven pricing

### Co můžeme převzít z Kalshi:

1. **Regulatory compliance**:
   - Legal certainty
   - Consumer protection
   - Institutional trust
   - Možnost mainstream adopce

2. **Fiat on-ramps**:
   - Jednodušší pro mainstream uživatele
   - Žádná potřeba crypto knowledge

3. **Structured approach**:
   - Jasná kategorizace markets
   - Professional presentation
   - Institutional appeal

---

## Klíčové výzvy pro Sports Prediction Markets

### 1. **Regulatory Landscape**

**Výzvy:**
- Sportovní sázení je vysoce regulované
- Různé zákony v různých jurisdikcích
- Gambling vs. prediction markets = právní šedá zóna
- Licenční požadavky

**Řešení:**
- Start v crypto-friendly jurisdikcích
- Nebo: Full regulatory compliance (Kalshi model)
- Nebo: FTMO model - demo/simulated capital pro challenges

### 2. **Likvidita**

**Výzvy:**
- Peer-to-peer vyžaduje obě strany trades
- Nízká likvidita = špatné ceny = špatná UX

**Řešení:**
- Automated market makers (AMM)
- Platform jako liquidity provider
- Incentivize market makers
- Dostatečný user base

### 3. **Oracle Problem**

**Výzvy:**
- Kdo určuje výsledky sportovních událostí?
- Jak zajistit trustworthy settlement?

**Řešení:**
- Integration s Flashscore-like data providery
- Multi-source verification
- Decentralized oracle networks (pro blockchain verzi)
- Manual oversight pro edge cases

### 4. **User Education**

**Výzvy:**
- Prediction markets jsou složitější než tradiční betting
- Mainstream uživatelé zvyklí na "odds" a "bookmakers"

**Řešení:**
- Intuitivní UX/UI
- Vzdělávací obsah
- Gradual onboarding
- Familiar terminology

---

## Hybridní model - Best of Both Worlds?

### Koncept:

**Kombinace:**
- **FTMO evaluační model**: Challenge → Verification → Funding
- **Flashscore UX**: Real-time sports data a statistiky
- **Polymarket mechanismus**: Peer-to-peer prediction markets
- **Kalshi approach**: Regulatory awareness (nebo sandbox s demo kapitálem)

### Možná struktura:

1. **Challenge fáze**:
   - Uživatelé platí vstupní fee
   - Dostávají simulovaný kapitál (např. $10,000)
   - Tradují na sportovních prediction markets (demo prostředí)
   - Musí dosáhnout X% ROI za Y dní

2. **Funded fáze**:
   - Úspěšní uživatelé dostanou "reálný" kapitál
   - Ale: stále může být demo (FTMO model)
   - Nebo: skutečné peer-to-peer trading na Polymarket-like platformě
   - Profit share: 70-90% pro usera

3. **Revenue model**:
   - **Primární**: Challenge fees (majority fails)
   - **Sekundární**: Profit share z funded traders
   - **Terciární**: Transaction fees na prediction market

### Výhody:

✅ Minimální regulatory risk (demo prostředí v challenge fázi)
✅ Proven FTMO model revenue structure
✅ Innovation v sports betting space
✅ Community a engagement (sdílení "predictions", leaderboards)
✅ Data insights pro vlastní trading

---

## Důležité poznatky pro case study

1. **Prediction markets ≠ Traditional betting**
   - Peer-to-peer vs. against the house
   - Market-driven prices vs. bookmaker odds
   - Potenciálně lepší value pro uživatele

2. **Regulace je klíčová**
   - Sports betting je heavily regulated
   - Crypto/decentralizace přináší další komplikace
   - Demo/simulated capital může být workaround (FTMO model)

3. **Likvidita je kritická**
   - Peer-to-peer vyžaduje obě strany
   - AMM nebo platform jako market maker nutnost

4. **Oracle problém musí být vyřešen**
   - Spolehlivé sportovní data feeds
   - Trustworthy settlement mechanism

5. **UX je klíčové**
   - Mainstream uživatelé nejsou zvyklí na prediction markets
   - Potřeba intuitivního interface
   - Edukace je důležitá

6. **Hybrid approach má potenciál**
   - FTMO model + Prediction markets + Flashscore UX
   - Minimalizuje regulatory risk
   - Proven revenue model
   - Innovation v sports space
