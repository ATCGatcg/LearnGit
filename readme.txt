git branch dev  //creating a branch named dev
git checkout dev   //switch to the branch 'dev'
git checkout -b dev  //equel to the two commands above this one,create and switch
git branch    //show the current branch
<<<<<<< HEAD
creating a new branch is quick and simple.
=======
creating a new branch is quick and simple.
>>>>>>> feature1
git merge defaultly used fast forward partten to merge the branches.
we can use --no-ff option to forbid the fast forward partten.
