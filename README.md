# git-foundation-final-submission
Git Foundation Final Submission before Vibe Code

## 1. Thông tin sinh viên

- Họ tên: Phạm Thanh Thảo 
- Lớp: AIK3 
- GitHub repository:https://github.com/thao1105/git-foundation-final-submission

## 2. Quá trình học Microsoft Learn

Em đã hoàn thành 2 learning path:

1. GitHub Foundations Part 1 of 2
2. GitHub Foundations Part 2 of 2

Minh chứng hoàn thành được đính kèm trong Redmine issue.

## 3. Mục tiêu project

Project này giúp em thực hành Git/GitHub trước khi tham gia khóa Vibe Code của AKA Lab.

Các kỹ năng đã thực hành:

- Tạo và quản lý GitHub repository
- Sử dụng các lệnh Git cơ bản
- Làm việc với branch
- Tạo pull request
- Xử lý conflict cơ bản
- Rollback/revert khi code bị lỗi
- Hiểu GitHub Flow
## 4. Danh sách lệnh Git đã sử dụng

- git clone: tải repository từ GitHub về máy
- git status: kiểm tra trạng thái thay đổi
- git add: đưa file vào vùng chờ commit
- git commit: lưu lại thay đổi
- git push: đẩy code lên GitHub
- git pull: lấy thay đổi mới nhất từ GitHub
- git branch: xem hoặc tạo nhánh
- git checkout: chuyển nhánh
- git log: xem lịch sử commit
- git revert: đảo ngược một commit bị lỗi
## 5. GitHub Flow

GitHub Flow là quy trình làm việc gồm các bước:

1. Tạo branch mới từ main
2. Thực hiện thay đổi trên branch
3. Commit thay đổi
4. Push branch lên GitHub
5. Tạo pull request
6. Review và merge vào main

Quy trình này giúp nhóm làm việc an toàn hơn, tránh sửa trực tiếp trên nhánh chính.
## 6. Branch đã thực hành

Các branch đã tạo:

- feature/update-readme
- feature/add-git-command-list
- practice/conflict-demo
## 7. Pull request đã thực hành

Pull request dùng để đề xuất thay đổi trước khi merge vào nhánh main.

Các pull request đã tạo:

1. Pull request cập nhật README
2. Pull request thực hành conflict hoặc Git command list
## 8. Tình huống conflict

Em đã thực hành conflict bằng cách sửa cùng một dòng trong cùng một file ở hai branch khác nhau.

Cách xử lý:

1. Git báo file bị conflict
2. Mở file bị conflict
3. Chọn nội dung đúng cần giữ lại
4. Xóa các ký hiệu conflict như <<<<<<<, =======, >>>>>>>
5. Commit lại sau khi xử lý
## 9. Tình huống rollback/revert

Em đã thực hành revert khi một thay đổi làm sai nội dung README.

Lệnh đã dùng:

```bash
git revert <commit-id>
```

## 10. Nguyên tắc bảo mật khi dùng GitHub

Khi đưa code lên GitHub, em cần lưu ý:

- Không push mật khẩu lên GitHub
- Không push API key hoặc token
- Không đưa file `.env` chứa thông tin nhạy cảm lên GitHub
- Sử dụng `.gitignore` để loại bỏ file không cần thiết
- Kiểm tra kỹ thay đổi trước khi commit

## 11. Tôi sẽ dùng Git như thế nào khi Vibe Code với AI?

Khi Vibe Code với AI, em sẽ không sửa trực tiếp trên nhánh main.

Em sẽ tạo branch riêng cho từng tính năng hoặc từng thử nghiệm. Sau khi AI sinh code, em sẽ kiểm tra lại code, chạy thử, commit từng bước rõ ràng và tạo pull request trước khi merge.

Nếu AI sinh code lỗi hoặc làm hỏng project, em có thể dùng Git để xem lịch sử thay đổi và revert về trạng thái ổn định.

## 12. Kết luận

Qua project này, em đã thực hành các kỹ năng Git/GitHub cơ bản để chuẩn bị cho khóa Vibe Code. Em hiểu rằng Git giúp quản lý thay đổi, bảo vệ code và hỗ trợ rollback khi có lỗi.


## Pull Request Practice

Em tạo branch mới để thực hành tạo pull request trên GitHub.
## Pull Request Practice 2

Em tạo pull request thứ hai để thực hành quy trình làm việc với branch và pull request trên GitHub.

Conflict practice line: This line is from conflict demo branch.