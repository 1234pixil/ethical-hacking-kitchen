# Ethical Hacking Kitchen

A single-file, client-side toolkit of encoders, decoders, ciphers, and formatters — CyberChef-inspired. Everything runs in the browser; nothing is sent to a server.

## Tools included

- Base64 / Base32
- Hex
- URL (percent) encoding
- Caesar / ROT (with brute-force all-shifts view)
- Vigenère cipher
- Atbash cipher
- Morse code
- Binary
- Hashing (MD5, SHA-1, SHA-256)
- JWT decoder (header/payload, no signature verification)
- JSON formatter / minifier
- Unix timestamp converter
- UUID v4 / random string generator
- Text case tools + Mirror / De-mirror
- AES-256-GCM encrypt/decrypt (password-derived key via PBKDF2)
- Gzip compress/decompress
- HTML entity encode/decode
- Unicode `\uXXXX` escape/unescape
- Defang / refang (for sharing IOCs safely)
- Regex extractor (URLs, emails, IPv4, hash-looking strings)

## Usage

Just open `index.html` in any modern browser. No build step, no dependencies, no server required.

## Deploying

Works as-is on GitHub Pages, Netlify, Vercel, or any static host — it's one HTML file.
