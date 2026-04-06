
# Apps

- [Stringfy](#stringfy)
- [AuthCraft](#authcraft)
- [SleekDB](#sleekdb)
- [Glyph](#glyph)
- [Quantix](#quantix)
- [Cryptoledger](#cryptoledger)
- [Cryptosign](#cryptosign)


---

## Stringfy

https://stringfy.pages.dev

Stringfy is a secure text obfuscation tool designed to protect sensitive information from bots and automated scrapers. It transforms phone numbers, email addresses, and other contact details into Base64-encoded images, ensuring they remain readable to humans while being inaccessible to machines. The app generates lightweight SVG, PNG, and WebP assets and works entirely without client-side JavaScript, making it fast, reliable, and privacy friendly.

Built with Astro.


## AuthCraft

https://authcraft.pages.dev

AuthCraft is a code first generator for authentication buttons that gives you full control over design and output. It allows you to create polished sign-in buttons for providers like Google, GitHub, and Apple with precise customization. You can export assets as SVG, PNG, or WebP or directly integrate clean, production ready code into your project. It removes the need to manually recreate provider buttons and ensures consistency across your interface.

Built with Blazor WebAssembly.


## SleekDB

https://sleekdb.pages.dev

SleekDB simplifies working with structured data by allowing you to convert multiple CSV files into a single SQLite database instantly. It also supports uploading an existing database and updating it by inserting or replacing records from CSV files. The workflow is streamlined and efficient, making it especially useful for developers and analysts who need quick data transformations without complex setup.

Built with Vite.


## Glyph

https://glyphgallery.pages.dev

Glyph is a modern icon exploration tool built for developers and designers. It provides access to a large collection of over 30,000 scalable vector icons across multiple libraries. The interface offers fast search, real time preview, and easy customization of size and color. Icons can be downloaded instantly as SVG files, making integration into projects seamless and efficient.

Built with Vite.


## Quantix

https://quantix.red

Quantix is a financial analysis platform that combines a SQLite powered engine with valuation and performance frameworks in a single workflow. It enables you to evaluate fair value, business quality, and market expectations using models such as DCF, dividend based valuation, and implied multiples.

The platform brings together profitability, capital structure, return metrics, growth trends, cash conversion, and volatility into a unified view. You can analyze leverage, liquidity, shareholder returns, and capital allocation decisions without leaving the core workflow.

Quantix also provides sensitivity analysis tools that help you test assumptions and explore upside, downside, and risk scenarios. Focused chart clusters make it easy to examine price ranges, margins, growth, solvency, and market behavior in a clear and structured way.

Built with Docker Hub container images, FastAPI, Vite, and Cloudflare Tunnel.


## Cryptoledger

https://cryptoledger.pages.dev

Cryptoledger is a fully client side, offline first distributed ledger application designed for secure and portable record keeping. It uses modern WebAuthn passkeys so private keys are never exposed to the browser, while cryptographic operations are handled by the operating system and authenticator.

A single JSON file acts as the database, making it easy to transfer, back up, and audit across devices and controlled environments. Each block is re hashed and signature verified locally using Rust WebAssembly, ensuring append only integrity and authenticity without requiring any server or network connection.

The system combines a static frontend with a Rust powered verification layer, allowing the entire ledger to be validated in a self contained environment.

Built with Astro and Rust WebAssembly.


## Cryptosign

https://cryptosign.pages.dev

Cryptosign is a client side web application for creating and verifying detached cryptographic signatures without relying on servers or external services. It allows authors to sign files locally using passkeys, while recipients can verify file integrity offline using the original file, signature, and public key.

The app is organized around three main workflows: Key Manager, Signer, and Verifier. In the Key Manager, a user creates a passkey signing identity and extracts the matching public key for sharing with clients. The Signer workflow is designed for detached signatures rather than embedded or wrapped documents. The Verifier checks whether the signature matches the file contents and the declared signing algorithm.

Built with Astro and Rust WebAssembly.
