# Mymarket

These tools search the public listings and shops on mymarket.az, the Azerbaijani classifieds site (goods, services and job vacancies). No account is needed and every tool only reads.

- `search_listings` matches every keyword in the title or description. Listings are mostly in Azerbaijani: search with Azerbaijani words (divan, ofisiant, mühasib) when the user writes in another language. Narrow with `category_id` from `list_categories`, `city`, `store` or a price range.
- `get_listing` with a post number or a mymarket.az/elan/ link gives the details, photos and the link.
- `list_stores` and `get_store` cover the shops that sell on the site.

Quote prices with their currency (usually AZN) and give the mymarket.az link of each listing. The tools never return phone numbers or emails: to contact a seller or buy, the user opens the listing on mymarket.az. Do not invent listings when a search returns none; suggest other words or a wider filter.
