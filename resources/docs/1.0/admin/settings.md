# Settings

Manage AddChat global settings here.

>{primary} To visit `Admin Panel` click on profile icon and then click <larecipe-button type="white">Admin Panel</larecipe-button>

- [General](#General)
- [Widget Config](#Widget-Config)
- [Users Table](#Users-Table)

--- 

<a name="General"></a>
## General Settings

Setup brand identity.


|Setting Name|Type|Description|
|:-|:-|
|Site Name|`alpha-numeric`|Brand/Website name|
|Site Logo|`image:jpg|jpeg|png`|Logo for AddChat widget and admin panel|
|Chat Icon|`image:jpg|jpeg|png`|Logo for the widget icon|
|Footer Text|`alpha-numeric`|Give chat widget your own brand name|
|Footer URL|`alpha-numeric`|Brand website URL|



<a name="Widget-Config"></a>
## Widget Config

These are the AddChat widget main configurations

|Setting Name|Type|Description|
|:-|:-|
|Admin User Id|`integer`|Admin-User-Id **VALUE** from the users table (by default **Admin-User-id** is **1**)|
|Pagination Limit|`integer`|The total number of records to be fetched at a single time (greater the value, greater load)|
|Upload Path|`integer`|The profile pics will be uploaded to this path|
|Assets Path|`integer`|AddChat assets path, AddChat will pick up the fonts, placeholder image and notification sound from this path|

---

>{danger} Please be sure to keep the `Upload Path` writable, or else it'll through an error while uploading images



<a name="Users-Table"></a>
## Users Table

Enter your website `users` table name and it's `user-id` & `email` column names.

|Setting Name|Type|Description|
|:-|:-|
|Users table name|`string`|`users` table name|
|User Id|`string`|`user-id` column name in the users table|
|User Email|`string`|`email` column name in the users table|


>{success} AddChat never modify any data the `users` table and never read the `password` or any other sensitive column except `user id` and `email`

---

> {warning} Please read the guidelines provided below each setting, and follow exactly mentioned, or else it may break down your site.

---

> {primary} After updating settings, please log out and log in again to see the effects.