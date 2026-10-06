## Cezar Tocaciu

Fourth-year computer science at the Technical University of Cluj-Napoca. Mostly
Python and backend work: scrapers, typed APIs, ML models that have to survive
their own validation before I trust them.

These days coding agents type a lot of my code. My job is deciding what gets
built, setting up how the agent works, and standing between its output and
`main`: reading the diffs, writing the tests that gate the merge, and writing
down which parts have never actually run.

**[cezart3.vercel.app](https://cezart3.vercel.app)** has the long version of
everything below, with the evidence behind each claim.

---

### What I've built

**[KiraImobiliare](https://github.com/Cezart3/KiraImobiliare)** · Python, FastAPI, React · [live demo](https://kira-imobiliare.vercel.app)  
Rental aggregator for Romania. Scrapes five listing sites and adds the filters
none of them have: own boiler or district heating, parking, walking time to your
faculty. Facts come out of messy Romanian ad text through regex, on purpose: I
can audit it when it gets one wrong. ~70 backend tests. The demo runs the real
pipeline over invented listings; real data only comes from running it yourself.

**[Escape With Your Friends](https://github.com/Cezart3/Escape-With-Your-Friends)** · Unity 6, C#, FishNet, Steamworks  
A four-player co-op survival game for Steam where your friends are the main
hazard. Host-authoritative P2P over Steam, no servers. Claude Code writes the
C#. I set scope, write the issues, playtest and decide what is fun. 136 PRs in
five weeks, ~70 headless test harnesses (some run host and client as two
processes), and frame times logged against a Radeon 760M as the min spec. Not on
Steam yet.

**[TradingBot](https://github.com/Cezart3/TradingBot)** · Python, XGBoost, LightGBM · *write-up public, code private*  
Opening-range breakout on US30 with a calibrated ML filter, live against
MetaTrader 5 on a demo account. Purged time-ordered CV, isotonic calibration,
and a walk-forward test that killed the configuration with the prettier win
rate. Has never traded real money.

**[RankUp](https://github.com/Cezart3/RankUp)** · TypeScript, React, WebAssembly  
Chrome extension that parses opponents' FACEIT CS2 demos inside the browser
(Rust parser compiled to WASM, a pool of web workers) and plots where each of
them usually plays. No backend and no telemetry. 400+ Vitest tests.

**[ShowerConfig](https://github.com/Cezart3/ShowerConfig)** · Java, Swing, MySQL · *client work, code private*  
Desktop configurator for a shower-cabin manufacturer: walks the salesperson
through the build, prices it at the day's BNR exchange rate and exports a PDF
quote. Replaced a spreadsheet and is used every day.

### Contributing to

**[unlost-in-translation-mobile](https://github.com/radumarias/unlost-in-translation-mobile)**  
[Radu Marias](https://github.com/radumarias)' open-source AI translator. I
contribute, he reviews and merges. My part: restructuring it into a Kotlin
Multiplatform project that also runs in the browser, a security audit, and an
end-to-end encrypted two-phone conversation mode.

---

### Tools

Comfortable: `Python` `FastAPI` `SQLAlchemy` `pytest` `pandas` `NumPy` `scikit-learn` `XGBoost` `SQL` `Git`  
Shipped with, still look things up: `Java` `TypeScript` `React` `MySQL` `SQLite` `C++` `LightGBM` `Optuna`  
Learning on real projects: `Kotlin Multiplatform` `Unity` `C#`  
How I work: `Claude Code` · agent skills and hooks · tests as the merge gate

### Contact

cezartocaciu233@gmail.com · [LinkedIn](https://www.linkedin.com/in/tocaciu-cezar-0865373b6/) · [Instagram](https://instagram.com/tcezar3) · [cezart3.vercel.app](https://cezart3.vercel.app) · Cluj-Napoca

Looking for a backend or ML internship. Private repos available on request.
