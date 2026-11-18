---
name: design-with-genpire
description: Design products in the person's own Genpire account. Use when they want to create, change, compare, restyle or document a product (size guide, specs, tech pack), explore product ideas, try colours or Pantone matches, make a moodboard, print files or Studio images, write a sales description, or prepare a factory quote request.
---

# Design with Genpire

Genpire is a product design studio. Everything made here is saved in the person's own Genpire account and is called a
"product", whatever its category. The Genpire tools come from the Genpire connector in this plugin.

## Getting started

- If the Genpire tools are not available yet, ask the person to connect Genpire and sign in with their Genpire
  account.
- To see what they already have, use `list_my_products`, then `get_product` for the one they mean. Use
  `list_my_brands` when they mention a brand style.
- To start something new, use `create_product` with their description. If they are looking for inspiration first, use
  `explore_ideas` and let them pick an idea.

## Working on a product

- Change a product in words with `edit_product`; draw it again with `redraw_product`.
- To compare looks, use `show_options`, then `use_option` for the one they choose.
- Restyle in a brand style with `apply_brand`.
- Technical documents (size guide, specs or a full tech pack): `make_tech_documents`.
- Colours: `suggest_colours`, `make_colour_previews` and `match_pantone`.
- Inspiration and files: `make_moodboard` and `make_print_files`.
- Product images: `make_studio_images` (product-only styles).
- A sales description: `write_description`.

## Longer work

Drawing and documents can take a while. When a tool returns a job, tell the person it is running and check it with
`get_job` when they ask, or after a short wait. Never invent a result before the job is done.

## Quotes from factories

Use `prepare_quote_request` to prepare a request for a sample or a bulk order, then show the details. The person sends
it from the product in Genpire. Never ask for an address or a phone number in the chat: those stay in Genpire.

## Rules

- Refer to products, jobs, ideas and brand styles only by the handles the tools return. Never guess or build one.
- Plan usage is shown only as the percentage left (`get_usage`). Never state amounts, prices or credit numbers.
- Images of people and the person's own uploaded images are not available here; suggest Genpire for those.
- Point the person to the Genpire link a tool returns to keep working in the Genpire editor.
