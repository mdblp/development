## TODO
### Hydrophone
* [x] Modify the service so it can use SMTP instead of AWS SES.
* [x] Create html templates (copy from diabeloop or tidepool) customized for la Charité.
* [ ] Define a storage for public assets
* [ ] Create the localization/transalation file (de.yaml)
* [ ] Review generated emails to make sure everything looks fine and we don't keep tidepool or diabeloop links/email@
* [ ] Save the template in this repo and update the configuration variable `i18nTemplatesPath`
* [ ] Build docker image and make it available (where?)
* [ ] Configure smtp and email address

### Blip
* Use Diabeloop version? Yes
* [x] Customize links, remove Zendesk integration... (config)
* [ ] Update download link for the _Tidepool Uploader tool_ to point to the relavant url
* [x] Create the localization file (de)
* [x] Prepare the logo and favicon
* [x] Build docker image and make it available (where?)
* [x] Define a url where to store public assets such as terms of use, logo, uploader binaries

### Uploader
* [x] Fork the repo and remove tidepool specifics
* [x] Set the correct api url
* [ ] Build the executable and publish it on La Charité servers?
* [x] Make Jellyfish service publicly availlable on ddc-upload.charite.de

### Mongo configuration
* [x] Create different mongo users
* [x] Update docker stack configuration
