#Editing the localization messages

Localized message files can be edited and changed for any specific texts.

> Read [How to add new localization](/Dashboard Server/How-to-add-new-localizations.md) to know how to upload `default.po` and translate to a desired language before editing it.

##Method 1: Editing localization values

You can directly edit the localization message in that `messages.po` file. 

1. Go to the locale folder  `~Installed Location~/Dashboard Server/DashboardServer.Web/locale` and open the `messages.po` file inside that language tag folder.

2. You can see `msgid` and `msgstr` words. `msgid` is the source language values (E.g. English) and `msgstr` is converted localization message. You can edit `msgstr` value  for your text and save it.

Refresh the page in the Dashboard Server to see the updated messages.

##Method 2: Using Google Translator kit

1. After converting the localized messages, Open the file and modify the words and sentences which you want to change in the window.

    ![Open exiting file](images/edit-localization-1.png)
    
    ![Edit existing file](images/edit-localization-1.png)

2. Click on `Complete` on the right-top corner of the page to complete the translation.

    ![Complete](images/edit-localization-3.png)
 
3. Download your translated `messages.po` file. And replace the original messages.po file with the downloaded file.

Refresh the page in the Dashboard Server to see the updated messages.
