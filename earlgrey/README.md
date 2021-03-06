## Espresso-BrowserStack-AppAutomate-Parallel

[EarlGrey](https://opensource.google/projects/earlgrey) Integration with Browserstack

![BrowserStack Logo](https://d98b8t1nnulk5.cloudfront.net/production/images/layout/logo-header.png?1469004780)

Running and Controlling and Parallel Test on BrowserStack App-Automate Frameworks ([Espresso](https://github.com/RathilVasani/Bstack-AppAutomate-Parallel/tree/master/espresso), [XCUITest](https://github.com/RathilVasani/Bstack-AppAutomate-Parallel/tree/master/xcuitest),[EarlGrey](https://github.com/RathilVasani/Bstack-AppAutomate-Parallel/tree/master/earlgrey))

## Setup

- Clone the repo
- Python setup
- Upload App and Test App on [BrowserStack](https://www.browserstack.com/app-automate/rest-api?framework=earlgrey)
- Update `earlgrey_runner.py` with your [BrowserStack Username and Access Key](https://www.browserstack.com/accounts/settings)
- To generate lastest `device.json` run [device-list Generator](https://github.com/RathilVasani/Bstack-AppAutomate-Parallel)

## Run Test

- To run test  execute `python earlgrey_runner.py <os-device.json> <app-url/CustomID>`

## Notes
* You can view your test results on the [BrowserStack App-Automate dashboard](https://app-automate.browserstack.com/)
* To test on a different set of devices, check out our [platform configurator](https://www.browserstack.com/list-of-browsers-and-platforms/app_automate)
* You can export the environment variables for the Username and Access Key of your BrowserStack account

  ```
  export BROWSERSTACK_USERNAME=<browserstack-username> &&
  export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>
  ```
## Additional Resource
- [Running EarlGrey Test with BrowserStack](https://www.browserstack.com/app-automate/earlgrey/get-started)
- [BrowserStack EarlGrey REST APIs](https://www.browserstack.com/app-automate/rest-api?framework=earlgrey)
