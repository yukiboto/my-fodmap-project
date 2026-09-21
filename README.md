# Sustenance — FODMAP & Gluten-Free Food Checker

A mobile-first, single-file web app for checking common foods, dishes, and ingredient lists for low-FODMAP and gluten-free clues.

## Features

- Search 77 common ingredients and dishes, including Japanese dishes such as gyudon (牛丼).
- Switch between English and Japanese labels, food names, and quick answers; Japanese aliases such as 「フムス」「玉ねぎ」「寿司」 are searchable.
- Forgiving search suggests likely matches for small spelling mistakes such as `humus` or `hummis`.
- Use the Search button or press Enter after typing a query.
- Filter by FODMAP level, gluten status, and category.
- Paste an ingredient list or menu description to flag common FODMAP and gluten clues.
- Take a food or label photo on mobile and optionally analyse it with Gemini.
- Scan a barcode or QR code with a supported browser; barcode products are looked up through Open Food Facts.
- Responsive layout designed for small phone screens as well as desktop.

## Run

Open index.html in a browser, or serve the folder over HTTPS/local development server for camera access.

Photo analysis is optional and requires a Gemini API key entered in the app. The key is kept in that browser's local storage. Ingredient checks and barcode lookups do not require a Gemini key.

## Important limitations

This is an educational screening tool, not a diagnosis or a gluten-free certification. FODMAP status depends on portion, preparation, brand, and the individual's reintroduction stage. Open Food Facts data may be incomplete. People with coeliac disease, allergies, or significant symptoms should verify the current manufacturer label and seek qualified medical advice.
