   73  git checkout -b Ken_Branch4
   74  rm Text.py
   75  git add Readme.txt
   76  git rm Test.py
   77  git commit -m "Updated Readme.txt and removed Test.py"
   78  git push -u origin Ken_Branch4
   79  git checkout main
   80  git add .
   81  git add Profile.txt Education.txt Background.txt Readme.txt Test.py
   82  git commit -m "Updated Profile.txt Education.txt Background.txt Readme.txt Test.py"
   83  git push -u origin main
   84  git branch
   85  git branch main
   86  git add .
   87  git branch
   88  git checkout main1
   89  git checkout -b main
   90  git branch -u main
   91  git branch -u origin
   92  git branch -u origin/main
   93  git checkout Ken_Branch1
   94  git checkout main1
   95  git checkout -b main
   96  git checkout main1
   97  git checkout main
   98  git checkout -b Baldomar_IT120_Act1
   99  git add .
  100  git add Profile.txt Education.txt Backgroun.txt Readme.txt Test.py
  101  git add Profile.txt Education.txt Background.txt Readme.txt Test.py
  102  git commit -m "Updated Profile.txt Education.txt Backgroun.txt Readme.txt Test.py"
  103  git commit -m "Updated Profile.txt"
  104  git push -u origin Baldomar_IT120_Act1
  105  git add .
  106  nano Profile.txt
  107  nano Education.txt
  108  nano Background.txt
  109  nano Readme.txt
  110  git add Profile.txt Education.txt Background.txt Readme.txt Test.py
  111  git commit -m "Updated Profile.txt Education.txt Background.txt Readme.txt Test.py"
  112  git push -u origin Baldomar_It120_Act1
  113  git push -u origin Baldomar_IT120_Act1
  114  git checkout main
  115  git checkout Ken_Branch1
  116  nano Profile.txt
  117  git add Profile.txt
  118  git commit -m "Updated Profile.txt"
  119  git push -u origin Ken_Branch1
  120  git checkout main
  121  git checkout Ken_Branch2
  122  nano Education.txt
  123  git add Education.txt
  124  git commit -m "Updated Education.txt"
  125  git push -u origin Ken_Branch2
  126  git checkout main
  127  git checkout Ken_Branch3
  128  nano Background.txt
  129  git add Background.txt
  130  git commit -m "Updated Background.txt"
  131  git push -u origin Ken_Branch3
  132  git checkout main
  133  git checkout Ken_Branch4
  134  nano Readme.txt
  135  nano Readme.txt
  136  git branch -d Readme.txt
  137  git rm Readme.txt
  138  git commit -m "Deleted Readme.txt"
  139  git push -u origin Ken_Branch4
  140  git checkout main
  141  git commit -m "Updated Readme.txt"
  142  git add .
  143  git add Readme.txt
  144  git commit -m "Updated Readme.txt"
  145  git push -u origin Ken_Branch4
  146  git checkout main
  147  git checkout -d Ken_Branch4
  148  git checkout main
  149  git branch -D Ken_Branch4
  150  git checkout -b Ken_Branch4
  151  git add .
  152  nano Readme.txt
  153   HEAD position was c42a45a Updated Readme.txt
  154  Switched to branch 'main'
  155  CallmeKen@DESKTOP-T6PO5SV MINGW64 ~/desktop/Ken_IT120_Act1 (main)
  156  $ git branch -D Ken_Branch4
  157  Deleted branch Ken_Branch4 (was c42a45a).
  158  CallmeKen@DESKTOP-T6PO5SV MINGW64 ~/desktop/Ken_IT120_Act1 (main)
  159  $ git checkout -b Ken_Branch4
  160  Switched to a new branch 'Ken_Branch4'
  161  CallmeKen@DESKTOP-T6PO5SV MINGW64 ~/desktop/Ken_IT120_Act1 (Ken_Branch4)
  162  $ git add .
  163  nano Readme.txt
  164  git commit -m "Updated Readme.txt"
  165  git push -u origin Ken_Branch4
  166  git checkout main
  167  exit
  168  cd
  169  cd desktop
  170  cd Ken_IT120_Act1
  171  git checkout main
  172  git pull origin main
  173  git merge Ken_Branch1
  174  git push origin main
  175  checkout main
  176  git checkout Baldomar_IT120_Act1
  177  git push origin -u main
  178  git push -u origin main
  179  xit
  180  exit
  181  cd desktop
  182  cd Ken_IT120_Act1
  183  git checkout main
  184  git pull origin main
  185  git pull origin main --allow-unrelated-histories
  186  cd ~/desktop/Ken_IT120_Act1
  187  git merge Ken_Branch1
  188  git status
  189  git add Readme.txt
  190  git commit
  191  git add .
  192  git push origin main
  193  git merger Ken_Branch1
  194  git merge Ken_Branch1
  195  git push origin main
  196  git merger Ken_Branch2
  197  git merge Ken_Branch2
  198  git merge Ken_Branch3
  199  git merge Ken_Branch4
  200  git push origin main
  201  git merge Baldomar_IT120_Act1
  202  git add Profile.txt Education.txt Background.txt Readme.txt
  203  git commit
  204  git push origin main
  205  git merge Ken_Branch1
  206  git push origin main
  207  exit
  208  cd desktop
  209  cd Ken_IT120_Act1
  210  git add .
  211  git push -u origin main
  212  git remote -v
  213  git pull origin main
  214  git commit -m "Initial commit with all files"
  215  git add .
  216  git branch -M main
  217  git push -u origin main
  218  git push origin main --force
  219  git rm -r *
  220  git commit -m "Deleted all files"
  221  git push origin main
  222  nano Profile.txt
  223  git checkout master
  224  mkdir master
  225  echo "This is the master folder" > master/Readme.md
  226  git add master
  227  git commit -m "Created master folder with Readme.md"
  228  git push origin main
  229  git mv master Baldomar_Master_Act1
  230  git commit -m "Renamed master folder to Baldomar_Master_Act1"
  231  git push origin main
  232  git checkout Baldomar_Master_Act1
  233  git checkout master
  234  cd master
  235  git checkout -b Baldomar_IT120_Act1
  236  git checkout -b Baldomar_IT120_ACT1
  237  cd documents
  238  cd Ken_IT120
  239  git init
  240  touch Profile.txt Education.txt Background.txt Readme.txt
  241  git init
  242  exit
  243  cd Documents
  244  cd Ken_IT120
  245  git init
  246  cd Desktop
  247  exit
  248  cd Desktop
  249  cd Ken_IT120
  250  git mv master Baldomar_IT120_Act1
  251  git init
  252  touch Profile.txt Education.txt Background.txt Readme.txt
  253  echo 'import os/nprint("Hello World")' > Test.py
  254  nano Profile.txt
  255  nano Education.txt
  256  nano Background.txt
  257  git add .
  258  git remote add origin Https://github.com/ItsmeHaru-hub/Baldomar_IT120_Act1.git
  259  git add .
  260  git commit -m "Initial commit with all files"
  261  script -a Readme.txt
  262  echo "git checkout -b Ken_IT120" >> Readme.txt
  263  git add Readme.txt
  264  git commit -m "Recorded command: git checkout -b Ken_IT120"
  265  git add .
  266  git commit -m "Initial commit with all files"
  267  git push -u origin main
  268  git checkout main
  269  git push origin master
  270  git chekout -b main
  271  git checkout -b main
  272  git add .
  273  git commit -m "Initial commit with all files"
  274  git push origin main
  275  git remote -v
  276  git push origin main --force
  277  git remote add origin https://github.com/ItsmeHaru-hub/Baldomar_IT120_Act1.git
  278  git remote set-url origin https://github.com/ItsmeHaru-hub/Baldomar_IT120_Act1.git
  279  git remote -v
  280  git push origin main
  281  git push origin main --force
  282  git push origin main
  283  git checkout -b Ken_B1
  284  nano Profile.txt
  285  git add .
  286  nano Profile.txt
  287  git add Profile.txt
  288  git commit -m "Updated Profile.txt"
  289  git push origin Ken_B1
  290  nano Profile.txt
  291  git add .
  292  git add Profile.txt
  293  git commit -m "Updated Profile.txt"
  294  git push origin Ken_B1
  295  git mr -r Ken_B1 *
  296  git rm -r Ken_B1 *
  297  git branch -d Ken_B1
  298  git push origin --delete Ken_B1
  299  git checkout main
  300  git add .
  301  git commit -m
  302  git commit -m "Initial commit with all files"
  303  git checkout -b Baldomar_IT120_Act1
  304  git add . 
  305  git commit -m "Initial commit with all files"
  306  git add Profile.txt Education.txt Background.txt Readme.txt Test.py
  307  git commit -m "Initial commit with all files"
  308  git psuh -u origin Baldomar_IT120_Act1
  309  git push -u origin Baldomar_IT120_Act1
  310  git checkout main
  311  git add .
  312  git branch -M main
  313  git push -u origin main
  314  git checkout -b Ken_B1
  315  git checkout -b Ken_Branch1
  316  git add .
  317  git add Profile.txt
  318  nano Profile.txt
  319  git commit -m "Updated Profile.txt"
  320  git push -u origin Ken_Branch1
  321  git push origin --delete Ken_Branch1
  322  git checkout main
  323  git push origin --delete Ken_Branch1
  324  git pull origin main
  325  git merge Ken_Branch1
  326  git push origin main
  327  cd desktop
  328  cd Ken_IT120
  329  cd Ken_IT120_Act1
  330  git init
  331  touch Profile.txt Education.txt Background.txt Readme.txt Test.py
  332  nano Profile.txt
  333  nano Education.txt
  334  Background.txt
  335  nano Background.txt
  336  script -f Readme.txt
  337  nano Test.py
  338  git add .
  339  git remote add origin https://github.com/ItsmeHaru-hub/Baldomar_IT120_Act1.git
  340  git remote -v
  341  git add .
  342  git commit -m "Initial commit with all files"
  343  git branch -M main
  344  git push -u origin main
  345  git push origin main --force
  346  git push -u origin main
  347  git add .
  348  git commit -m "Initial commit with all files"
  349  git push -u origin main
  350  history > Readme.txt
  351  git add .
  352  git commit -m "Initial commit with all files"
  353  git push -u origin main
  354  git checkout Baldomar_IT120_Act1
  355  git checkout -b Ken_Branch1
  356  nano Profile.txt
  357  git add Profile.txt
  358  git commit -m "Updated Profile.txt"
  359  git push -u origin Ken_Branch1
  360  git push origin Ken_Branch1
  361  find . -type f ! -name 'Profile.txt' -exec sh -c '> "$0"' {} \;
  362  git checkout Ken_Branch1
  363  git checkout Ken_Branch1
  364  git checkout -b Ken_Branch1
  365  nano Profile.txt
  366  git add Profile.txt
  367  git commit -m "Updated Profile.txt"
  368  git push origin Ken_Branch1
  369  git push -u origin Ken_Branch1
  370  cd Desktop
  371  cd IT106_ACT1
  372  exit
  373  cd Desktop
  374  cd IT120_ACT1
  375  git checkout main
  376  git checkout -b main
  377  git init
  378  git checkout main
  379  git push origin main --force
  380  git add remote https://github.com/ItsmeHaru-hub/Baldomar_IT106_Act1.git
  381  touch Profile.txt
  382  touch Education.txt Background.txt Readme.txt Test.py
  383  nano Profile.txt
  384  nano Education.txt
  385  Background.txt
  386  nano Background.txt
  387  nano Test.py
  388  git remote add https://github.com/ItsmeHaru-hub/Baldomar_IT106_Act1.git
  389  git branch -M main
  390  git remote 
  391  git remote add origin https://github.com/ItsmeHaru-hub/Baldomar_IT106_Act1.git
  392  git branch -M main
  393  git push -u origin main
  394  git branch
  395  git branch -M main
  396  git push -u origin main
  397  git push origin --delete master
  398  git remote -v
  399  git checkout -b main
  400  git branch -M main
  401  git push -u origin main
  402  git init
  403  echo "# main" >> README.md
  404  git add README.md
  405  git commit -m "first commit"
  406  git branch -M main
  407  git remote add origin https://github.com/ItsmeHaru-hub/Baldomar_IT106_Act1.git
  408  git push -u origin main
  409  git add .
  410  git commit -m "Initial commit with all files"
  411  git push -u origin main
  412  git add .
  413  history > Readme.txt
  414  git add Readme.txt
  415  git commit -m "Updated Readme.txt"
  416  git push -u origin main
  417  git checkout -b Ken_Branch1
  418  nano Profile.txt
  419  git add .
  420  git add Profile.txt
  421  git commit -m "Updated Profile.txt"
  422  git push -u origin Ken_Branch1
  423  for file in *; do if ["$file" != "Profile.txt"]; then > "$file"; fi; done
  424  for file in *; do  if [ "$file" != "Profile.txt" ]; then fi
  425  for file in *; do  if [ "$file" != "Profile.txt" ]; then
  426  cd Desktop
  427  cd IT120_ACT1
  428  for file in *; do  if [ "$file" != "Profile.txt" ]; then  fi
  429  for file in *; do if [ "$file" != "Profile.txt" ]; then fi
  430  for file in *; do  fi [ "$file" != "Profile.txt" ]; then
  431  for file in *; do  if [ "$file" != "Profile.txt" ]; then    > "$file";  fi; done
  432  git add .
  433  git commit -m "Emptied all files except Profile.txt"
  434  git push origin Ken_Branch1
  435  history > Readme.txt
  436  git add .
  437  git add Readme.txt
  438  git commit -m "Updated Readme.txt"
  439  git push origin Ken_Branch1
  440  git checkout main
  441  git checkout -b Ken_Branch2
  442  nano Education.txt
  443  git add .
  444  git add Education.txt
  445  git commit -m "Updated Education.txt"
  446  git push -u origin Ken_Branch2
  447  for file in *; do  if [ "$file" != "Profile.txt" ]; then    > "$file";  fi; exit; done
  448  cd
  449  cd desktop
  450  cd IT120_ACT1
  451  for file in *; do  if [ "$file" != "Education.txt" ]; then    > "$file"; fi; done
  452  git add .
  453  git commit -m "Cleared all files except Education.txt in Ken_Branch2"
  454  git push -u origin Ken_Branch2
  455  history > Readme.txt
  456  git add .
  457  git add Readme.txt
  458  git commit -m "Updated Readme.txt"
  459  git push -u origin Ken_Branch2
  460  git checkout main
  461  git checkout -b Ken_Branch3
  462  git add .
  463  nano Background.txt
  464  git add Background.txt
  465  git commit -m "Updated Background.txt"
  466  git push -u origin Ken_Branch3
  467  for file *; do
  468  for file in *; do  if [ "$file" != "Profile.txt" ]; then  if [ "$file" != "Background.txt" ]; then    > "$file";  fi; done
  469  for file in *; do  if [ "$file" != "Background.txt" ]; then    > "$file";  fi; done
  470  history > Readme.txt
  471  git add .
  472  git commit -m "Updated Readme.txt and Cleared all files except Background.txt in Ken_Branch3"
  473  git push -u origin Ken_Branch3
  474  git rm -r Test.py
  475  history > Readme.txt
  476  git add .
  477  git add Readme.txt
  478  git commit -m "Deleted Test.py and Updated Readme.txt"
  479  git push -u origin Ken_Branch3
  480  git checkout main
  481  git checkout -b Ken_Branch4
  482  git rm -r Test.py
  483  history > Readme.txt
  484  git add .
  485  git add Readme.txt
  486  git commit -m "Deleted Test.py and Updated Readme.txt"
  487  git push -u origin Ken_Branch4
  488  for file in *; do  if [ "$file" != "Readme.txt" ]; then    > "$file";  fi; done
  489  git add .
  490  history > Readme.txt
  491  git add Readme.txt
  492  git commit -m "Cleared all files exept Readme.txt in Ken_Branch4"
  493  git push -u origin Ken_Branch4
  494  git checkout main
  495  git log --oneline
  496  git reset --hard e3a1c9f
  497  git log --oneline
  498  git reset --hard 19344ae
  499  git pull origin main
  500  git revert -m 1 19344ae
  501  cd desktop/IT120_ACT1
  502  git revert -m 1 19344ae -m "Revert merge commit 19344ae"
  503  git log --oneline
  504  git revert -m 1 19344ae -m "Revert merge commit 19344ae"
  505  git revert -m 1 19344ae -m "Revert merge commit 19344ae"
  506  git reset --hard 19344ae
  507  git push origin main
  508  nano Profile.txt
  509  nano Education.txt
  510  nano Background.txt
  511  nano Test.py
  512  git add .
  513  git commit -m "Initial commit with all files"
  514  git push -u origin main
  515  git checkout -b Baldomar_IT120_Act1
  516  git add .
  517  git commit -m "Master Folder for all files"
  518  git add Profile.txt Education.txt Background.txt Readme.txt Test.py
  519  git commit -m "Master Folder for all files"
  520  git push origin Baldomar_IT120_Act1
  521  git checkout main
  522  git merge Ken_Branch1
  523  git merge Ken_Branch2
  524  git merge --squash Ken_Branch1
  525  git commit -m "Merge Ken_Branch1 into main"
  526  git push -u origin main
  527  nano Test.py
  528  git add Education.txt Readme.txt Test.py
  529  git commit -m "Resovle conflicts and merged Ken_Branch1 into main"
  530  git push origin to main
  531  git push origin main
  532  git add .
  533  nano Profile.txt
  534  nano Background.txt
  535  git add Profile.txt Background.txt
  536  git commit -m "Updated Profile.txt Background.txt"
  537  git push -u origin main
  538  git merge --squash Ken_Branch1 Ken_Branch3
  539  git commit -m "Merge Ken_Branch1 Ken_Branch2 into main"
  540  nano Test.py
  541  nano Profile.txt
  542  git commit -m "Merge Ken_Branch1 Ken_Branch3 into main"
  543  nano Education.txt
  544  nano Readme.txt
  545  git commit -m "Resolve conflicts and merge Ken_Branch1 Ken_Branch3 into main"
  546  nano Background.txt
  547  nano Profile.txt
  548  git add .
  549  git commit -m "Merge Ken_Branch1 into main"
  550  git push -u origin main
  551  nano Profile.txt
  552  git pull origin main
  553  git merge Ken_Branch1
  554  git add .
  555  git commit
  556  git push origin main
  557  git checkout Ken_Branch1
  558  cat Profile.txt
  559  git checkout main
  560  git pull origin main
  561  git merger Ken_Branch1
  562  git merge Ken_Branch1
  563  history > Readme.txt
  564  git checkout Ken_Branch1
  565  git checkout Ken_Branch1
  566  git checkout Ken_Branch1
  567  git commit --abort
  568  git reset --commit
  569  git reset --hard
  570  git checkout Ken_Branch1
  571  git add .
  572  history > Readme.txt
