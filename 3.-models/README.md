# 3. Models

Here the admin can view the list of all deployable models stored on the DeepQ AI platform. Completing a training task does not automatically make the model deployable, the adminsitrator will have to decide which model can be deployed. Clicking on the "**IMPORT MODEL**" button brings you to the model list

![Deployable model list of DeepQ AI platform](../.gitbook/assets/Deeploy-adm-3-0-1.png)



The list here shows all the models trained in the AI Training module. Any "finished" or "stopped" training task will result in a model that can be imported and deployed.

Each row contains the folloing information of a model：

* Model name：The name of the training task given in AI Training module
* Type：Classification, Detection or Segmentation
* Owner：The owner of the training task/model
* Imported date：The date when the model is imported as a deployable model
* Image：Some thumbnails of the training data images

Users can search for any specific model by going through the list or search by keywords. Training tasks that are either "Waiting", "Running" or aborted too early by the owner (no training curve) cannot be found in this list. Models that already have been imported will be greyed out and should be found in the previous model list.

Selecting one or more models then clicking on "**IMPORT**" will complete the process and make the models deployable.
