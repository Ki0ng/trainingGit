---
marp: true
theme: default
paginate: true
style: |
  section {
    display: flex !important;
    flex-direction: column !important;
    justify-content: flex-start !important;
    align-items: flex-start !important;
    place-content: flex-start flex-start !important;
    text-align: left !important;
    background-color: #ffffff;
    color: #1e293b;
    font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    padding: 40px 50px;
    font-size: 20px;
    line-height: 1.35;
  }
  h1 {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 15px;
    color: #0fb9e4;
    font-size: 2.1rem;
    border-bottom: 4px solid #fbb316;
    padding-bottom: 8px;
    margin-top: 0;
    margin-bottom: 8px;
    width: 100%;
  }
  .title-logo {
    height: 48px;
    width: 48px;
    object-fit: contain;
    flex-shrink: 0;
  }
  h2 {
    color: #d97706;
    font-size: 1.4rem;
    margin-top: 0;
    margin-bottom: 14px;
    font-weight: 600;
    text-align: left;
    width: 100%;
  }
  h3 {
    color: #0fb9e4;
    font-size: 1.2rem;
    margin-top: 0;
    margin-bottom: 8px;
  }
  p, li {
    margin-top: 0;
    margin-bottom: 8px;
    font-size: 1.05rem;
    text-align: left;
  }
  ul, ol {
    margin-top: 0;
    margin-bottom: 8px;
    padding-left: 24px;
    width: 100%;
  }
  code {
    background-color: #f1f5f9;
    color: #092540;
    padding: 2px 6px;
    border-radius: 4px;
    font-family: 'Consolas', 'Courier New', monospace;
    font-size: 0.95rem;
  }
  pre {
    background-color: #0f172a;
    color: #f8fafc;
    padding: 10px 14px;
    border-radius: 6px;
    border-left: 4px solid #fbb316;
    margin-top: 6px;
    margin-bottom: 10px;
    width: 100%;
    box-sizing: border-box;
  }
  pre code {
    background-color: transparent;
    color: #f8fafc;
    font-size: 0.9rem;
  }
  .highlight {
    color: #fbb316;
    font-weight: bold;
  }
  .accent {
    color: #0fb9e4;
    font-weight: bold;
  }
  .box {
    background-color: #ffffff;
    border: 2px solid #cbd5e1;
    border-radius: 8px;
    padding: 12px;
    margin-bottom: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.03);
    width: 100%;
    box-sizing: border-box;
  }
  .practice-box {
    background-color: #f0fdf4;
    border: 2px solid #22c55e;
    border-radius: 8px;
    padding: 12px;
    margin-bottom: 10px;
    width: 100%;
    box-sizing: border-box;
  }
  .practice-box h3 {
    color: #15803d;
  }
  .grid-2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    align-items: start;
    margin-top: 10px;
    width: 100%;
  }
  .grid-3 {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 12px;
    margin-top: 10px;
    width: 100%;
  }
  img {
    border-radius: 6px;
    max-height: 350px;
    object-fit: contain;
  }
  .center-page-image {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    flex: 1;
  }
  .center-page-image img {
    display: block;
    max-width: 100%;
    max-height: 100%;
  }
  table {
    font-size: 0.9rem;
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
  }
  th, td {
    padding: 6px 8px;
    border: 1px solid #cbd5e1;
    text-align: left;
  }
  th {
    background-color: #f8fafc;
  }
---

<!-- Slide 1: Cover Slide - Introduction Git & GitHub -->
# <img src="./images/logo.png" class="title-logo" /> INTRODUCTION TO GIT & GITHUB
## Git, GitHub

<div class="box" style="text-align: center; padding: 10px;">
    <img src="./images/imageGit.png" width="100%" style="max-height: 220px; object-fit: contain;" alt="Git Installation" />
</div>

---

<!-- Slide 2: Khóa Học OVERVIEW -->
# <img src="./images/logo.png" class="title-logo" /> TỔNG QUAN 5 BUỔI HỌC
## Lộ trình cho học PNV28

<div class="box">
  <h3>Buổi 1: Giới thiệu Git, Khái niệm cơ bản, Init / Add / Commit / Log</h3>
  <p>Làm quen Git, cài đặt, tạo account GitHub, hiểu 3 vùng dữ liệu & lệnh Terminal đầu tiên.</p>
</div>

