# Entertainment IT — TrueNAS App Catalog

Custom TrueNAS SCALE app catalog by [Entertainment IT](https://www.entertainmentit.co).

## Available Apps

| App | Description | Price |
|-----|-------------|-------|
| **HyperDeck Backup Manager** | Professional backup solution for Blackmagic HyperDeck recorders | $365/year ([Free trial](https://www.entertainmentit.co/hyperdeck-backup)) |

## How to Install

### Step 1: Add this catalog to TrueNAS

1. Open your TrueNAS SCALE web UI
2. Go to **Apps** → **Discover Apps** → **Manage Catalogs**
3. Click **Add Catalog**
4. Fill in:
   - **Catalog Name:** `Entertainment IT`
   - **Repository:** `https://github.com/devsupport-eit/truenas-catalog`
   - **Preferred Train:** `stable`
   - **Branch:** `main`
5. Click **Save**

### Step 2: Install the app

1. Go to **Apps** → **Discover Apps**
2. Search for "HyperDeck"
3. Click **Install**
4. Configure your settings (ports, storage paths, timezone)
5. Click **Install**
6. Open the web UI and activate your license

## Requirements

- TrueNAS SCALE 24.04 (Dragonfish) or later
- A storage pool with available space for recordings
- Network access to Blackmagic HyperDeck devices
- License key from [Entertainment IT](https://www.entertainmentit.co/hyperdeck-backup)

## Support

- **Email:** devsupport@entertainmentit.co
- **Subject:** HyperDeck Issue for [YOUR COMPANY]
- **Website:** [entertainmentit.co](https://www.entertainmentit.co)
