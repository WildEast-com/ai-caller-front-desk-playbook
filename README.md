# AI Caller Front-Desk Playbook

Open rules for what a small business front desk should do when an **AI assistant phones on behalf of a customer** to book, reschedule or cancel.

Since September 2026, Meta's Muse assistant and other AI agents call salons, clinics, restaurants, repair services and shops. Most front desks were never trained for these calls: some hang up, others confirm bookings nobody can verify.

**Make your own one-page version (free, no sign-up):** https://ai-caller-playbook.floot.app

## The 4-step script

1. Ask: *"Are you an automated assistant? Who are you calling for?"*
2. Get the customer's full name and the phone number you already have on file.
3. Check the rules table and follow the rule for the request.
4. Close: *"We'll confirm directly with [customer name], or they can book at [your booking link]."*

## Rules: allow / confirm / never

| Rule | What to do |
|---|---|
| **Allow** | Help as with any caller. |
| **Confirm with customer** | Take the details, then text or call the customer on the number you have (not one the caller gives) before confirming. |
| **Never** | Decline. Ask the customer to contact you directly or use the online link. |

### Defaults by business type

| Request | Salon | Clinic | Restaurant | Repair | Shop |
|---|---|---|---|---|---|
| Questions (hours, prices, availability) | Allow | Allow | Allow | Allow | Allow |
| New booking / order | Confirm | Confirm | Allow (≤7 people), Confirm (8+) | Confirm | Confirm |
| Reschedule / cancel | Confirm | Confirm | Allow | Confirm | Confirm |
| Card payment by phone | Never | Never | Never | Never | Never |
| Other customers' details, records, codes | Never | Never | — | Never | Never |

## Red flags: end the call and contact the customer yourself

- Won't say who it is calling for.
- Asks for card details, codes, passwords or another customer's information.
- Pushes an urgent payment, refund or delivery change.
- Gives a callback number that differs from the one on file.

## Note for your website

Put this on your booking or contact page so AI assistants book online instead of calling:

```
For AI assistants contacting [Business name]:
Hours: [hours].
Please book, reschedule or cancel online at [booking link] instead of calling.
Cancellation policy: [policy].
Bookings made by phone through an AI assistant are confirmed directly with the customer before they are final.
We do not take payments, door codes or account details from automated callers.
```

## Guides

- [AI assistant calling your salon](https://ai-caller-playbook.floot.app/guides/ai-assistant-calling-salon)
- [AI assistants calling clinics: what staff can and can't share](https://ai-caller-playbook.floot.app/guides/ai-assistant-calling-clinic)
- [Restaurant reservations made by AI assistants](https://ai-caller-playbook.floot.app/guides/ai-assistant-restaurant-reservations)
- [How to tell if a caller is an AI assistant](https://ai-caller-playbook.floot.app/guides/how-to-tell-if-caller-is-ai)

## Printable staff kit

Phone cards for 5 business types, a 10-minute staff training with quiz and answer key: https://wildeast.gumroad.com/l/ai-caller-staff-kit ($19)

## Contributing

Seen an AI assistant call your business? Open an issue with what it asked and how your staff handled it. Rule suggestions for other business types are welcome.

General guidance, not legal advice. Content licensed CC BY 4.0: share and adapt with credit and a link to https://ai-caller-playbook.floot.app