<div class="box">
  <h3>Buổi 2: Git Branching, Merge & Conflict Resolution</h3>
  <p>Tạo nhánh độc lập, gộp code và kỹ thuật tự tay xử lý đụng độ code thủ công.</p>
</div>

<div class="box">
  <h3>Buổi 3: GitHub Remote - Push / Pull / Clone & Pull Requests</h3>
  <p>Đưa dự án lên đám mây, đồng bộ dữ liệu và quy trình duyệt code (PR) chuẩn team.</p>
</div>

<div class="box">
  <h3>Buổi 4: Workflow Thực Tế (Git Flow, Feature Branch) & Teamwork</h3>
  <p>Mô hình Git Flow chuẩn doanh nghiệp, làm việc nhóm an toàn với GitHub.</p>
</div>

<div class="box">
  <h3>Buổi 5: Quản Lý Dự Án Jira & Liên Kết GitHub</h3>
  <p>Tạo Project/Board trên Jira, theo dõi công việc và tự động hóa trạng thái với Git.</p>
</div>

---

<!-- Slide 3: BUỔI 1 OVERVIEW -->
# <img src="./images/logo.png" class="title-logo" /> BUỔI 1: OVERVIEW NỘI DUNG HỌC
## Cài Đặt, Khái Niệm Cơ Bản & Câu Lệnh Terminal Khởi Đầu

<div class="grid-2">
  <div>
    <div class="box">
      <h3>Các Nội Dung Chính</h3>
      <p>1. Hiểu nhanh Git là gì & phân biệt Git vs GitHub / SourceTree.</p>
      <p>2. Cài đặt Git & Đăng ký tài khoản GitHub.</p>
      <p>3. Nắm vững 3 Vùng Dữ Liệu Trong Git.</p>
      <p>4. Các câu lệnh Terminal căn bản: <code>init</code>, <code>status</code>, <code>add</code>, <code>commit</code>, <code>log</code>.</p>
    </div>
  </div>
  <div>
    <img src="./images/gitAdSourceTree.jpg" width="100%" alt="Buổi 1 Overview" />
  </div>
</div>

---

<!-- Slide 4: Buổi 1 - Giới Thiệu Git Ngắn Gọn -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 1: Git Là Gì & Tại Sao Lại Dùng Git?
## Giới thiệu cực kỳ dễ hiểu dành cho người mới

<div class="grid-2">
  <div>
    <div class="box">
      <h3>Git Là Gì? (Nhật Ký Lưu Bản Vẽ)</h3>
      <p>Giống như nút <b>"Save / Undo"</b> thông minh. Giúp bạn lưu lại từng mốc thời gian của file code để quay lại bất kỳ lúc nào nếu lỡ làm hỏng.</p>
    </div>
    <div class="box">
      <h3>Mục Đích Sử Dụng</h3>
      <p>• Tránh việc phải lưu file thủ công: <code>Code_v1.zip</code>, <code>Code_Final.zip</code>.</p>
      <p>• Cho phép 10 người cùng sửa 1 dự án mà không lo đè mất code của nhau.</p>
    </div>
  </div>
  <div>
    <img src="./images/gitOverview.jpg" width="100%" alt="Khái niệm Git trực quan" />
  </div>
</div>

---

<!-- Slide 5: Buổi 1 - Phân Biệt Tool -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 1: Phân Biệt Git, GitHub & SourceTree
## Đừng nhầm lẫn giữa engine, server đám mây và giao diện đồ họa!

<div class="grid-3">
  <div class="box">
    <h3>1. Git (Động cơ)</h3>
    <p>Phần mềm chạy dòng lệnh cài trên máy bạn để lưu lịch sử code local.</p>
  </div>
  <div class="box">
    <h3>2. GitHub / Bitbucket</h3>
    <p>Website lưu trữ kho chứa code lên đám mây để chia sẻ cho cả team.</p>
  </div>
  <div class="box">
    <h3>3. SourceTree / Client</h3>
    <p>Phần mềm giao diện đồ họa (nút bấm) giúp thao tác Git không cần gõ lệnh.</p>
  </div>
</div>

