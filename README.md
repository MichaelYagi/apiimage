Testing and staging area before things get pushed to https://github.com/tidbyt/community/tree/main/apps/apiimage. Make sure to do an [advanced build of pixlet](https://tidbyt.dev/docs/build/advanced-installation) so you can run the commands below.

After making changes:

* Run ```format```, ```render``` and ```check``` and commit to this repo
* Create fork of https://github.com/tidbyt/community/tree/main
* Copy api_image.star file to fork apps/apiimage/api_image and push changes to fork for review
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

![Ducks API](https://michaelyagi.github.io/images/api_image_3.gif)
