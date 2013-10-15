OdinEditor
==========

An Eclipse Update site that offers an IDE for the Odin scripting language (demo project):

INSTALLATION:
1)	Install Eclipse, preferable 4.2 Classic edition
2)	Help -> Install new software
3)	Add update site, location: http://maartje.github.io/OdinEditor, name: Odin
4)	You have to restart Eclipse and modify the eclipse.ini (add/change options -Xss8m, -server, -Xms256m, -Xmx1024m
    (Ignore ‘annoying’ warning about –server option missing).

GETTING STARTED:
1) Follow the installation instructions above 
2) Start a (mini)Odin project using the wizard: File -> New Project -> Nipo Software -> Odin Project
- OdinDemo/odindemo.q shows an example questionnaire. The questionnaire has syntactic and semantic editor services
- OdinDemo/out/index.html renders this questionnaire in the browser. The rendered questionnaire has validation and navigation
