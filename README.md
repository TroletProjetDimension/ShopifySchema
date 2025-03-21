# Shopify Schema

This repository holds the Trolet shopify store's entire GraphiQL schema, for both the Storefront and Admin API. This way, every 20 minutes, a job runs which runs introspection on both API graphiql schema endpoints and saves them in `/admin` and `storefront`. 
This isolates types from projects where these specifications can be consumed.
