# Free Website Builder, API. Web Design Automation.
Web Design Automation. Instantly generate a dynamic feature packed website.

## Instant Website, generated via API, example:
![sonet website example](https://user-images.githubusercontent.com/27966874/34644603-892f1e9a-f2ee-11e7-851e-ae856b4130e8.png)

## API fast start - Use your browsers address bar (GET).

1. Register.
http://store.iradek.com/Client/Register

NOTE: Simply use http://127.0.0.1 for a Callback URL and Browser for your application type

2. Click your application "Name" to view your Client App ID and Client App Secret.

3. Generate a security token with this HTTP GET:
http://www.lpk7.com/mvc/oauth?client_id=YOURCLIENTID&scope=Api.Access&redirect_uri=http%3A%2F%2F127.0.0.1&response_type=token

4. Copy the token you generated from the returned string.
NOTE: look for this in the address bar " #token_type=bearer&access_token=THISISTHETOKENYOUGENERATED "

## API fast start - Use your browsers Developer Tools (POST).

5a. Use this HTTP POST to generate your first site:
http://www.lpk7.com/api/SiteObjects/CreateSite?siteName=TYPEANAME&templateName=1024px&isEntireSitePublic=true&requiresRegistration=false&adminUserName=
TYPEAUSERNAME&adminEmail=YOUR@EMAILGOESHERE.COM&adminPassword=TYPEASITEPASSWORD

5b. Add this request header to the post (the spaces are needed):
Authorization: Bearer PASTETHETOKENYOUGENERATEDHERE
 
The API itself is documented here: http://lpk7.com/api/help

## Congrats! 
You just made a complete website, now visit LPK7.com and sort by "Recently Created" to see it and login.

Now that you see how easy the API makes things like complete sites, go ahead and make your own applications using any of the functionality available. You do not have to generate an entire site, you can simply use the functions you need to very quickly create useful applications that leverage the power of your individual SoNET Web Engine install. 

Make image apps, with voting, comments, ratings and more.
Make video apps, surveys, custom form apps, blogging apps and much more. Your imagination is the limit.
