Trước tiên bạn cần đăng nhập vào Github, sau đó ấn vào dấu + trên menu và chọn New repository.

Bạn sẽ cần đặt tên cho kho chứa của bạn. Bạn có thể chọn loại kho chứa là Public (ai cũng có thể clone) 
và Private (chỉ có những người được cấp quyền mới có thể clone).

Khi tạo xong nó sẽ dẫn bạn tới trang hướng dẫn làm việc với kho chứa vừa tạo. 
Và kho chứa của bạn bây giờ sẽ có địa chỉ là https://github.com/$user-name/$repository, ví dụ https://github.com/thachphamblog/hoc-git.
Việc của bạn bây giờ là hãy clone cái kho chứa này về máy của mình bằng lệnh git clone địa_chỉ.

Bây giờ hãy truy cập vào thư mục working tree (thư mục vừa clone repository về) và thử tạo ra một file tên là README.md, 
sau đó dùng lệnh git add để đưa file này vào Staging Area.
git add README.md
$ git commit -m "First commit on Github"

Tuy nhiên sau khi commit xong, tập tin đã được commit sẽ vẫn không thể xuất hiện trong kho chứa trên Github 
mà bạn phải làm thêm một việc nữa đó là dùng lệnh git push để đẩy các tập tin đã được commit lên Github. 
Lưu ý rằng bạn sẽ cần nhập tài khoản và mật khẩu Github.sau đó dùng lệnh git add để đưa file này vào Staging Area.
$ git push origin master
origin nghĩa là tên remote (xem ở bài sau) và master là tên branch, hai cái này mình sẽ giải thích kỹ hơn ở bài riêng của nó. 
Bây giờ bạn có thể kiểm tra kho chứa của bạn trên Github rồi đó.