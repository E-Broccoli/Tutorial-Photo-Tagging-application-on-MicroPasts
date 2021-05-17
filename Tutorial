# **TUTORIAL - CREATING A PHOTO-TAGGING APPLICATION ON MICROPASTS**
## **MSc Heritage, HERPP05 Digital Heritage and Museums**

### Authors: Elisa Broccoli, Chiara Bonacchi e Marta Krzyzanska

##**INTRODUCTION**

###**Pybossa technology for crowdsourcing**

In this tutorial, we will consider how to enable the crowdsourcing of reasearch data using the Pybossa framework (http://pybossa.com), a technology to collect, enrich and analyse data via small tasks submitted by relatively large groups of people, over the Internet. Pybossa was developed by SciFabric under the technical lead of Daniel Lombraña González (http://github.com/pybossa/pybossa).

To power the crowdsourcing of research data through Pybossa, there are three possible routes that can be followed. The first is to install your own Pybossa server and develop a bespoke crowdsourcing website, following the documentation available here:
https://docs.pybossa.com/installation/gettingstarted/. This is the route chosen by the MicroPasts team and also by the British Library, whose LibCrowds initiative is powered by Pybossa (https://www.libcrowds.com). The second route is to create an account in the Pybossa server, and then a project that runs on https://scifabric.com/crowdcrafting/, by following these steps:
https://docs.pybossa.com/build/overview/. The third route is that of collaborating with a themed crowdsourcing website built using the Pybossa framework, such as MicroPasts (http://crowdsourced.micropasts.org). This tutorial will focus on this third and last route.

###**The MicroPasts crowdsourcing platform**

The MicroPasts crowdsourcing platform was built as part of the MicroPasts project, funded by the UK Arts and Humanities Research Council and developed as a collaboration between the UCL Institute of Archaeology and the British Museum. The platform is now maintained by the main MicroPasts team (Andy Bevan, Daniel Pett, Chiara Bonacchi, Jennifer Wexler), together with other institutions, researchers and heritage professionals internationally.

The MicroPasts crowdsourcing platform runs on the Pybossa framework developed by SciFabric. Templates have been created so far by the project team and by collaborators, by elaborating on and modifying some of the templates already available in Pybossa. The MicroPasts templates are modular, this means that they are adaptable to the needs of different collections and institutions.
So far the kinds of tasks that are supported by the MicroPasts templates are: transcription of structured and unstructured text and of sound; geo-referencing of find spots; classification of photographic material; video-tagging; and 3D photo-masking.


###**Phototagging in MicroPasts**

In this tutorial you will learn the technology and workflow behind cloning and adapting an existing crowdsourcing template in MicroPasts, through the example of the Phototagging template, which was created in 2020 for the Scottish Political Archive.

The Phototagging application loads a photo from the 2014 Referendum Collection Flickr feed of the Scottish Political Archive, and invite help from participants online to tag any people, places, and objects that they identify. They can use the tags provided first, and then add their own tags too. If in the picture there are any signs, the app invites participants to transcribe their content in the Comments box. 


## **PART 1 - CLONING AND ADAPTING A PHOTO-TAGGING APPLICATION ON GITHUB**

![title](https://github.githubassets.com/images/modules/site/git-guides/git-guides.png)

###**1. Setting-up GitHub** 

The crowdsourcing application you will develop will be accessible via the MicroPasts crowdsourcing website (http://crowdsourced.micropasts.org). The code will be created and made publicly available via the MicroPasts GitHub account (https://github.com/MicroPasts). GitHub is a platform for collaborative coding which enables version control. This means that all the changes that are made to the code as you go along in your coding practices are tracked; it also means you can ask collaborators for help to solve issues and clone and modify copies of the repositories that already exist on a project account and are publicly shared.

The first thing to do, in order to clone and modify a phototagging application via MicroPasts, is then to set-up a GitHub account. To do this, go to https://github.com, sign-up for an account and log into it. To code using Git, you can either run commands directly via your terminal, or use a desktop version of GitHub. In this tutorial we will choose the second route, so you will need to download and install the version suitable for you, macOS or Windows, of GitHub Desktop available at https://desktop.github.com/.


###**2. Clone an existing phototagging application**

Once you have installed GitHub Desktop, you are ready to clone the code of an existing phototagging application, so that you can then modify it and adapt it for the phototagging of your photographs collection. 

To clone the code of an existing application, go to the MicroPasts project page on GitHub https://github.com/MicroPasts. Here, you will find all the code that powers MicroPasts, shared in different and dedicated repositories. You will need to find the repository (repo) that contains the code of a recent application similar to the one you would like to develop. 

For this tutorial you will find the code of the Phototagging application on Dr Elisa Broccoli GitHub. Go to her page on GitHub https://github.com/E-Broccoli and search for the repo “SPA_PhotoTagging”, which contains the code for an application to phototagging the photographs from the 2014 Referendum Collection of the Scottish Political Archive, in Stirling.

Once you have found the “SPA_PhotoTagging” repo, click on it so you visualize the webpage https://github.com/E-Broccoli/SPA_PhotoTagging. Then you will need to click on the green button
‘Code’ and choose the option ‘Open with GitHub Desktop’. When prompted, click on ‘Clone’ and the repo will be saved locally on your computer in a folder called ‘GitHub’ (unless you have previously changed the default name).


###**3. Create a repo for your new application**

Once you have cloned a copy of the phototagging application ‘SPA_Phototagging, you will need to create a repo for the new application you are developing. The subsequent step, in fact, will be to copy paste locally, on your computer, all the files contained in the ‘SPA_Phototagging’ repo into the new repo you have created and make the necessary changes. To create a new repo for your application, which we will call ‘Referendum2014’, you need to go to your GitHub page, click on the ‘+’ button on the top right side of the page and choose the option ‘New Repository’.

When prompted, choose a name for your repository (‘Referendum2014’), leave the default viewing option set to ‘Public’, tick the option ‘Initialise this repository with: Add a README file’, and then click on
‘Create repository’. Ticking the ‘Initialise this repository with: Add a README file’ option will allow you to create a repo that already has a so-called ‘README’ file inside, where you will write the metadata that explains what your repo is, who developed it and how, under what licenses and for what uses.
Once you have done this, click on ‘Code’ and choose the ‘Open with GitHub Desktop’ option.
When prompted, click on ‘Clone’ and the repo will be saved locally on your computer in a folder called ‘GitHub’ (unless you changed the default name).


###**4. Copy and modify files in your new repo**

Now you should have two repos visible on your GitHub Desktop: 'SPA_Phototagging', containing the files that power a phototagging application created for the 2014 Referendum Collection of the SPA, and "Referendum2014" which is your new repo that at present contains only a README file with the title of your repo.
What you want to do is to go to the folder where the repos are stored locally. So, in your Finder, search for a folder called 'GitHub'. The 'GitHub' folder should contain two folders called, respectively 'SPA_Phototagging' and 'Referendum2014' (your two repos). Now copy all the files contained in 'SPA_Phototagging' except for the README and paste them inside the 'Referendum2014' folder. Now if you go back to your GitHub Desktop and click on your 'Referendum2014' repo, you should see that GitHub has tracked the additions and changes you have made. This is what version control means in practice: tracking changes made by developers, so they can be reviewed.

Now that you have the files that power a phototagging application, you will need to adapt them so that they suit the phototagging of your own photographs collection. 
To know how to do this, you first need to know what files are inside the repo and what they are useful for. The 'Referendum2014' repo contains the following files: 'requirement.txt' (requirements to run the application), 'template.html' (this is useful to enable the view for every task and to deal with the data of the answers), 'tutorial.html' (this is the file to show the tutorial that guides users in the completion of phototagging tasks), 'README.md' (a markdown file that contains metadata about the repo), 'long_description.md' (the description of the application that will appear on the MicroPasts crowdsourcing website), 'project.json'(it contains the setup metadata) and 'AUTHORS.md'(a markdown file that contains metadata about the authors of the app).

You will need to modify the following files: 

**(1) README.md**: Open the README file inside the 'SPA_Phototagging', copy all the text, and paste it in the README file of the 'Referendum2014' folder under the text that is already there . Save and close. 

**(2) AUTHORS.md**: Change the name and email address to your name and email address. Save and close.

**(3) Long_description.md**: update the text to suit the photographic collection you are dealing with. You need to describe your application, its aims, and what are the tasks of the participants. You can also include the URL of the logos of the funded partners involved, so that they are displayed. For this tutorial, it is not necessary to change these elements, but we ask you to add a curiosity about the Scottish Political Archive. Before "This project is on behalf of", tape "Did you know that?" and write what you have found about this collection or the archive. Save and close.

**(4) Project.json**: Change "name" and tape "Referendum2014 Phototagging"; change "short_name" and tape "Ref2014"; and change "description" and "question"(for this example it is not necessary). Save and close.

**(5) Template.html**: This file allows users to view the interface of the phototagging application, so they can submit their answers. To edit this file you need to use an external editor like Atom https://atom.io/. Once you have downloaded the editor, you need to right click the template file in GitHubDesktop and click 'Open in external editor'. Now, substitute ‘Spa2014tag’ with ‘Ref2014' every time it features (CTRL+F help you to find a word quickly through the code). Save and close.

**(6) Tutorial.html**: Adapt the existing tutorial to your app or delete and write a new one using the external editor (for this example it is not necessary). Save and close.

Now go to your GitHub Desktop and click on your 'Referendum2014' repo. All the changes you made should be showed. Now you will need to update the online version of the repo with all the additions and changes you made to your local version of the repo; in Git this is called 'committing' changes. To commit your changes, just write a Summary and a Description describing the changes and then click on the ‘Commit to main’ button at the bottom of the page. Then press 'Sync' (in some versions of GitHub this is 'Push commits to the origin remote' 'Push Origin') at the top of the page. The online version of your repo should now be exactly the same as the local copy of 'Referendum2014' that you have locally on your computer, in the 'GitHub' folder.


##**PART 2 - SETTING UP A NEW PROJECT ON MICROPASTS**

![title](https://pbs.twimg.com/media/El7tVbdXgAou9Z4?format=jpg&name=large)

###**1. Setting-up a MicroPasts Account**

To create a crowdsourcing project you need to be a registered user on the https://crowdsourced.micropasts.org site (to register go here: https://crowdsourced.micropasts.org/account/register). You must then sign in to the site and find out your personal API key which is available from user dropdown menu on the top right of the page ('My Profile').

###**2. Create a new project**

You can create a new project from scratch or more likely modify an existing template of a project and add this to the site as a new project. Most of the time it is easiest to copy the relevant files from an existing project (on MicroPasts or Crowdcrafting for instance), modify them a bit to get the style and content you want, then use them to create a new project.

To create a blank project, making sure you are logged in, and then go to 
https://crowdsourced.micropasts.org/project/new
Then in the resulting dialog, we add the 'Name' of the project such as "Referendum2014", a 'short name' for the project (that must have no spaces, as it will go in the project URL, for example "Ref2014" or if this i already taken, some other short name that has no spaces in it), and a longer description (which is the project abstract or description and which can be written in plain text or with markdown elements to add institutional logos, etc.). For this example use the items created before for the Project.json file in your GitHub repo, just copy and paste. Once you have added these, click Create.

This creates a new project on the MicroPasts site and the resulting dialog allows you to further modify it, for example adding a project avatar (i.e. a picture/logo), assign it to an existing category of project (only admin users can create new categories however), and then Save the Changes. You should then be taken to a new page where you can see your avatar, project name and description (you can always go back and edit the above details at: https://crowdsourced.micropasts.org/project/Ref2014/update)

###**3. Create a Task Presenter**

You now need to create the Task Presenter which is the page that loads and shows a new task to the end user. This can be found from the left-hand menu Tasks-Task Presenter (or directly https://crowdsourced.micropasts.org/project/Ref2014/tasks/taskpresentereditor). In fact, you always start with a template, even if just a very basic one. For this example, click on 'Basic' and in the resulting dialog, you will see the html and javascript that would create the page the users sees on starting a task. In our current example, we will simply delete everything in the current html box and paste in everything in template.html file in your GitHub repo. Then click 'Update'.

You will probably need to go back to fine-tune the html of the Task Presenter later and can always do so by going back to the Task Presenter page at
https://crowdsourced.micropasts.org/project/Ref2014/tasks/taskpresentereditor. 
However, for now the above should allow you to create some dummy tasks and check the overall functioning of the project. 

###**4. Import Tasks**

Now you can go to your project: https://crowdsourced.micropasts.org/project/Ref2014 and then to 'Import Tasks - Import'. This app loads photos from the 2014 Referendum Collection Flickr feed of the Scottish Political Archive. To load photos of a Flickr album you need to click on 'Flickr, Use images from a Flickr set - Import data' and tape the ID of it in the box indicated. 
You find the ID of a Flickr album in the url bar when you click on it.
For example, for this album https://www.flickr.com/photos/scottishpoliticalarchive/albums/72157716578739916 the ID number is 72157716578739916. Click 'Import'.


###**5. Test and Publish your project**

Now it should load the task. And when you click on 'TestIt!' top right it should load the way the user would see the task. You then tinker with the Task Presenter until you are happy with it and the other set-up. Then delete the example task and load the real ones, and then 'Publish' the project. If you wish you can also ask an admin user to move it into the 'Featured Projects' section of the MicroPasts site to increase its prominence.
