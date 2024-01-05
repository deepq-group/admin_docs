# User Accounts

### User List

Users that belong to your organization is listed here, the maximum number of active users is shown at the top of the list.&#x20;

{% hint style="warning" %}
&#x20;If the number of active users reaches the limit, you may not add another user.
{% endhint %}

![user account list](../../.gitbook/assets/User\_List.png)

### Add New User

Adding a new user requires the admin to set the following information：

* Account login email
* Password (later can be changed by the user)
* Display Name
* Product permission
* Two-Factor Authentication on/off

{% hint style="warning" %}
If the account uses a non-existent email, the user will fail to receive  two-factor authentication code
{% endhint %}

<figure><img src="../../.gitbook/assets/Add_New_User.png" alt=""><figcaption></figcaption></figure>

### Product permission <a href="#module-permission" id="module-permission"></a>

DeepQ AI Platform module & function permission is listed in the table below. Set product permission according to the functions needed by the user.

<table><thead><tr><th width="300">Functions</th><th width="126">DeepCap</th><th width="116">AI Training</th></tr></thead><tbody><tr><td>Upload/manage dataset</td><td>V</td><td>V</td></tr><tr><td>Create/manage annotation project</td><td>V</td><td></td></tr><tr><td>Annotate/review image(s)</td><td>V</td><td></td></tr><tr><td>Create/manage training tasks</td><td></td><td>V</td></tr><tr><td>Evaluate training tasks</td><td></td><td>V</td></tr></tbody></table>

###

###

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

