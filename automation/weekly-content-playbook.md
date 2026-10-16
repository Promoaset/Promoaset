# Weekly content playbook

## Objective

Every Monday at 07:00 Europe/London, create one review-ready article draft for ViKlandCraft that can eventually earn from relevant woodworking and craft affiliate links.

## Run steps

1. Read `automation/content-queue.csv` and select the earliest row with status `planned`.
2. Research the topic using current primary sources where possible. For products, check the retailer/manufacturer page rather than copying a marketplace description. Record the date checked and the source URLs.
3. Draft 1,200–1,800 words in plain UK English. The article must add first-hand or genuinely useful editorial value: decision criteria, measurements, a bill of materials, tested workflow, limitations, or safety context. Do not invent tests, ownership, prices, discounts, stock, ratings or personal experience.
4. If the article is wholly about affiliate-linked products, begin the title with `Ad: `; otherwise put the affiliate disclosure before the first recommendation and immediately before each affiliate block. Use `compliance/affiliate-disclosure.md`.
5. Include a short “What I would choose” section, a “Check before buying” section, and a safety note where tools, dust, solvents, resin or power equipment are mentioned.
6. Do not add live affiliate URLs unless an approved programme ID and the exact link are present in `automation/link-register.csv`. Use `[affiliate link pending]` when not present.
7. Run the quality gate:
   - every product fact has a source or is clearly labelled as requiring verification;
   - no unsupported superlatives or fabricated first-hand claims;
   - disclosure is visible before engagement;
   - prices and availability are marked as changeable;
   - no medical, legal or financial claims;
   - no unsafe instruction that conflicts with the manufacturer’s instructions;
   - no copied or lightly rewritten retailer text;
   - slug, excerpt, headings, internal-link suggestions and image brief are present.
8. Save the draft as `drafts/<next-number>-<slug>.md` with YAML front matter containing `status: review`, `source_checked_at`, `target_query`, `commercial_intent`, and `affiliate_links: pending`.
9. Update the selected queue row to `drafted` and add the draft path and date. Do not mark it published.
10. Produce a concise report listing the draft path, key sources, unresolved checks, and the next human action. Never apply for a programme, buy a plan, publish, delete data, or alter account security.

## Monetisation rules

Prioritise content where a reader is close to a buying decision, but keep the editorial recommendation honest. Use several retailers or a non-affiliate alternative where that helps the reader. Never make the commission the reason to recommend a product.

## Stop conditions

Stop and report instead of drafting if the topic is unsafe, the source material is unavailable, the product is regulated or recalled, the queue has no planned row, the site’s niche has materially changed, or a required claim cannot be verified.
