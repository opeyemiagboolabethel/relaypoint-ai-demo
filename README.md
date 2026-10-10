# RelayPoint AI

Standalone ONE Light Analytics logistics operating demonstration. Independent of CedarStone.

## Deploy to Streamlit

Repository: `opeyemiagboolabethel/relaypoint-ai-demo`
Branch: `main`
Main file: `streamlit_app.py`
Requested subdomain: `relaypoint-ai-demo` (subject to availability).

Configure `GEMINI_API_KEY` or `GOOGLE_API_KEY` privately in Streamlit Secrets for Live AI. Without a key, Scenario mode works. Never commit secrets.

## Scope

48 fictional shipment records, fixed 9 October 2026 09:00 WAT snapshot, role-scoped tools, session-isolated state, customer drafts and explicitly confirmed simulated allocations. No real messages, GPS or dispatch. Model tools can read and propose; only reviewed UI actions commit sandbox changes.

## Verify

`python -m unittest test_logistics -q`

`python test_logistics_agent.py`

`python test_logistics_app.py`
