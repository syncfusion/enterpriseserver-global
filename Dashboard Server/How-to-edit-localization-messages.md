#Editing the localization messages

Localized message files can be edited and changed for any specific texts.

> Read [How to add new localization](How-to-add-new-localizations.md) to know how to upload `default.po` and translate to a desired language before editing it.

##Method 1: Editing localization values

You can directly edit the localization message in that `messages.po` file. 

1. Go to the locale folder  `~Installed Location~/Dashboard Server/DashboardServer.Web/locale` and open the `messages.po` file inside the corresponding language tag folder.

2. Find the `msgid` for which you want to edit the localization message, and replace the localization message inside the double quote of `msgstr` field as below

    ![Edit msgstr value](images/edit-msgstr-values.png)

Localization will be updated on next page refresh.

##Method 2: Using Google Translator kit

1. After converting the localized messages, Open the file and modify the words and sentences which you want to change in the window.

    ![Open exiting file](images/edit-localization-1.png)
    
    ![Edit existing file](images/edit-localization-1.png)

2. Click on `Complete` on the right-top corner of the page to complete the translation.

    ![Complete](images/edit-localization-3.png)
 
3. Download your translated `messages.po` file. And replace the original messages.po file with the downloaded file.

Refresh the page in the Dashboard Server to see the updated messages.
