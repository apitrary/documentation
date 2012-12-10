# Getting started

This is the getting started guide which will lead you through easy steps in order to successfully deploy your apitrary backend.

For this guide you should already have successfully signed up for apitrary. If not, please make sure to [sign up now](http://launchpad.apitrary.com/ "Sign up for apitrary") in order to continue with the guide. You can quickly sign up on [Launchpad](http://launchpad.apitrary.com/ "Launchpad").

## APIs and Entities

apitrary uses RESTful APIs which can easily be created in [Launchpad](http://launchpad.apitrary.com/ "Launchpad"). Each API then needs to be configured by creating *entities* which will provide your endpoints. Once those endpoints have been created you can instantly start working with your API.

We will now walk you through the process of creating an API with an entity.

## Creating APIs

Once you have [signed up](https://launchpad.apitrary.com "Launchpad"), simply login into [Launchpad](https://launchpad.apitrary.com "Launchpad"). On your first login, you will not have an API, yet. Click the *Create API* button to start creating your first API.

![getting_started-create_api_button](../images/getting_started-create_api_button.png "Create API")

You should now see the API Create box:

![API Create box](../images/getting_started-api_create_input_box.png "API Create box")

Fill in the name of your API and, optionally, a short description. Finish by clicking *Create API*. You should now see a new API:

![New API](../images/getting_started-api_created.png "API created")

You have successfully created your first API. Now continue to edit your API by adding entities.

## Adding entities

Adding entities to your API is just as easy. Click the *Edit Entities* which will bring you to **Kolay**, our API editor.

![New Entity](../images/getting_started-kolay-add_entity.png "New Entity")

Click *New Entity* to create your first entity and add a descriptive name.

**Please note:** Entity names should be **lower-case**!

![Enter Entity name](../images/getting_started-kolay-new_entity_box.png "Enter entity name")

Add more entities as you need!

In case your plan does not provide the number of entities you require, add more entities through our add-ons.

**BETA NOTICE!** Due to our current *Beta stadium*, we still have a few limitations:

- add-ons are still not available *(coming in the near future)*
- entities cannot be deleted after deployment *(coming soon)*
- functionality to add *attributes* to entities is not yet provided *(coming soon)*

**Great!** You are just about to deploy your first API!

## Deploying an API

Once you are finished with adding entities, click the *Deploy* button:

![Deploy your API](../images/getting_started-kolay-deploy.png "Deploy your API")

You can now return back to *Launchpad* and should see the current state of your API:

![Deployed API](../images/getting_started-api_is_deployed.png "API is deployed")

Your API will now be in state *Deployed*.

Deployed APIs have a new *Console* button to reach the REST Console. More information about the *Console* can be found in the [Console Guide](../ConsoleGuide.html).

**BETA NOTICE!** Due to our current *Beta stadium*, we still have a few limitations:

- Undeploying an API is currently not available *(coming in the near future)*

**Congratulations! You have your first running API!**

You can now continue with your application and start using your API. More information on how talk to your backend can be found in following guides:

- [REST Guide](../RESTGuide.html)
- [Search Guide](../SearchGuide.html)
- [Console Guide](../ConsoleGuide.html)
