Showoff presentations on OpenShift
==================================

Create an account at http://openshift.redhat.com/

Create a ruby-1.8 application

    rhc app create -a showoff -t ruby-1.8

Then add this repo

    cd showoff 
    git remote add upstream -m master git://github.com/richardfontana/showoff-openshift-quickstart.git
    git pull -s recursive -X theirs upstream master

Add your showoff files
    
Then push the repo upstream

    git push

You can now view your presentation at:

    http://showoff-$yournamespace.rhcloud.com

