
Hướng dẫn Push code lên Github:
1. git init : khởi tạo repo (trong bài này có thể bỏ qua vì đã kết nối rồi) 
2. git remote add origin "Link repo" : kết nối với remote repo (trong bài này bỏ qua vì đã kết nối rồi)
3. git add . : thêm tất cả file vào staging area
4. git commit -m "message" : commit và thêm note khi update
5. git push origin "nhánh" : push code lên nhánh, trong bài này là push lên master nên code sẽ là:
git push origin master