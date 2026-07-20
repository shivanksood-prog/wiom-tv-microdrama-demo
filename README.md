# Wiom TV — microdrama promo channel (demo)

Static export of the real wiom.tv app with the microdrama promo channel (ch 21).
Frontend is production code; the backend is mocked (events go to
`window.__wiomEvents` instead of `/api/event`, and the payment is simulated).

- `?md_reset=1` — clear the 12-hour pass and rotation cursor
- `?md_demo=1` — jump each promo near its end, to reach the offer in seconds
- `window.__wiomEvents` — the captured funnel

Live TV channels will not play here (broadcaster CDNs block this origin); the
microdrama channel is the point of the demo.
