# Merchant Pro website

Private review website. Run npm run dev, npm run build. The Windows ARM host requires the locally ignored x64 Node runtime for workerd.

## Before accepting online inquiries

/api/review validates input and fails closed with HTTP 503 until an approved CRM or delivery integration is configured. No inquiry is stored, emailed, or marked received. Telephone and email contact links work. Implement destination delivery, persistent abuse protection and idempotency together, and confirm receipt before enabling success responses. Never collect statements or card data through this initial inquiry form.

## Before public launch

Confirm company copy/contact details, legal privacy notice, current equipment availability, and intake destination. Replace private preview noindex metadata only after launch approval. No existing domain or DNS has been changed.

## Assets

public/images/gary-baillio.jpg: Merchant Pro website, /wp-content/uploads/2026/08/garry.jpg, 160×160 original.
public/images/clover-mini.jpg: Merchant Pro website, /wp-content/themes/merchantpro/assets/images/clover-mini1.jpg, 556×340 original. Illustrative device; availability unconfirmed.
Private training manual is not included. No third-party tracking scripts, stock testimonials, savings claims, or certification badges were added.

