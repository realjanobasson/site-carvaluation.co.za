# carvaluation.co.za

Production Cloudflare Worker website for **Car Valuation**, part of the DealershipCore ecosystem.

## Included

- Responsive domain-specific public website
- Accessible navigation, reveal motion and reduced-motion support
- Persistent enquiry handoff to `https://dealership.janobasson.com/api/enquiries`
- Source, campaign and consent capture
- Privacy, terms, 404, sitemap and robots files
- Worker health endpoint at `/api/health`
- Automated source checks

## Commands

```bash
npm install
npm run check
npm run dev
npm run deploy
```

The enquiry endpoint never reports success unless the central DealershipCore API confirms persistence.
