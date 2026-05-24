# Invoice Generator

A simple, beautiful invoice generator that runs entirely in your browser. No sign-ups, no servers — your data never leaves your computer.

## Features

- Multiple currencies (USD, KES, GBP, EUR)
- Client management — save & reuse client details
- Auto-save settings to localStorage
- Print to PDF or download as HTML
- Email invoice directly from the app
- Works offline

## How to Download & Use

### Option 1: Use Online (GitHub Pages)

Visit **https://mamatechafrica.github.io/invoice_generator**

### Option 2: Download & Use Offline

1. Click the green **Code** button above and select **Download ZIP**

### Option 3: Clone with Git

```bash
git clone https://github.com/mamatechafrica/invoice_generator.git
cd invoice_generator
open index.html
```

## Usage

1. Fill in your account details under **Account Settings** (name, bank info, address)
2. Click **Save Account Info**
3. Add client details under **Invoice Details**
4. Click **Save** to store client info for reuse
5. Fill in the invoice description, amount, and percentage
6. Click **Generate Invoice** to preview
7. Use **Print/PDF** to save or print, or **Download** to save as HTML

## Data & Privacy

All data is stored **only in your browser** using localStorage. Nothing is sent to any server. Your account details, saved clients, and settings remain private on your device.

If you clear your browser data, you'll lose saved settings. To keep a backup:
- Download your invoice as HTML or PDF
- Keep a copy of the downloaded ZIP as a fresh start

## Deploy Your Own

This app can be hosted on GitHub Pages for free:

```bash
git clone https://github.com/mamatechafrica/invoice_generator.git
cd invoice_generator
git push origin main
```

Then go to **Settings → Pages** in your repo and set the source to `main` branch.
