
This is one of my apps for the TidByt. You can pull images from an endpoint that serves images or a JSON feed. Things like random image endpoints are an ideal use.

This repo is intended as a testing and staging area before things get pushed to https://github.com/tidbyt/community/tree/main/apps/apiimage. Make sure to do an [advanced build of pixlet](https://tidbyt.dev/docs/build/advanced-installation) so you can run the commands below.

After making changes:

* Create a fork and run ```lint```,```format```, and ```check``` before commiting your changes for review
* Once review passes, create fork of https://github.com/tidbyt/community/tree/main
* Copy api_image.star file to forked apps/apiimage/api_image, run formatter/linter and push changes to fork for review
* Create a PR if automated tests pass

Example usages:

-----

API URL: ```https://cataas.com/cat/gif?height=32```

Fit screen: ```On```

![Cats API](https://michaelyagi.github.io/images/api_image_1.gif)

-----

API URL: ```https://dog.ceo/api/breeds/image/random```

Response path: ```message```

![Dogs API](https://michaelyagi.github.io/images/api_image_2.gif)

-----

API URL: ```https://nuthatch.lastelm.software/v2/birds```

Response path: ```entities,[rand],images,0```

Request headers: ```api-key:<api_key>```

Fit screen: ```On```

* Note the [rand] keyword chooses from a random index according to the list length

![Ducks API](https://michaelyagi.github.io/images/api_image_3.gif)
