# CJ Affiliate Tag for Google Tag Manager(server-side)

The CJ Affiliate Tag allows advertisers to store a server-side cookie for CJ's click ID and send a conversion event (S2S) to CJ Affiliate.

## How to use the CJ Affiliate tag

CJ Affiliate Tag tracks two event types:

- *Pageview event* reads the CJ's click ID parameter from the URL (`cjevent`) and stores it on a server-side cookie named `cje`.
- *Conversion events* sends the conversion to CJ Affiliate.

This template is a tag that reads the standard event schema that’s sent from the client running on a tagging server. It then converts the conversion event to the appropriate schema and sends it through CJ API. The Tag supports only the [GA4 Client](https://developers.google.com/tag-manager/serverside/send-data#server-side_client_configuration)

# Reporting Bugs/Feedback
Please raise any issue on GitHub
