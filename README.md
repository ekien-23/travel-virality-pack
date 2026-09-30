# Travel Virality Pack - x402

Pay-per-use API for travel creators on Base.

Endpoint: https://travel-caption-agent.vercel.app/api/virality?image=beach
Price: $0.03 USDC on Base
PayTo: 0x1c92f0c2c63255840313d82b13295ecc83503c04

Returns: caption + 25 hashtags + altText + bestTime

Test: curl -i https://travel-caption-agent.vercel.app/api/virality?image=beach
Should return HTTP 402 with x402 payment instructions.
