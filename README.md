# CJ Affiliate Tag for Google Tag Manager (server-side)

The CJ Affiliate Tag allows advertisers to store a server-side cookie for CJ's click ID and send a conversion event (S2S) to CJ Affiliate.

## How does the Addingwell tag work?

This template is a tag that reads the standard event schema that’s sent from the client running on a tagging server. It then converts the conversion event to the appropriate schema and sends it through CJ API.

CJ Affiliate Tag tracks two event types:
- Pageview event reads the CJ's click ID parameter from the URL (cjevent) and stores it on a server-side cookie named cje.
- Conversion event sends the conversion to CJ Affiliate.

The tag supports only GA4 client.

## Implementation

You can follow our [step-by-step instructions](https://docs.addingwell.com/cj-affiliate/import-cj-affiliate-tag-google-tag-manager).

## Reporting Bugs/Feedback

Please raise any issues on GitHub or contact us directly at support@addingwell.com.

## Open Source

CJ Affiliate Tag for GTM Server Side is developed and maintained by [Addingwell](https://www.addingwell.com/) under the Apache 2.0 license.
