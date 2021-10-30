# <p align="center">Vote-System</p>
<p align="center">A voting system to handle your bot vote's from top.gg with MONGO DB.</p>

### How to Use?
<ul>
  <li>Fork this repo (https://github.com/Mitsuya-Bot/System-Vote/)</li>
  <li>Run <i>npm install</i> To install the required modules</li>
  <li>Head to the <a href="https://github.com/Mitsuya-Bot/System-Vote/blob/main/config.json">config.json</a> File and change as such:</li>
</ul>

```yaml
{
      mongo -> Your MONGO Database URL
      dbl_secret --> Top.gg Authorization (Found here https://top.gg/bot/YOUR-BOT-ID/webhooks
      bot_token --> Your bot's token (found here https://discord.com/developers/applications)
      bot_name --> Your discord bot's name
      bot_logo --> Bot logo's URL
      port --> Website's Port (default: 5000)
}
```
-----

### <p align="center">Webhooks</p>
Let'say the webhook you copied is: https://discord.com/api/webhooks/827092347325644200/EJWOSlDFNRiux_XBG4Fbj0wJyNTM4riPDyO0Qe6zAwr1SSQZpfhv3Bzbfa9AQkDqlImF

 ```yaml
{
       webhook_id --> 827092347325644200
       webhook_url --> EJWOSlDFNRiux_XBG4Fbj0wJyNTM4riPDyO0Qe6zAwr1SSQZpfhv3Bzbfa9AQkDqlImF 
}
```
<br>
<p align="center">Make sure the <i>dbl_secret</i> Is the same authorization in top.gg or It will not work.</p>
<p align="center">Make sure the Webhook URL on top.gg is the website-name/dblwebhook or It will not work.</p>
<br>
<p align="center">Any questions? DM me on <a href="https://discord.com/users/447411230098063362">Discord</a>.</p>