<div class="grid-2" style="margin-top: 10px;">
  <div>
    <img src="./images/imageCompare.png" width="100%" alt="So sánh công cụ Git" />
  </div>
  <div>
    <div class="practice-box">
      <h3>Mini Practice 1.1</h3>
      <p><b>Câu hỏi nhanh:</b> Bạn A dùng VS Code sửa file, bấm nút <i>Commit</i> rồi đẩy lên <i>GitHub</i>. Trong luồng này, đâu là Git và đâu là GitHub?</p>
    </div>
  </div>
</div>

---

<!-- Slide 6: Buổi 1 - Cài Đặt Git Step-by-Step -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 1: Cài Đặt Git Cho Windows & Mac
## Hướng dẫn từng bước tải và cài đặt phần mềm

<div class="grid-2">
  <div>
    <h3>Các Bước Thực Hiện:</h3>
    <p><b>1. Tải bộ cài:</b> Truy cập <span class="accent">https://git-scm.com/downloads</span> chọn installer phù hợp.</p>
    <p><b>2. Cài đặt:</b> Giữ nguyên cài đặt mặc định (Default). Tích chọn <b>Git Bash</b> trên Windows.</p>
    <p><b>3. Kiểm tra:</b> Mở Terminal / Git Bash gõ lệnh test:</p>
    <pre><code>git --version</code></pre>
  </div>
  <div>
    <img src="./images/buoi1-install-git.png" width="100%" alt="Hướng dẫn cài đặt Git" />
  </div>
</div>

---

<!-- Slide 7: Buổi 1 - Git Config & GitHub Register -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 1: Thiết Lập Identity & Account GitHub
## Khởi tạo thông tin người dùng local và tài khoản web

<div class="grid-2">
  <div>
    <h3>1. Thao Tác Terminal (Config Email/Name)</h3>
    <pre><code>git config --global user.name "Nguyen Van A"
git config --global user.email "a.nguyen@gmail.com"
git config --list</code></pre>
    <p><i>Email config trùng 100% với Email đăng ký GitHub!</i></p>
  </div>
    <div>
        <h3>2. Đăng Ký GitHub Web</h3>
        <p>Truy cập <span class="accent">https://github.com</span> &rarr; bấm <b>Sign Up</b> &rarr; Điền Email, Pass, Username &rarr; Xác minh OTP qua mail.</p>
    </div>
</div>

<div class="practice-box">
  <h3>Mini Practice 1.2: Thực Hành Cài Đặt & Cấu Hình</h3>
  <p>1. Chạy lệnh <code>git config --list</code> trên máy cá nhân và chụp lại màn hình tên/email đã đặt.</p>
  <p>2. Đăng ký thành công 1 tài khoản GitHub cá nhân.</p>
</div>

---

<!-- Slide 8: Buổi 1 - 3 Vùng Dữ Liệu Trong Git -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 1: 3 Vùng Dữ Liệu Trong Git
## Cực kỳ dễ hiểu qua mô hình Đi Siêu Thị

<div class="grid-2">
  <div>
    <div class="box">
      <h3>1. Working Directory</h3>
      <p>Nơi viết code trực tiếp trên VS Code (Giống hàng hóa nằm trên kệ siêu thị).</p>
    </div>
    <div class="box">
      <h3>2. Staging Area (Khu vực chờ)</h3>
      <p>Dùng lệnh <code>git add .</code> để chọn file (Giống nhặt đồ bỏ vào <b>Giỏ Hàng</b>).</p>
    </div>
    <div class="box">
      <h3>3. Local Repository (Kho lưu trữ)</h3>
      <p>Dùng <code>git commit</code> để đóng gói vĩnh viễn (Giống tính tiền nhận <b>Hóa Đơn</b>).</p>
    </div>
  </div>
  <div>
    <img src="./images/3-vung-du-lieu.png" width="100%" alt="3 vùng dữ liệu trong Git" />
  </div>
</div>

---

<!-- Slide 9: Buổi 1 - Câu Lệnh Terminal Căn Bản -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 1: Thao Tác Dòng Lệnh Git Căn Bản
## Các lệnh làm việc local chạy hàng ngày

<div class="grid-2">
  <div>
    <p><code>git init</code> : Biến 1 thư mục thường thành kho chứa Git.</p>
    <p><code>git status</code> : Kiểm tra trạng thái các file (đã sửa / chưa add).</p>
    <p><code>git add .</code> : Đưa file vào Staging Area (Giỏ hàng).</p>
    <p><code>git commit -m "Mô tả"</code> : Chốt phiên bản kèm lời nhắn.</p>
    <p><code>git log --oneline</code> : Xem lại lịch sử các commit.</p>
  </div>
  <div>
    <img src="./images/buoi1-basic-commands.png" width="100%" alt="Sơ đồ câu lệnh Git căn bản" />
  </div>
