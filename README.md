DMWG-2HDM-whitepaper
====

This is a repository for the DMWG Whitepaper on the recent 2HDM effort. 

#How to edit

This whitepaper is being written in an experimental collaborative environment. 
You can edit it on:
   * Sharelatex (ask caterina.doglioni@cern.ch for access rights, 
   this option is limited to 10 co-authors at a time)
   * Gitlab (ask lhc-dmwg-admin@cern.ch for access rights)
   * Github (ask caterina.doglioni@cern.ch for access rights)

It is therefore *essential* that you update the repository before and after editing. 

To update in gitlab/github: 
   * use 'git pull' command to download the current snapshot
   * use 'git add' command to add the files with your changes for upload
   * use 'git commit -m [commit message]' to commit your changes
   * use 'git push' to push (upload) your changes to the remote repository

To update in sharelatex:
   * click on the right-hand side column "git"
   * click on "pull changes" to update ShareLatex 
   to the most recent version of the whitepaper in git. Do this every time you
   start working
   * click on "push changes" to update git with your ShareLatex work

Rule of thumb: commit early, commit often. You can always refine your text in 
a later iteration. 

#Troubleshooting

*Gitlab/github*: someone may have made changes in the repository while you were working. 
In that case, your 'push' command will be rejected. In most cases, you will just need
to do 'git pull' as others will not have edited the same file as you. If you have conflicts, 
git will help you take care of them by creating a file where the differences/conflicts
are highlighted clearly. 

*Sharelatex*: if someone has committed to git while you're editing ShareLatex, 
copy all your work to text files and refresh the page, then merge the changes. 
(Yes, this is the price to pay if you prefer to work with an online latex editor). 
