# premodern-set-selector
Chrome extension for automatically selecting premodern sets on TCGplayer, ManaPool, and The Comicbook Store websites

# Premodern Set Shopper

A Chrome extension that makes it easier to browse Premodern-era Magic: The Gathering cards across **TCGplayer, ManaPool, and ComicBookStore**.

The extension automatically selects the supported Premodern sets in the marketplace's set filter and provides a post-execution review showing which sets were found, selected, already selected, or missing.

## Features

- Supports TCGplayer, ManaPool, and ComicBookStore.
- Automatically selects supported Premodern-era MTG sets.
- Includes applicable set subcategories and promotional sets.
- Shows a results summary after execution.
- Identifies sets that were found, newly selected, already selected, and not found.
- Simple dark-themed interface.

## Installation

1. Download the latest release ZIP file.
2. Extract the ZIP file to a folder on your computer.
3. Open Google Chrome.
4. Navigate to `chrome://extensions/`.
5. Enable **Developer mode** in the upper-right corner.
6. Click **Load unpacked**.
7. Select the extracted Premodern Set Shopper folder.

The extension should now appear in your Chrome extensions list.

## How to Use

Before running the extension, navigate to the appropriate starting page for the marketplace you want to use.

### 1. TCGplayer

**Starting point:** A seller's store page.

1. Navigate to the seller's TCGplayer store.
2. Make sure the product line is set to **Magic: The Gathering**.
3. Open Premodern Set Shopper from your Chrome extensions.
4. Select **TCGplayer**.
5. Run the extension.

The extension will select the supported sets and display a post-execution report.

### 2. ManaPool

**Starting point:** A seller's store page.

1. Navigate to the ManaPool seller's store.
2. Open Premodern Set Shopper from your Chrome extensions.
3. Select **ManaPool**.
4. Run the extension.

The extension will select the supported sets, including applicable subcategories.

### 3. ComicBookStore

**Starting point:** The Magic: The Gathering store page.

You must first navigate to the Magic: The Gathering store page through the site's category navigation.

1. Navigate to ComicBookStore.
2. Go to **Categories → Magic**.
3. Pick any set.
4. This will take you to the Magic: The Gathering store page.
5. Remove the set you selected in the previous step from the active filters.
6. Open Premodern Set Shopper from your Chrome extensions.
7. Select **ComicBookStore**.
8. Run the extension.

**Important:** Make sure you remove the initially selected set before running the extension. Otherwise, that set will remain part of your search results.

## Execution Results

After running the extension, the results panel provides a breakdown of the set-selection process:

| Result | Meaning |
|---|---|
| Found | Sets available in the marketplace filter |
| Newly Selected | Sets the extension successfully selected |
| Already Selected | Sets that were selected before execution |
| Not Found | Supported sets that were not available in the marketplace filter |

This makes it easy to see whether the marketplace contains all the expected sets.

## Notes

- The extension does not automatically navigate to seller stores or marketplace pages. You must navigate to the correct starting point first.
- Existing marketplace filters may affect the final search results. Follow the marketplace-specific instructions above before running the extension.
- The extension only selects sets; it does not modify card listings or purchase anything.

## Version

**Current version:** 2.0.1