</div>

<div class="practice-box">
  <h3>Mini Practice 1.3: Bài Tập Commit Đầu Tiên</h3>
  <p>Tạo thư mục <code>my-project</code> &rarr; Chạy <code>git init</code> &rarr; Tạo file <code>index.html</code> &rarr; Chạy <code>git add .</code> &rarr; Commit với tin nhắn <i>"Init project"</i> &rarr; Kiểm tra lại bằng <code>git log</code>.</p>
</div>

---

<!-- Slide 10: BUỔI 2 OVERVIEW -->
# <img src="./images/logo.png" class="title-logo" /> BUỔI 2: OVERVIEW NỘI DUNG HỌC
## Git Branching, Merge & Conflict Resolution

<div class="grid-2">
  <div>
    <div class="box">
      <h3>Các Nội Dung Chính</h3>
      <p>1. Khái niệm nhánh (Branch) và tại sao phải chia nhánh?</p>
      <p>2. Các lệnh thao tác nhánh: <code>branch</code>, <code>checkout</code>, <code>checkout -b</code>.</p>
      <p>3. Gộp nhánh (Merge code) về nhánh chính <code>main</code>.</p>
      <p>4. Nhận diện và tự tay giải quyết Merge Conflict thủ công.</p>
    </div>
  </div>
  <div>
    <img src="./images/buoi2-overview.png" width="100%" alt="Buổi 2 Overview" />
  </div>
</div>

---

<!-- Slide 11: Buổi 2 - Quản Lý Nhánh (Branch) -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 2: Kỹ Thuật Chia Nhánh (Branching)
## Giúp bạn làm tính năng mới cực kỳ an toàn

<div class="grid-2">
  <div>
    <h3>Lệnh Thao Tác Nhánh:</h3>
    <p>• Xem danh sách nhánh: <code>git branch</code></p>
    <p>• Tạo nhánh mới: <code>git branch feature/login</code></p>
    <p>• Chuyển sang nhánh mới: <code>git checkout feature/login</code></p>
    <p>• Tạo & chuyển nhanh: <code>git checkout -b feature/login</code></p>
  </div>
  <div>
    <img src="./images/buoi2-git-branch-merge.png" width="100%" alt="Sơ đồ chia nhánh trong Git" />
  </div>
</div>

<div class="practice-box">
  <h3>Mini Practice 2.1</h3>
  <p>Tại dự án <code>my-project</code>, tạo nhánh mới tên <code>feature/header</code>, chuyển sang nhánh đó, tạo file <code>header.html</code> rồi thực hiện commit.</p>
</div>

---

<!-- Slide 12: Buổi 2 - Gộp Nhánh (Merge) & Conflict -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 2: Quy Trình Merge & Fix Conflict
## Cách xử lý đụng độ code khi làm việc chung file

<div class="grid-2">
  <div>
    <h3>1. Gộp Nhánh (Merge)</h3>
    <pre><code>git checkout main
git merge feature/login</code></pre>
    <h3>2. 4 Bước Fix Conflict Thủ Công</h3>
    <p><b>B1:</b> Mở file lỗi trên VS Code tìm vạch <code><<<<<<< HEAD</code>.</p>
    <p><b>B2:</b> Thảo luận với bạn cùng team để chọn đoạn code đúng.</p>
    <p><b>B3:</b> Xóa vạch ký hiệu, chạy <code>git add .</code></p>
    <p><b>B4:</b> Chốt commit: <code>git commit -m "Fix conflict"</code></p>
  </div>
  <div>
    <img src="./images/buoi2-conflict-resolution.png" width="100%" alt="Giao diện Fix Conflict trên VS Code" />
  </div>
</div>

<div class="practice-box">
  <h3>Mini Practice 2.2: Thử Tạo & Sửa Conflict</h3>
  <p>Tạo 2 nhánh cùng sửa dòng 1 file <code>README.md</code>. Tiến hành Merge nhánh 2 vào nhánh 1 để kích hoạt conflict, sau đó dùng VS Code sửa và commit lại!</p>
</div>

