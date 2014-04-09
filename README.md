# df_git cookbook
this is supposed to install and put git on the system. There really isn't much to this one that is different than a apt-get install git
# Requirements
* NOTE1: This cookbook (along with almost all dataFundamentals cookbooks) requires that you have local binaries to install other programs. If you are looking to use these as is, download the df_base cookbook to pull all the repositories. If you are looking to only pull certain binaries, please select the install flavor you would like in the attributes. The only one currently available is for Maven
*NOTE2: Please look at the .kitchen.yml file and adjust the synced folder from what we have run or it won't work


# Attributes
There are no attributes currently
# Recipes
* default- yes, it's a one resource recipe to install it. Deal with it.
This needs an additional git configuration thing going on.

# Author

Author:: Jeff Carapetyan (<YOUR_EMAIL>)
