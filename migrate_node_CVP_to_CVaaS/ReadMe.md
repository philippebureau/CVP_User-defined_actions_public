# Migrate to CVaaS

This script will migrage the selected node to a CVaaS instance.

The node will start streaming telemetry to the CVaaS instance which will 

To make this script available in CVP Change Controls:

* log into CVP shell as root
* copy the script and YAML file to a local folder 
    * you can copy directly from github using `wget https://raw.githubusercontent.com/philippebureau/CVP_User-defined_actions_public/main/migrate_node_CVP_to_CVaaS/Migrate_to_CVaaS.py https://raw.githubusercontent.com/philippebureau/CVP_User-defined_actions_public/main/migrate_node_CVP_to_CVaaS/cfg_Migrate_to_CVaaS.yml`
* install using script-util 
    * ex : `/cvpi/tools/script-util upload -path Migrate_to_CVaaS.py -config cfg_Migrate_to_CVaaS.yml`
* validate with command `/cvpi/tools/script-util list`