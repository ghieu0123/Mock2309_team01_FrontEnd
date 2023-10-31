# Mock2309_team01_FrontEnd

//Nhân bản từ git về máy
git clone link.git

//tạo 1 nhánh mới ví dụ như develop. Không làm việc trên nhánh main.
//AI làm nhánh nào thì tạo nhánh ví dụ: develop_Hieu
git checkout -b newBranchName

// coding

git status		  		 // check changes
git add . 		  		 // git add folder/file.java
git commit -m "message"  //version on local
git push 		  //git push -u origin master    create & push branch

// merging: Muốn ghép nhánh
git checkout develop
git pull
git checkout yourBranchName
git merge develop

// fix conflict if exists

//Đẩy 1 file hay 1 folder lên git qua 4 lệnh dưới
git status
git add .
git commit -m ""
git push

// create merge request in git UI


// other statement
 git checkout HEAD -- file.java		// rollback file
 git checkout commit_code			// rollback by commit
 git reset --hard					// rollback to previous commit
 
git config --global user.name "Tên người dùng"
git config --global user.email "Địa chỉ mail"
 
Tutorial: https://backlog.com/git-tutorial/vn/contents/


 git checkout HEAD -- file_name //rollback file: reset về file ban đầu
 git checkout commit_code //rollback commit: rollback về commit theo mã commit
 

git log //
