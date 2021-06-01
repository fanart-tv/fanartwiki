# __Personal API Keys__

With the launch of *[v3](https://fanarttv.docs.apiary.io/#reference){target= blank}* - of the API we also introduced the concept of personal API keys, but it seems we never really posted anywhere why we added them or the benefits of using a personal API key.

There were a couple of reasons for adding personal API keys, the first was to try and help with our problem of obscurity, last year our API was used nearly 2 billion times, but 99.9% of end users using our service will never have heard of us.

Some well meaning developers make their end users get their own API key to use, but this makes it hard for us to check where traffic is coming from and if there are any potential issues with the service.

Having personal API keys means the developer can use their own developer API key for the software and direct their end users to the site to [obtain a personal API key.](https://fanart.tv/get-an-api-key/){target= blank}.

The second reason was to reward members who help our continued survival by becoming [VIP members](vip.md), these users benefit from earlier access to newly approved images via the API.

V2 API requests are 2 weeks behind, v3 requests are a week behind, v3 requests with a personal API key are 2 days behind and v3 requests with a personal API key and the user is a VIP member are up to date.

I will explain this with an example.

- User ArieS has an image approved on the 1st of January 2015
- Software using v2 of the API will see that image on the 15th of January.
- Software using v3 of the API will see that image on the 8th of January.
- Software using v3 AND sending a users valid personal API key will see that image on the 3rd of January.
- Software using v3, sending a valid personal API key, and that user is a VIP member will see the image immediately.
- The end goal is to get more eyes to the site, the more exposure and people coming to the site we get, the more submissions we will get, the more people creating tutorials for the site, the more people wanting to help out and become moderators (in - theory at any rate) which can only be a benefit to everyone.

So if you use software that utilises our API, please encourage them to implement personal API keys in it.

If the software you use has already implemented personal API keys, you can get your personal API key [here](https://fanart.tv/get-an-api-key/){target= blank}. You will need to be logged in to request a personal API key.

Other benefits for [VIP Members](vip.md) include:

- Quicker API responses
- Hide all advertising
- Members only discussion forum
- VIP badge
- Additional 3 requests
- Additional 5 pending
- Between 2 to 4 votes per image