# Mymarket for Gemini CLI

Search the listings and shops on [mymarket.az](https://mymarket.az), the Azerbaijani classifieds site, from Gemini CLI: goods, services and job vacancies. No account or API key is needed.

## Install

```bash
gemini extensions install https://github.com/alik472/mymarket-gemini-extension
```

That is all: there is no account, sign-in or API key.

## What you can ask

- Find a sofa (divan) in Baku under 300 AZN.
- Show waiter (ofisiant) job vacancies in Baku.
- What categories does Mymarket have?
- Find the shop that sells Lego and show its newest listings.

## Tools

| Tool | What it does |
| --- | --- |
| `search_listings` | Listings by keyword, category, city, shop and price range, newest or cheapest first. |
| `get_listing` | Details of one listing from its number or mymarket.az link: price, description, photos and link. |
| `list_categories` | Top-level categories, one category's subcategories, or categories found by name. |
| `list_stores` | Shops that sell on Mymarket with their rating, number of listings and page. |
| `get_store` | One shop's description, rating and newest listings. |

## Good to know

- Every tool only reads public listings. Nothing can be posted, bought or paid for, and no seller is contacted.
- Seller phone numbers, emails and private names are never returned. To contact a seller, open the listing link on mymarket.az.
- Listings are mostly written in Azerbaijani; search words in Azerbaijani find the most results. Prices are usually in AZN.

## Other MCP clients

The extension only points Gemini CLI at Mymarket's hosted MCP server (streamable HTTP):

```
https://mymarket.az/mcp
```

Any MCP client that supports remote servers can use the same address. It needs no authentication.

## Links

[Website](https://mymarket.az) · [About the AI tools](https://mymarket.az/ai-assistants) · [Privacy](https://mymarket.az/ai-assistants/privacy) · [Terms](https://mymarket.az/ai-assistants/terms)

## License

The files in this repository are released under the MIT License. The Mymarket service itself is covered by its terms.
