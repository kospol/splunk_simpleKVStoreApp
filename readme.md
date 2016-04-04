# Simple Splunk KV Store app
> Kostas Polychronis

A very simple Splunk app showing how to interact with the KV Store.
It is based on the tutorial from the [Splunk documentation](http://dev.splunk.com/view/SP-CAAAEZT). The concept of the app is to allow the Splunk app users to add and remove Customer information that includes several fields.

### Installation

If you want to install the app to your local Splunk instance you can do so in two different ways:

>Using the Splunk Web interface (easy)

* Click the `Manage Apps` blue icon at the left side of the Splunk Web Interface
*  Click the `Install app from file`
*  Select the `spl` file and click upload
*  Restart Splunk

>Using the command line (moderate)

```sh
$ mv Downloads/app.spl $SPLUNK_HOME/etc/apps
$ cd $SPLUNK_HOME/etc/apps
$ gunzip -c app.spl | tar xopf -
$ splunk restart
```

License
----

MIT