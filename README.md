COBA

A lightweight, self-contained text encryption tool.

Coba is a single HTML file that transforms text into compact, password-protected URLs.
How it works

    Compression — Deflate, with an LZW fallback.
    Encryption — AES-256-GCM with PBKDF2 / SHA-256 key derivation.
    Encoding — encrypted bytes are converted into words using built-in dictionaries.
    URL generation — the encoded data is embedded into the URL fragment (#).

Features

    Single-file HTML application.
    Pure client-side processing.
    No backend, server, or database required.
    Works offline.
    No installation or account required.

Technologies

HTML, CSS, JavaScript, Web Crypto API, Compression Streams API.
