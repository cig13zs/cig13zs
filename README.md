# jju1s

I make small browser tools for annoyances that should have a simple fix. They
do not need an account, and none of them sends analytics to me.

[![Ko-fi](https://img.shields.io/badge/Ko--fi-buy_me_a_coffee-FF5E5B?style=flat-square&logo=ko-fi&logoColor=white)](https://ko-fi.com/jju1s)

## Tools

| Project | What it does | Try it |
|---|---|---|
| [Defrost](https://github.com/cig13zs/defrost) | Unfreezes scroll, restores copy & right-click, and strips modal overlays. | [Project page](https://cig13zs.github.io/defrost/) |
| [Invisibles](https://github.com/cig13zs/invisibles) | Reveals zero-width characters, bidi controls and hidden Unicode, then strips them. | [Web app](https://cig13zs.github.io/invisibles/) |
| [Unfurl](https://github.com/cig13zs/unfurl) | Unwraps Google/FB redirects and strips UTM tracking tails offline. | [Web app](https://cig13zs.github.io/unfurl/) |
| [PromptPurify](https://github.com/cig13zs/prompt-purify) | Sanitizes code, logs, and stack traces before pasting into AI models. | [Web app](https://cig13zs.github.io/prompt-purify/) |
| [CleanCSV](https://github.com/cig13zs/clean-csv) | Repairs delimiters, missing columns, and quote escaping in messy CSVs. | [Web app](https://cig13zs.github.io/clean-csv/) |
| [UnbreakText](https://github.com/cig13zs/unbreak-text) | Unwraps hard line-breaks and normalizes copied paragraphs into clean text. | [Web app](https://cig13zs.github.io/unbreak-text/) |
| [JSONFixer](https://github.com/cig13zs/json-fixer) | Repairs syntax errors, trailing commas, and unquoted keys in broken JSON. | [Web app](https://cig13zs.github.io/json-fixer/) |
| [CronHuman](https://github.com/cig13zs/cron-human) | Translates cryptic cron schedule expressions into plain English offline. | [Web app](https://cig13zs.github.io/cron-human/) |
| [CurlToFetch](https://github.com/cig13zs/curl-to-fetch) | Converts cURL commands into clean JavaScript fetch() snippets. | [Web app](https://cig13zs.github.io/curl-to-fetch/) |
| [Base64Studio](https://github.com/cig13zs/base64-studio) | Decodes Base64 payloads and inspects JWT tokens offline. | [Web app](https://cig13zs.github.io/base64-studio/) |
| [SVGDiet](https://github.com/cig13zs/svg-diet) | Strips junk editor metadata and comments from SVG files offline. | [Web app](https://cig13zs.github.io/svg-diet/) |
| [TextDiff](https://github.com/cig13zs/text-diff) | Fast offline side-by-side line diff viewer. | [Web app](https://cig13zs.github.io/text-diff/) |
| [SQLFormat](https://github.com/cig13zs/sql-format) | Formats and beautifies raw SQL queries with standard uppercase keywords. | [Web app](https://cig13zs.github.io/sql-format/) |
| [EnvClean](https://github.com/cig13zs/env-clean) | Deduplicates and normalizes .env variables and generates .env.example files. | [Web app](https://cig13zs.github.io/env-clean/) |
| [ColorBlindSafe](https://github.com/cig13zs/color-blind-safe) | Calculates WCAG AA/AAA color contrast ratios and colorblind safety offline. | [Web app](https://cig13zs.github.io/color-blind-safe/) |
| [RegexExplain](https://github.com/cig13zs/regex-explain) | Deconstructs and explains regular expression tokens and flags in plain English. | [Web app](https://cig13zs.github.io/regex-explain/) |
| [JWTKit](https://github.com/cig13zs/jwt-kit) | Inspects JWT headers, claims, and expiration timestamps offline. | [Web app](https://cig13zs.github.io/jwt-kit/) |
| [Looktwice](https://github.com/cig13zs/looktwice) | Inspects a page's links and forms to see where they actually lead. | [Project page](https://cig13zs.github.io/looktwice/) |
| [Filed](https://github.com/cig13zs/filed) | Saves the job application page you're viewing and exports to CSV locally. | [Project page](https://cig13zs.github.io/filed/) |
| [Plusminus](https://github.com/cig13zs/plusminus) | Propagates measurement uncertainty specs through formulas for lab reports. | [Web app](https://cig13zs.github.io/plusminus/) |
| [Carryover](https://github.com/cig13zs/carryover) | Measures context fill and carries handoffs into fresh chats cleanly. | [Project page](https://cig13zs.github.io/carryover/) |
| [Rinse](https://github.com/cig13zs/rinse) | Shows GPS, camera, and timestamps in photos before exporting clean copies. | [Web app](https://cig13zs.github.io/rinse/) |
| [Return Google Cache](https://github.com/cig13zs/return-google-cache) | Adds Wayback Machine and archive.today links under Google search results. | [Install page](https://cig13zs.github.io/return-google-cache/) |
| [Return 100 Results](https://github.com/cig13zs/return-100-results) | Loads the next Google results pages inline as one long list. | [Install page](https://cig13zs.github.io/return-100-results/) |

The photo and text tools process files in the page. The chat extension has no
permissions key and makes no network requests. The Google extensions only work
on Google Search and do not use a project-owned server.

The source is deliberately small. Each project includes its limits in the
README and has a test you can run with Node.

MIT licensed. If one saved you some time, the tip jar is at
[ko-fi.com/jju1s](https://ko-fi.com/jju1s).
