# Tsumihon Extensions Repository

Extensions for the Tsumihon doujinshi collection tracker.

## Available Extensions

### Aggregators

- **Schale Network** - Multi-mirror doujinshi archive with automatic fallback
- **Chaika** - Panda archive mirror with comprehensive search
- **nHentai** - Popular doujinshi and manga aggregator
- **Hentag** - Doujinshi metadata aggregator and search service
- **Hdoujin** - Doujinshi aggregator and archive
- **E-hentai** - Large doujinshi archive (supports ExHentai with authentication)

### Self-Hosted

- **Schale Network** - Can be self-hosted with custom mirrors
- **LANraragi** - Self-hosted manga/doujinshi server (requires configuration)

### Stores

- **Melonbooks** - Japanese doujinshi store (placeholder - coming soon)

## Installation

These extensions are designed to be installed through the Tsumihon app:

1. Open Tsumihon
2. Navigate to Settings → Extensions
3. Browse available extensions
4. Tap "Install" on any extension you want to use

## Usage

After installing an extension:

1. Go to the Search screen
2. Select the extension from the provider dropdown
3. Search for content
4. View and manage your collection

## Extension Details

### Schale Network

- **Category:** Self-Hosted / Aggregator
- **Authentication:** Not required
- **Features:** Search, Get by ID, Pagination
- **Fallback URLs:** Automatic failover to backup mirrors

### Chaika (Panda)

- **Category:** Aggregator
- **Authentication:** Not required
- **Features:** Search, Get by ID, Pagination
- **Base URL:** https://panda.chaika.moe

### nHentai

- **Category:** Aggregator
- **Authentication:** Not required
- **Features:** Search, Get by ID, Pagination
- **Base URL:** https://nhentai.net

### Hentag

- **Category:** Aggregator
- **Authentication:** Not required
- **Features:** Search, Get by ID (no pagination)
- **Base URL:** https://hentag.com
- **Note:** Metadata aggregator, returns all results at once

### Hdoujin

- **Category:** Aggregator
- **Authentication:** Not required
- **Features:** Search, Get by ID, Pagination
- **Base URL:** https://hdoujin.org

### E-hentai

- **Category:** Aggregator
- **Authentication:** Optional (for ExHentai)
- **Features:** Search, Image Search, Pagination
- **Base URL:** https://e-hentai.org
- **Configuration:** Can be configured with ExHentai cookies for access to additional content

**ExHentai Setup:**
1. Login to ExHentai in your browser
2. Copy cookie values: `ipb_member_id`, `ipb_pass_hash`, `igneous`
3. Open extension settings in Tsumihon
4. Enable "Use ExHentai"
5. Paste cookie values
6. Save

### LANraragi

- **Category:** Self-Hosted
- **Authentication:** Optional
- **Configuration Required:** Yes
- **Status:** Placeholder (coming soon)

**Setup:**
1. Install and configure LANraragi server
2. In Tsumihon, configure extension with your server URL
3. Optionally add API key if enabled on server

### Melonbooks

- **Category:** Store
- **Status:** Placeholder (coming soon)
- **Note:** Future integration with Melonbooks.co.jp store

## Support

- **Issues:** https://github.com/tsumihon/tsumihon/issues
- **Documentation:** https://github.com/tsumihon/tsumihon
- **Discord:** [Coming soon]

## License

These extension manifests are provided under the MIT License. Individual services accessed by extensions have their own terms of service.

## Disclaimer

Tsumihon and these extensions are tools for managing your personal collection. Users are responsible for complying with the terms of service of any external services they access through these extensions. The extension authors and Tsumihon maintainers are not responsible for content accessed through third-party services.
