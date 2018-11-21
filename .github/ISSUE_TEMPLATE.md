Hello,

I encountered an issue with the following code:
```php
echo Carbon::parse('2018-06-01')->subDay()->month;
```
Carbon version: **PUT HERE YOUR COMPOSER CARBON VERSION**
PHP version: **PUT HERE YOUR PHP VERSION**
<!--
Run the command `composer show nesbot/carbon`
to get "versions"
Use `echo phpversion();`
to get PHP version.

Some bugs may be related to your context, settings,
macros, timezone or language. For that reason, try to
reproduce your bug using the below editor:
https://try-carbon.herokuapp.com/?theme=xcode&export&embed

Use the [Options] button to change the version of Carbon
you wish to use.

When you can reproduce the bug you can use the [Export] 
button. Copy the link of the newly opened tab and paste 
it in this issue, this way we can very easily reproduce 
your bug.
-->

I expected to get:
```
6
```
<!--
Always specify your expectations, each use has their own.
You may want to account for daylight saving time or 
timezones, someone else may not.
-->

But I actually get:
```
5
```
<!--
If you did not succeed to get the same result in
https://try-carbon.herokuapp.com/ then precise the
result you get.
-->

Thanks!
