# make-automation-workflows
Production automation scenarios built with Make.com, connected to Claude API 
and HubSpot CRM for a live e-commerce business. All workflows are documented 
with real business context — not tutorial recreations.

## Workflows Built

### Email Triage & Routing
**Problem:** Inbound customer emails were handled manually with no 
prioritization or consistent response structure.

**Solution:** Make.com scenario that:
- Receives inbound email via webhook trigger
- Sends content to Claude API for intent classification
- Routes to response template based on classification
- Logs interaction to HubSpot CRM with intent tag
- Flags damage claims and urgent issues for immediate human review

**Result:** Zero manual sorting. Every email classified and routed 
automatically within seconds of receipt.

### HubSpot CRM Integration
**Problem:** B2B outreach to landscape architects and pool companies 
had no tracking system — follow-ups were getting missed.

**Solution:** Make.com workflow that:
- Creates and updates HubSpot contact records from outreach activity
- Tracks email open and response status
- Triggers follow-up reminders based on response timeline
- Tags contacts by business type and outreach stage

### Buffer Social Media Pipeline
**Problem:** Consistent social posting required daily manual effort.

**Solution:** Make.com webhook pipeline connected to Buffer that:
- Accepts product and content data as input
- Formats posts for each platform automatically
- Schedules to Buffer queue via API
- Maintains brand voice consistency across platforms

## Tech Stack
Make.com · Claude API · HubSpot CRM · Buffer · 
Webhook Architecture · JSON · REST APIs

## About
These workflows run on a live Shopify store. Every scenario here 
was built to solve a real operational problem, not as a portfolio exercise.