---

<!-- Slide 13: BUỔI 3 OVERVIEW -->
# <img src="./images/logo.png" class="title-logo" /> BUỔI 3: OVERVIEW NỘI DUNG HỌC
## GitHub Remote Repository & Quy Trình Pull Request (PR)

<div class="grid-2">
  <div>
    <div class="box">
      <h3>Các Nội Dung Chính</h3>
      <p>1. Kết nối Git Local với Remote Repo trên GitHub Web.</p>
      <p>2. Thành thạo 3 lệnh đồng bộ: <code>clone</code>, <code>push</code>, <code>pull</code>.</p>
      <p>3. Quy trình gửi Pull Request (PR) để xin gộp code.</p>
      <p>4. Cách phân công Assignee, chỉ định Reviewer và Comment duyệt code.</p>
    </div>
  </div>
  <div>
    <img src="./images/buoi3-overview.png" width="100%" alt="Buổi 3 Overview" />
  </div>
</div>

---

<!-- Slide 14: Buổi 3 - Các Lệnh Đám Mây -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 3: Kết Nối GitHub Remote (Clone/Push/Pull)
## Đưa project từ máy cá nhân lên server đám mây

<div class="grid-2">
  <div>
    <h3>1. Liên Kết Remote Repo</h3>
    <pre><code>git remote add origin <URL-GitHub></code></pre>
    <h3>2. 3 Lệnh Thao Tác Chính</h3>
    <p>• <code>git clone <URL></code> : Tải toàn bộ Repo từ GitHub về máy mới.</p>
    <p>• <code>git push origin <branch></code> : Đẩy commit từ máy lên GitHub.</p>
    <p>• <code>git pull origin <branch></code> : Tải code mới nhất từ GitHub về máy.</p>
  </div>
  <div>
    <img src="./images/buoi3-github-remote-push-pull.png" width="100%" alt="Thao tác Push Pull Clone" />
  </div>
</div>

<div class="practice-box">
  <h3>Mini Practice 3.1</h3>
  <p>Tạo Repo mới trên GitHub web &rarr; Liên kết với project dưới máy qua <code>git remote add origin</code> &rarr; Push nhánh <code>main</code> lên GitHub.</p>
</div>

---

<!-- Slide 15: Buổi 3 - Quy Trình Pull Request (PR) -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 3: Quy Trình Mở & Duyệt Pull Request (PR)
## Quy chuẩn kiểm tra chất lượng code trước khi gộp nhánh main

<div class="grid-2">
  <div>
    <h3>Các Bước Thực Hiện PR Chuyên Nghiệp:</h3>
    <p><b>1. Push nhánh:</b> <code>git push origin feature/user-profile</code></p>
    <p><b>2. Mở PR:</b> Vào GitHub bấm <b>Compare & pull request</b>.</p>
    <p><b>3. Description:</b> Nhập mô tả công việc đã hoàn thành.</p>
    <p><b>4. Gán người:</b> Chọn bản thân ở <b>Assignees</b>, chọn Leader ở <b>Reviewers</b>.</p>
    <p><b>5. Review & Merge:</b> Leader xem Diff, Comment, Approve &rarr; Bấm <b>Merge Pull Request</b>.</p>
  </div>
  <div>
    <img src="./images/buoi3-github-remote-push-pull.png" width="100%" alt="Giao diện Pull Request trên GitHub" />
  </div>
</div>

<div class="practice-box">
  <h3>Mini Practice 3.2: Bài Tập Làm Việc Cặp</h3>
  <p>Học viên A tạo nhánh feature, push lên GitHub và mở PR &rarr; Gán Học viên B làm Reviewer &rarr; Học viên B vào comment check code và bấm Approve &rarr; Tiến hành Merge PR.</p>
</div>

---

<!-- Slide 16: BUỔI 4 OVERVIEW -->
# <img src="./images/logo.png" class="title-logo" /> BUỔI 4: OVERVIEW NỘI DUNG HỌC
## Workflow Thực Tế (Git Flow) & Làm Việc Nhóm

