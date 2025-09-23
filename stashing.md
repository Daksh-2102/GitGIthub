jab aap kisi branch mai kaam kr rhe ho and apney kuch code likha hai and apeny uss code ko
commit nhi kiya hai , aur aap dusri branch m jne ka try kr rhe ho, toh git apko bolta hai ki bhai changes
saved nhi h , wo changes delete ho jayege .... hum chaye toh un changes ko delete hone de
yan fhr , unn changes ko draft kr dein !!
jab b draft krege toh wo changes na add honge aur na delete honge , wo beech mai khin dale rhege
fhr jb aap uss branch pr aao toh firse changes apply kr skte ho!! 


stashing why?

if u r currently working in some branch and suddenly u want to switch to another branch
without commiting the current changes in that branch, u can simply stash those changes 
and u can switch to another branch and do whatever u want to do !!

use command :- git stash -> holds / saves those changes without adding/commiting it
then git switch branch_name - > make changes 
then return to the stashed branch
and if u want those stashed changes back use - > git stash apply
