Via Verde App for Splunk

#Instalation

##Distributed envirioment
Install App in the Search heads

#Configuring Splunk
##Using GUI
Create a new index to hold Via Verde (e.g viaverde) data or choose an existing one
Upload the file or configure a new monitor input
Select pinsafe as sourcetype
Select your destination index

#Configuring Via Verde App
##Using GUI
Open the Via Verde App
In Splunk Settings > Advanced Search > Search Macros
Edit the via_verde_index and replace "viaverde" with index name you created to hold you data. 

#Support
via_verde_app is community supported (http://answers.splunk.com)

#Feedback
Please send your feedback to feedback+viaverdeapp [@] devbusters.com