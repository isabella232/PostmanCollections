
# Postman Collections

This repo contains full postman collections for most of the MessageMedia APIs. This will be added to over time.

## Instructions for Getting Started

You can use these by cloning the repo and importing into your Postman Application OR with the buttons below.

First sign up for a developer key and receive your starter credit at:

https://developers.messagemedia.com/register/

Be sure to keep this somewhere safe after you register. 

Click on the collection you want to use below and it will open up in Postman. In the side draw for postman hover over the top level of the collection that jsut imported until you see the three dots. Click on the three dots menu, and select edit, to select the collection level details.  

![step1](/img/topleveledit1.png)

Go to the variables tab and make sure the username and password variables are present and have been updated to be your username (developer key) and password (developer secret). 

![step2](/img/usernamepasswordedit.png)

Go to the authorisation tab and check that the authorisation type is set to Basic Auth and the username and password reference the variables. 

![step3](/img/authorisationedit.png)

All other sublevels of the collection should have all set to "Inherit auth from parent".

You can now run the collections by changing the relevant key value pairs. Be sure to consult the documentation for which ones are required and which ones you can delete as well as information about what each key value pair is for. 

### Messages

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/11b2a979fa10c6564f77)

### Lookups

Our Lookups API provides a simple way to keep your database clean. It accesses mobile carrier information about any mobile number, in real-time, anywhere in the world.

To learn more about the benefits of using the Lookups API, visit our [product page](https://www.messagemedia.com/au/feature/lookups/).

In the collection update the headers with your parameters. Enter your phone number, and one or more of the lookup type. You can use "carrier, type" together or individually (seperate with a comma). Option "hlr" can only be used individually.

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/7dbb0007cff1630317b5)

### Short Trackable Links

Short Trackable Links is a feature available to [Messaging API](https://developers.messagemedia.com/code/messages-api-documentation/) users whereby it automatically and seamlessly shortens any URL to just 22 characters. Every shortened URL is unique to each recipient.

The reporting API has endpoints specific to 
this feature, allowing users to obtain details regarding 
the number of click-throughs on each URL.

To enable this feature on your account, contact your account manager or contact support on [support@messagemedia.com](support@messagemedia.com).

To learn more about the benefits of the Short Trackable Links feature, [visit our feature page](https://messagemedia.com/au/feature/short-urls/).

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/6183fd2040995b67332b)

### Webhooks Management

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/4484dfbb1fef44e53094)

### Reporting

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/4328b75d99c64a439e39)

### Signature Key Management

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/e301a1cb751032a3d32f)

### Number Authorisation

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/0cb82955424cc2d15b48)

### Numbers 

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/b7c172bf5249e7130f7f)

### Conversations

N.B. Conversations API is in beta and requires account activation, see MessageMedia docs.

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/9c0f67ae55f173310d33)
