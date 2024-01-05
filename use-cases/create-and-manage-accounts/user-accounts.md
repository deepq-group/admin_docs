# User Accounts

### Users

The administrator can perform the following tasks related to user accounts:

* create new account
* edit account permission--module authorization & expiry date
* reset password
* suspend/delete account

![user account list](../../.gitbook/assets/User\_List.png)

### Add New User

Adding a new user requires the admin to set the following information：

* Account login email
* Password (later can be changed by the user)
* Display Name
* Product permission
* Two-Factor Authentication on/off

<figure><img src="../../.gitbook/assets/Add_New_User.png" alt=""><figcaption></figcaption></figure>

### Manage User Account

The administrator can perform the following operations:

* Edit account permission--module authorization, expiry date & two-factor authorization on/off
* Reset user password (in case of user forgot their password)
* Suspend account (can be unsuspended)
* Delete account

{% hint style="warning" %}
Deleting an user account will remove all assets that belong to the user (Uploaded dataset, created annotation files, annotation projects, training tasks, models and inference results.). All assets cannot the saved after the account deletion.

Please make sure that the user is fully aware of the changes you plan to make, and properly backup their contents.
{% endhint %}



![edit account permission/ set expiry date](../../.gitbook/assets/Manage\_User.png)

