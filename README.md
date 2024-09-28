Testing and staging area before things get pushed to https://github.com/tidbyt/community/tree/main/apps/apiimage. Make sure to do an [advanced build of pixlet](https://tidbyt.dev/docs/build/advanced-installation) so you can run the commands below.

After making changes:

* Run ```format```, ```render``` and ```check``` and commit to this repo
* Create fork of https://github.com/tidbyt/community/tree/main
* Copy api_image.star file to fork apps/apiimage/api_image and push changes to fork for review
* Create a PR if automated tests pass
