# mcm-postman-templates
The Moloco MCM Postman templates help you easily start with Moloco’s APIs, such as Decision APIs, Event API and Management APIs.

# Requirements

You need to have Postman [app](https://www.postman.com/) installed on your system before you start using the MCM Postman template. 

# Importing Collections and Environment variable

> 📘 Download the template json files from [GitHub](https://github.com/moloco-mcm/mcm-postman-templates) repository and import by following below steps

1. Open Postman app
2. Import all Collections from Collection .json files through import button on Collections tab

   ![](https://files.readme.io/b5d4baa8fc458b84059f2b95853d819fcdba722fa6800afd0d7604a89c09de3b-image.png)
3. import Environments Variables from Environment .json file through import button on Environments tab

   ![](https://files.readme.io/4d59ef4407c44a61d044c68b15ec74772c5d5339d83f0e2abbbfd5f4ed68f4da-image.png)

# Configuration

> 📘 You need to prepare API urls provided by Moloco representative

1. Go to Environment tab and Input your API url addresses on `dcsn_url, mgmt_url, event_url`  
2. input your API keys on `mgmt_api_key, dscn_api_key, event_api_key`  
   1. If you don't have those keys, please generate them by referring to [guide](https://mcm-docs.moloco.com/docs/api-and-sso-credential-management)
3. Input your Platform ID on `platform_id`
4. Do not input anything for `request_id` . This will be automatically generated through pre-script when you fire any relevant API
5. Make sure to save before leaving Environment tab

![](https://files.readme.io/a26a3ab4bbaf8a024962a3caf072c719ae992b02264c69548cd17b70c18ed74e-image.png)

<br />

# Sending API request

1. Before you start sending request, make sure to choose environment where you input those variables from configuration steps
2. Make sure to input all necessary params from params tab
3. If the API requires body contents, input the body value by referring to the sample body within the template and API [reference](https://mcm-docs.moloco.com/reference)

![](https://files.readme.io/70e791aff7b78612fcb5d485e0de8abcbc02eb3c74aee87dafac22b4d4d90142-image.png)
