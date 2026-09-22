# Program terms (free program)

Status: **draft, pending legal review.** Rewritten 2026-09-22 when the
program went free and Stripe was removed. Plain-language descendant of
Andrew's original checkout disclaimer. Not yet lawyer-blessed. Confirm
Quebec Consumer Protection Act fit, the negligence carve-out, and GFM
coverage before use.

This text is what the "terms and conditions" modal on the landing page
shows. Keep the two in sync (`landing/index.html`, `#terms-modal`).

## Disclaimer text

> By checking this box, you agree:
>
> When we say "we," we mean both Orisha and Growing for Market.
> Everything here covers both of us.
>
> What works on one farm may not work on yours. Before you try any
> idea from the program, it's on you to make sure it fits your farm,
> your climate, and your local rules. You join at your own risk.
>
> The program is free, so there is nothing to refund. If something
> goes wrong and we're held responsible, even if it's our fault, our
> responsibility is limited as far as the law allows.

## What changed when the program went free

The original last line was *"the most you can get back is what you
paid us."* That capped liability at the amount paid, which is zero
once nobody pays. A zero cap is the kind of clause a court is most
likely to strike, and leaving it in reads as sharp practice. The
replacement states the free status plainly and defers the limit to
whatever the law actually allows.

**This substitution is a legal judgment call made without a lawyer.**
It is the open item most in need of review below.

## Open items for the lawyer

- **Liability limit with no consideration.** A free program means no
  payment from the farmer. Confirm the limitation clause still holds,
  and whether "limited as far as the law allows" is the right formula
  in Quebec, or whether a specific cap should be named instead.
- Negligence carve-out: confirm "even if it's our fault" still reads
  as covering ordinary negligence.
- Dropped the explicit "what's covered" list (coaching, courses,
  community, apps). Plain "if something goes wrong" is broad; lawyer
  may want the list back for certainty.
- GFM as covered party: confirm the "we = both" line actually
  protects Growing for Market now that no merchant relationship
  exists on the Orisha side.
- Governing law / venue: none stated. Decide if needed.
- Checkbox mechanics: must be unchecked by default, required before
  joining, actively checked by the farmer. (Still enforced in the
  page: the Join button blocks until the box is checked.)
- **Personal data.** The page now collects an email address and posts
  it to an Airtable automation, then sends the farmer to a Circle
  community. Neither was true at checkout time. Confirm whether a
  privacy notice or consent line is required at the point of
  collection under Law 25.