<div class="grid-2">
  <div>
    <div class="box">
      <h3>Các Nội Dung Chính</h3>
      <p>1. Tại sao dự án thực tế cần mô hình chuẩn (Workflow)?</p>
      <p>2. Chi tiết Mô hình nhánh Git Flow (Master, Develop, Feature, Hotfix).</p>
      <p>3. Quy tắc phối hợp làm việc nhóm an toàn trên GitHub.</p>
      <p>4. Các VS Code Extension hỗ trợ dùng Git tốt hơn (GitLens, Git Graph).</p>
    </div>
  </div>
  <div>
    <img src="./images/buoi4-overview.png" width="100%" alt="Buổi 4 Overview" />
  </div>
</div>

---

<!-- Slide 17: Buổi 4 - Mô Hình Git Flow -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 4: Mô Hình Git Flow Trong Doanh Nghiệp
## Phân loại chức năng từng nhánh trong dự án thực tế

<div class="grid-2">
  <div>
    <h3>Phân Loại Nhánh Chuẩn:</h3>
    <ul>
      <li><span class="highlight">Main / Master:</span> Code chạy trực tiếp cho khách hàng (Production-ready).</li>
      <li><span class="accent">Develop:</span> Nơi chứa code mới nhất đang thử nghiệm.</li>
      <li><b>Feature Branches:</b> Nhánh làm tính năng riêng (VD: <code>feature/login</code>).</li>
      <li><b>Hotfix Branches:</b> Nhánh vá lỗi gấp trực tiếp trên <code>main</code>.</li>
    </ul>
  </div>
  <div>
    <img src="./images/buoi4-git-flow-diagram.png" width="100%" alt="Sơ đồ mô hình Git Flow" />
  </div>
</div>

<div class="practice-box">
  <h3>Mini Practice 4.1</h3>
  <p>Cả nhóm thống nhất tạo nhánh <code>develop</code> từ <code>main</code>. Mỗi thành viên rẽ nhánh <code>feature/ten-minh</code> từ <code>develop</code> để làm bài tập, sau đó mở PR gộp lại vào <code>develop</code>.</p>
</div>

---

<!-- Slide 18: Buổi 4 - Extensions Hỗ Trợ Git -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 4: Các Extension Hỗ Trợ Git Trên VS Code
## Tăng tốc độ làm việc và soi lịch sử code trực quan

<div class="grid-2">
  <div>
    <h3>1. GitLens</h3>
    <p>Hiển thị trực tiếp ai là người viết từng dòng code (Git Blame) và lịch sử chỉnh sửa theo thời gian thực.</p>
    <h3>2. Git Graph</h3>
    <p>Vẽ sơ đồ cây các nhánh, các điểm Commit & Merge bằng giao diện hình ảnh đẹp mắt, dễ thao tác.</p>
  </div>
  <div>
    <img src="./images/buoi4-git-extensions.png" width="100%" alt="Extensions GitLens và Git Graph" />
    <img src="./images/buoi4-git-extensionss.png" width="100%" alt="Extensions GitLens và Git Graph" />
  </div>
</div>

---

<!-- Slide 19: BUỔI 5 OVERVIEW -->
# <img src="./images/logo.png" class="title-logo" /> BUỔI 5: OVERVIEW NỘI DUNG HỌC
## Quản Lý Dự Án Jira & Liên Kết Tự Động Với GitHub

<div class="grid-2">
  <div>
    <div class="box">
      <h3>Các Nội Dung Chính</h3>
      <p>1. Giới thiệu các Tool quản lý công việc: Jira, Trello & GitHub Projects.</p>
      <p>2. Khởi tạo Project & thiết lập Board (Kanban/Scrum) trên Jira.</p>
      <p>3. Quản lý các loại Issue (Epic, Story, Task, Bug).</p>
      <p>4. Tự động hóa liên kết Task ID Jira với Git Commit & Pull Request.</p>
    </div>
  </div>
  <div>
    <img src="./images/buoi5-overview.png" width="100%" alt="Buổi 5 Overview" />
  </div>
</div>

---

<!-- Slide 20: Buổi 5 - Jira Project & Task Types -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 5: Tạo Project & Quản Lý Task Trên Jira
## Theo dõi tiến độ dự án chuyên nghiệp

