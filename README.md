A Python library to control [foobar2000](http://foobar2000.org) media player via [foo_httpcontrol](https://bitbucket.org/oblikoamorale/foo_httpcontrol) plugin (by oblikoamorale)

Currently only some of foo_httpcontrol functions are implemented:
* Some basic playback commands
* Fetching track info and  album art from player
* Fetching playlists

foobar2000 Setup and Requirements:

* foobar2000 version >= 1.1  
* Install foo_httpcontrol [plugin](https://bitbucket.org/oblikoamorale/foo_httpcontrol/downloads/) (by oblikoamorale) (tested on version 0.97.17)  
* Import foo_httpcontrol template from this project  

Template Installation:

Copy `template/` directory content from this project into `foo_httpcontrol_data/` directory of foobar2000.      
foobar2000 standard installation: usually goes into `%APPDATA%\foobar2000\foo_httpcontrol_data\pyfoobar2k`    
foobar2000 portable installation: usually goes into `<foobar2000_root_dir>\foo_httpcontrol_data\pyfoobar2k`    
A successful installation of the template can be verified at `http://<player_ip_address>:8888/pyfoobar2k`    


