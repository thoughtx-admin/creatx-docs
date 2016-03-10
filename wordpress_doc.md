## Wordpress integration for Creat(x)

Follow the following steps to allow Creat(x) to publish to your Wordpress.org website

### Installation of plugins
You need to install the following plugins on your Wordpress.org website.
* [JSON Basic Authentication](https://github.com/WP-API/Basic-Auth)

  Installation instructions:

  1. Download the .zip from [here](https://github.com/WP-API/Basic-Auth/archive/master.zip)
  2. Extract the zip into your wordpress plugins directory (`<your wordpress installation directory>/wp-content/plugins/`).
  3. Go to your Wordpress.com admin --> Plugins --> Installed Plugins and activate JSON Basic Authentication

* [WP Rest Api V2](http://v2.wp-api.org/)

  You may install this plugin from the wordpress plugins directory. To do so, go to your Wordpress.com admin --> Plugins --> Add New and search for **WP Rest Api V2**

  Manual Installation instructions:

  1. Download the .zip from [here]
  2. Extract the zip. You should get a folder called `rest-api`
  3. Copy that folder to your wordpress plugins directory (`<your wordpress installation directory>/wp-content/plugins/`)

  After installing, go to your Wordpress.com admin --> Plugins --> Installed Pugins and activate WP Rest Api V2.

### Publishing from Creat(x)
After saving a story on [creatx.io](http://staging2.creatx.io), you can click on **Publish** and it will publish to your Wordpress.org website.

When you click **Publish** for the first time, you will have to enter your Wordpress.com username and password, as well as your Wordpress.com url.
