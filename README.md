This is one of my apps for the TidByt. You can pull images from an endpoint that serves images or JSON. Things like random image endpoints are an ideal use.

This repo is intended as a testing and staging area before things get pushed to https://github.com/tidbyt/community/tree/main/apps/apiimage.

https://github.com/public-apis/public-apis is a great resource for APIs you can use for this app.

Example usages:

-----

API URL: ```https://media.tenor.com/0fCHAuYZRoYAAAAM/akira-shotaro-kaneda.gif```

Fit screen: ```On```

![Gifs API](https://michaelyagi.github.io/images/api_image_4.gif)

-----

API URL: ```https://dog.ceo/api/breeds/image/random```

Response path: ```message```

![Dogs API](https://michaelyagi.github.io/images/api_image_2.gif)

-----

API URL: ```https://nuthatch.lastelm.software/v2/birds```

Response path: ```entities,[rand],images,[rand]```

Request headers: ```api-key:<api_key>```

Fit screen: ```On```

* Note the [rand] keyword chooses from a random index each time it's called according to the list length

![Ducks API](https://michaelyagi.github.io/images/api_image_3.gif)