<div class="grid-2">
  <div>
    <h3>1. Các Cột Căn Bản Trên Board:</h3>
    <p>• <b>To Do</b> &rarr; <b>In Progress</b> &rarr; <b>Code Review</b> &rarr; <b>Done</b>.</p>
    <h3>2. Phân Loại Issue TRên Jira:</h3>
    <p>• <b>Epic:</b> Tính năng lớn dự án.</p>
    <p>• <b>Story / Task:</b> Yêu cầu công việc cụ thể (có Mã ID: <code>ECOMM-101</code>).</p>
    <p>• <b>Bug:</b> Lỗi phát sinh cần sửa.</p>
  </div>
  <div>
    <img src="./images/buoi5-jira-kanban-board.png" width="100%" alt="Jira Kanban Board" />
  </div>
</div>

<div class="practice-box">
  <h3>Mini Practice 5.1</h3>
  <p>Đăng nhập Jira, tạo 1 Software Project mẫu, tạo 2 Task trong cột <b>To Do</b> và gán Assignee cho bản thân.</p>
</div>

---

<!-- Slide 21: Buổi 5 - Hướng Dẫn Kết Nối Jira Với GitHub (CÀI ĐẶT INTEGRATION) -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 5: Hướng Dẫn Tích Hợp Jira Với GitHub
## Các bước thiết lập liên kết hai nền tảng

<div class="grid-2">
  <div>
    <h3>4 Bước Kết Nối Hệ Thống:</h3>
    <p><b>Bước 1:</b> Vào Jira &rarr; Chọn <b>Apps</b> &rarr; Tìm app <b>GitHub for Jira</b> và bấm <i>Get it now</i>.</p>
    <p><b>Bước 2:</b> Đăng nhập tài khoản GitHub &rarr; Ủy quyền cấp phép (Authorize Atlassian).</p>
    <p><b>Bước 3:</b> Chọn Organization / Repository trên GitHub muốn kết nối với Jira Project.</p>
    <p><b>Bước 4:</b> Kiểm tra mục <b>Development</b> hiển thị trong giao diện chi tiết Task của Jira.</p>
  </div>
  <div>
    <img src="./images/buoi5-jira-github-integration-setup.png" width="100%" alt="Cài đặt kết nối Jira với GitHub" />
  </div>
</div>

---

<!-- Slide 22: Buổi 5 - Tự Động Hóa Jira + GitHub -->
# <img src="./images/logo.png" class="title-logo" /> Buổi 5: Quy Trình Tự Động Hóa Jira + GitHub
## Chỉ cần gắn Mã Task ID, Jira sẽ tự động cập nhật!

<div class="box">
  <h3>Luồng Tích Hợp Đã Tối Ưu Hóa</h3>
  <table>
    <tr>
      <th>Giai Đoạn</th>
      <th>Thao Tác Jira</th>
      <th>Thao Tác Dưới Git / GitHub</th>
    </tr>
    <tr>
      <td>1. Nhận Task</td>
      <td>Lấy mã Task ID (VD: <code>ECOMM-101</code>)</td>
      <td><code>git checkout -b feature/ECOMM-101-login</code></td>
    </tr>
    <tr>
      <td>2. Viết Code</td>
      <td>Chuyển Task sang <b>In Progress</b></td>
      <td><code>git commit -m "ECOMM-101 Add validation"</code></td>
    </tr>
    <tr>
      <td>3. Code Review</td>
      <td>Jira tự động gắn link PR vào Task</td>
      <td>Push nhánh & Tạo PR chỉ định Reviewer</td>
    </tr>
    <tr>
      <td>4. Hoàn Thành</td>
      <td>Task tự động chuyển sang <b>Done</b></td>
      <td>Merge Pull Request vào nhánh chính</td>
    </tr>
  </table>
</div>

---
# <img src="./images/logo.png" class="title-logo" /> Buổi 5: Quy Trình Tự Động Hóa Jira + GitHub
## Chỉ cần gắn Mã Task ID, Jira sẽ tự động cập nhật!

<div class="grid-2">
  <div>
    <img src="./images/buoi5-jira-github-link.png" width="100%" alt="Liên kết mã Task ID" />
  </div>
  <div>
    <img src="./images/buoi5-jira-auto-done.png" width="70%" alt="Tự động Done Task trên Jira" />
  </div>
</div>  

---

<!-- Slide 23: Tổng Kết Khóa Đào Tạo -->
# <img src="./images/logo.png" class="title-logo" /> TỔNG KẾT KHÓA ĐÀO TẠO
## Đây là phần câu hỏi

<div class="center-page-image">
  <img src="./images/git-summary-outro.png" width="50%" alt="Q & A" />
</div>
