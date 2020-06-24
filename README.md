# Tesla Shortcuts

This is a list of shortcuts I've created that I'm sharing with everyone.

## Core Shortcuts

| Name & Source | iCloud | Description | Requires | Speakable |
| ------------- | :----: | ----------- | :-------------: | :-------: |
| Authenticate with Tesla | [Get](https://www.icloud.com/shortcuts/d2e1166c37b843a1a25d826f770af284) | Authenticate with Tesla using your email & password | Tesla account email & password; Tesla Client ID & Client Secret | No |
| Get Vehicle ID | [Get](https://www.icloud.com/shortcuts/9cc61c0c795c4f85a71fe9977fd12b61) | Gets your Vehicle ID based on the name | Access token & name of the vehicle. Passed in Share Sheet, values on new lines | No |
| Tesla files In shortcut folder | [Get](https://www.icloud.com/shortcuts/62309c5754a84516a04f0a93cd22174a) | Creates your credentials file and an empty access file | Tesla account email & password; Tesla Client ID & Client Secret | No |
| Open Frunk | [Get](https://www.icloud.com/shortcuts/3af21c1fe8c44e99adc6fa2110e96f48) | Opens the frunk of your Tesla | Access token & Vehicle ID. Passed in Share Sheet, values on new lines | No |
| Wake Up Tesla | [Get](https://www.icloud.com/shortcuts/5b19450f575b4a12b9ab1699157d31e3) | Attempts to wake up your Tesla | Access token & Vehicle ID. Passed in Share Sheet, values on new lines | No |
| Open/Unlock Chargeport| [Get](https://www.icloud.com/shortcuts/d5ae5e748e6f4210bc457735632ed742) | Opens the charge flap or unlocks the charge cable | Access token & Vehicle ID. Passed in Share Sheet, values on new lines | No |

## Speakable Shortcuts

| Name & Source | iCloud | Description | Requires | Speakable |
| ------------- | :----: | ----------- | :-------------: | :-------: |
| Open Frunk | [Get](https://www.icloud.com/shortcuts/a9e22b3fea344b27a0779edc56489c30) | Opening your Frunk | Requires shortcuts: Authenticate with Tesla, Get Vehicle ID, Wake Up Tesla, Open Frunk | Yes |
| Initiate Software Update | [Get](https://www.icloud.com/shortcuts/c8d89f5181bd47beae0088c367c1e862) | Using Siri to start the software update | Requires shortcuts: Authenticate with Tesla, Get Vehicle ID, Wake Up Tesla | Yes |
| Open Charge Port | [Get](https://www.icloud.com/shortcuts/2d37746372c64a8abeb6f3d6895f442b) | Use Siri or widget to open/unlock the charge port | Requires shortcuts: Authenticate with Tesla, Get Vehicle ID, Wake Up Tesla, Open/Unlock Chargeport | Yes |

## iCloud Authentication file

You will need to create a .json file in your iCloud drive
| Item  |   value   |
|:-----------:|:------------:|
| iCloud folder: | /Shortcuts/ |
| File name: | tesla_credentials.json |

### File Structure

```javascript
{
    "email": "me@tesla.com",
    "password": "password",
    "secret": "aaaaaiwillfindtheclientsecretonlinezzzz",
    "client_id": "aaaaaiwillfindtheclientidonlinezzzzz"
}
```

## Open to contributions

If you like my stuff and want to support by joining the tesla comunity 
or signing up to Green energy company (UK only) my links are bellow:
Tesla referal - <https://ts.la/john72161>
Ocotpus Energy - <https://share.octopus.energy/alive-owl-500>
