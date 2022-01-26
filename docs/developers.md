# Developer APIs Guide
Are you a developer looking to integrate your script, app or website with Space Pool data? Good news, Space Pool has public developer REST APIs specifically built for this purpose.
The developer APIs allow authorized 3rd party developers to officially access both pool statistics as well as individual farmer statistics programmatically.

## OpenAPI Spec 
For a detailed list of the developer APIs, API documentation can be found at [https://developer.pool.space](https://developer.pool.space). The developer APIs also support the OpenAPI standard- for anyone looking to auto-generate clients please see the OpenAPI JSON spec at [https://developer.pool.space/api/v1/docs/openapi.json](https://developer.pool.space/api/v1/docs/openapi.json)
Any developer interested in using the developer APIs should follow the below instructions.

## Developer onboarding instructions
Request a Developer API key (see below for instructions)
Visit [https://developer.pool.space](https://developer.pool.space) for API documentation or use the OpenAPI JSON spec at [https://developer.pool.space/api/v1/docs/openapi.json](https://developer.pool.space/api/v1/docs/openapi.json) to build your app client
Make all API requests against the ```https://developer.pool.space``` domain and use the /api/v1 path prefix for all API requests
Make sure to include your developer API key in the headers of the web request along with a user agent string. Please use ```Developer-Key``` and ```User-Agent``` as the respective header names in the requests for authorization

### How to request a developer API key
To request an API key:
1. Login to your account settings on the Space Pool webpage (see [this blog post](https://blog.pool.space/enabling-health-notifications-on-discord-for-your-chia-farm-in-space-pool-da9bb1368260) for more info)
1. Tap the ‘Request API Key’
1. Enter the requested information
1. Tap the ‘Save’ button

If you have any issues with this self-service flow, please visit the [Space Pool discord](https://pool.space/discord) #developer-api-requests channel and make a post with the following information:

1. Your Space Pool launcher id
1. Your discord id (if different from the discord account requesting)
1. Your application name and use case for requesting access
1. Whether your application will be public or private use
1. Your expected request rate (requests per second/minute) and estimated user count for your app
1. Details on the issue you experienced with self-service flow above

Once the above information is provided a member of the Space Pool team will respond back in discord DM to review your use case and provide a developer API key for use with the developer APIs.
**Note that only APIs deemed as public developer APIs documented on [https://developer.pool.space](https://developer.pool.space) are authorized for 3rd party use. 3rd party usage or scraping of any other APIs is unauthorized and may result in account restrictions or suspension.**
