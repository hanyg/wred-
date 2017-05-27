# wredit-
Dynamics CRM WebResources Editor

The WebResources Editor, wred, provided direct editing of the WebResources of a CRM instance. It is based on the Javascript web editor CodeMirror, https://codemirror.net/, and a number of other libraries, such as jQuery, CRM FetchKit, etc.

This is an early Beta release, and there are more than likely bugs that will need to be resolved over time. I use the tool on a daily basis however, and I have created features based on things I need to do on a daily basis as a CRM developer.

To try out the editor, just download the managed solution and import it into your CRM instance. Then I would typically open a new window or tab and type:

https://org.yoururl.com/WebResources/hg_wredit.html

After initializing, you will see the toolbar and the main window that supports tabs so that you can be editing more than one web resource at a time.

The first thing I typically do is select settings from the toolbar, the small gear icon to the right, and I specify the filters for the web resources I want to see. So, if your publisher is, hg_, I would add hg_ to the list of filters. You can comma separate more than one filter.

You can add filters for entities and attributes as well from the same dialog. You can also specify which web resource types to list, i.e. html, js, css etc. 

Finally, you can specify that you want to Publish All Customizations automatically after Save. The default is not to. There is a button on the toolbar to explicitly request you want to Publish All Customizations.

Once you have selected the settings, you are ready to create or open an existing web resource. Starting from the left, you will see the web resources you can open available in the drop down list box. Select the web resource to open and click on the open file icon immediately to the right of the drop down list. The web resource will be downloaded and opened within the current tab. If there were changes in the current tab, then you are prompted to save the contents as a local file or as a web resource. To the left of the drop down list is a refresh icon that reloads the list of web resources available, based on the current settings.

The next group of icons provide the following:
- open local file or simply drag the file onto the current tab
- create a new web resource
- save the local file or web resource

The next group of icons provide the following:
- open the search and replace dialog
- jump to line
- undo the last change
- redo the last change
- format the current tab
- format the current selection
- cycle through the font size, increases until max size and starts over
- show rulers on the current tab
- open the save bookmarks, to see and jump to a bookmarked section of the file
- fold all blocks, e.g. if blocks, for blocks, etc
- unfold all blocks
- toggle comments of the current selection
- toggle display of the line numbers on the left
- toggle display of leading and trailing whitespace on each line of the current tab
- show a split screen of the same file and a preview window. allows editing a portion of a large file in the smaller window
- preview the web resource
- show differences and merge changes of the current web resource. compares what is being edited locally with what has been saved and published on the server
- show info on the current web resource being edited
- create a new web resource - shown on save automatically when editing a new file that is being saved for the first time as a web resource
- delete the web resource
- publish all customizations

The next group of icons provide the following:
- select VI mode
- select normal mode
- open the XSLT dialog, select the XML to transform and the XSLT file to use for the transformation
- open the FetchXML dialog - execute the FetchXML on the current tab or execute the selected FetchXML text. You can copy the FetchXML as a Javascript block to the clipboard. Useful when creating FetchXML calls

The next dropdown list box provides some common code snippets for FetchXML and basic HTML. Just select the snippet and click the open snippet icon immediately to the right of the code snippets drop down list box.

The remaining icons the settings, the about dialog and the help toggle

There are various Hot Keys you can use and they are described in the Help.

This is the very first release and it is freely availble. Please pass on any comments or suggestions you may have for improving the editor.

Hany Greiss
May 2017
