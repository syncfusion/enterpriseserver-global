#Adding new localizations

Create your own culture texts for the Syncfusion Dashboard Server and add it in the application anytime.

To make Syncfusion Dashboard Server use a different culture perform any one method from the below.

##Method 1: Editing localization values

You can directly edit the localization message in that `default.po` file. 

1. Go to the locale folder  `~Installed Location~/Dashboard Server/DashboardServer.Web/locale` and open the `default.po`.

2. You can see `msgid` and `msgstr` words. `msgid` is the source language values (E.g. English) and `msgstr` is localization message. You can put your correspond `msgid` words local culture value to inside double quote of `msgstr`.

    ![Open Google Translator Kit](images/edit-msgstr-values.png)

3. Create you language tag folder inside locale folder (E.g. Folder name `en-ES`) and save edited default.po file into newly created folder named as `messages.po`.

    ![Open Google Translator Kit](images/locale-folder.png)

##Method 2: Using Google Translator Kit

1. Open [Google Translator Kit](https://translate.google.com/toolkit). Click on Upload button.

    ![Open Google Translator Kit](images/add-localization-1.png)

    It will open a new window to upload the existing culture file en-us. Then click on `Add content to translate` link in the screen.
    
    ![Add content to translate](images/add-localization-2.png)
 
2. Select `Upload file` option in the dropdown.

    ![Upload](images/add-localization-3.png)
 
3. Upload [default.po](locale/default.po) file which contains the texts from the Dashboard Server application from `~Installed Location~/Dashboard Server/DashboardServer.Web/locale into google translator`.

4. Make sure that the source language is in English and file name as `messages` as in the below image.

    ![Source Language](images/add-localization-4.png)
    
    Select your desire language in the listed language and click `Next`.
    
5. In the next screen, select `Start Order`, if you need paid service on translation; otherwise select `No, thanks`.

    ![Start Order or No thanks](images/add-localization-5.png)
 
6. The uploaded file will be listed in home page of translator kit. Click on the file to open it and make any corrections in the translation if needed.

    ![Translator Home page](images/add-localization-6.png)
 
7. Click on `Complete` on the right-top corner of the page to complete the translation.

    ![Complete](images/add-localization-7.png)
 
8. Download your translated `messages.po` file.

    ![Download Messages.po](images/add-localization-8.png)
 
9. Create a folder in `~Installed Location~/Dashboard Server/DashboardServer.Web/locale` with {language code}-{country code} and paste the downloaded messages.po file inside the newly created folder.

    For example, if you are translating to Italian, create a folder named `it-it` and paste the messages.po like the below.
    
    `~Installed Location~/Dashboard Server/DashboardServer.Web/locale/it-it/messages.po`
    
    Newly added language will be listed in language list in Dashboard Server after refreshing the page in the Dashboard Server.
    
    ![New Languages](images/add-localization-9.png)