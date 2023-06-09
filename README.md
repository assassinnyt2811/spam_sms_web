﻿# spam_sms_web
<a name="readme-top"></a>

[![LinkedIn][linkedin-shield]][linkedin-url]


<br />
<div align="center">
  <a href="https://github.com/">
    <img src="data_img/first_img.png" alt="Logo" width="240" height="180">
  </a>

  <h3 align="center">Spam or Ham web</h3>

  <p align="center">
    Trang web kiểm tra tin nhắn có là spam hay không
    <br />
    <a href="/link_doc"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="/link_demo">View Demo</a>
    ·
    <a href="https://github.com/">Request Feature</a>
  </p>
</div>



<details>
  <summary>Mục lục</summary>
  <ol>
    <li>
      <a href="###Giới thiệu về chủ đề">Giới thiệu vể chủ đề</a>
      <ul>
        <li><a href="#Thành Phần">Thành Phần</a></li>
      </ul>
    </li>
    <li>
      <a href="#Bắt đầu">Bắt đầu</a>
      <ul>
        <li><a href="#Môi trường cần thiết">Môi trường cần thiết</a></li>
        <li><a href="#Cài đặt">Cài đặt</a></li>
      </ul>
    </li>
    <li><a href="#Cách sử dụng">Cách sử dụng</a></li>
    <li><a href="#Các hướng đi">Các hướng đi</a></li>
    <li><a href="#Nhóm">Nhóm</a></li>
    <li><a href="#Liên Hệ">Liên Hệ</a></li>
    <li><a href="#Tài nguyên hữu ích">Tài nguyên hữu ích</a></li>
  </ol>
</details>



## Giới thiệu về chủ đề

Theo cùng chặng đường phát triển của các loại hình truyền thông cũng như internet ra đời đã thay thế phần nào số lượng tin nhắn SMS được dùng trong liên lạc, sự quan tâm quản lý của các cơ quan thực thi pháp luật còn chưa nắm bắt được diễn biến tình hình tội phạm từ đó trong khía cạnh tin nhắn SMS đã phát sinh ra nhiều tiêu cực và dần trở thành vấn đề nhức nhối. Vấn đề tiêu biểu ở đây chúng em muốn đề cập tới là tin nhắn SPAM - tin nhắn rác.

[![Product Name Screen Shot][product-screenshot]](https://example.com)


<p align="right">(<a href="#readme-top">Trở lại đầu trang</a>)</p>


### Thành Phần

Các thành phần và framework sử dụng

* [![Next][python]][Next-url]
* [![Fontawesome][fontawesome]][fontawesome-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]
* [![Boxicons][boxicons]][boxicons-url]
* [![Javascript][Javascript]][Javascript-url]
* [![HTML5][HTML5]][HTML5-url]
* [![CSS3][CSS3]][CSS3-url]
* [![MYSQL][MYSQL]][MYSQL-url]
* [![Flask][flask]][flask-url]
* [![VSCode][VSCode]][VSCode-url]
* [![XAMPP][XAMPP]][XAMPP-url]
* [![GIT][GIT]][GIT-url]


<p align="right">(<a href="#readme-top">Trở lại đầu trang</a>)</p>

 <img src="data_img/Product.png" alt="StepPython">

 

## Bắt đầu

Hướng dẫn cài đặt và chạy web với mạng Lan

### Môi trường cần thiết

Tải các bản cài đặt cần thiết để chuẩn bị cài đặt

#### Python: <a href="https://www.python.org/downloads/release/python-3109/">Python 3.10.4 </a>
<p>Tải bản tương thích với hệ điều hảnh</p>
 <img src="data_img/python/Python_1.png" alt="StepPython">
<p>Bấm vào bản cài đặt vừa tải về và bắt đầu cài</p>
  <img src="data_img/python/Python_2.png" alt="StepPython">
<p>Đảm bảo đánh dấu Add Python 3.10 to PATH nếu không bạn sẽ phải thực hiện điều đó một cách cụ thể. Nó sẽ bắt đầu cài đặt python trên windows.</p> <br />


#### XAMPP: <a href="https://www.apachefriends.org/download.html">XAMPP </a><br />
Cách cài đặt XAMPP trên Windows
+ Bước 1: Download XAMPP
+ Bước 2: Nhấp vào file có đuôi .exe trên file tải xuống.
+ Bước 3: Trên cửa sổ Set up, tích chọn các phần mềm mà bạn muốn cài đặt. Nếu bạn muốn cài WordPress trên XAMPP, các phần mềm + bắt buộc phải chọn là MySQL, Apache, PHPMyAdmin. Sau khi chọn xong, nhấn Next.
+ Bước 4: Chọn thư mục cài đặt và nhấn Next.
+ Bước 5: Chờ vài phút để cài đặt, sau khi cài đặt hoàn tất nhấn finish để kết thúc.

Cách cài đặt XAMPP trên Linux
+ Bước 1: Download XAMPP cho Linux.
+ Bước 2: Chọn file xampp-linux-x64-7.2.8-0-installer.run  trong file cài đặt
+ Đầu tiên thêm quyền thực thi cho file cài đặt

Đầu tiên thêm quyền thực thi cho file cài đặt
```sh
cd thu_muc_chua_file_cai_dat/
sudo chmod +x xampp-linux-x64-7.2.8-0-installer.run
```

Chọn cài đặt với quyền sudo.
```sh
sudo ./xampp-linux-x64-7.2.8-0-installer.run
```
Nhấn Next để cài đặt.
+ Bước 3: Trong cửa sổ Set up, tiếp tục nhấn Next tại các cửa sổ hiện ra.
+ Bước 4: Chờ vài phút để cài đặt, sau khi cài đặt hoàn tất nhấn finish để kết thúc.

+ Lưu ý trước khi cài đặt
Một lưu ý cho người dùng trước khi cài đặt XAMPP là phải xóa hết tất cả phần mềm liên quan đến việc làm localhost như PHP, MySQL. Ngoài ra, trong trường hợp máy chủ Windows đã cài đặt IIS, việc cài XAMPP là điều không cần thiết. Không dùng đồng thời các công cụ tạo localhost khác, khuyến khích gỡ cài đặt trước khi cài XAMPP. Trong quá trình sử dụng, các phần mềm tạo Localhost có thể xung đột với nhau.

+ Nếu dùng Skype
Trong trường hợp máy tính của bạn đang cài Skype, bạn mở Skype -> Tools -> Connection Options -> và bỏ chọn phần “Use port 80 and 443…..” rồi nhập chọn một cổng bất kỳ. Nếu không thực hiện thao tác này, XAMPP sẽ không thể chạy được do cổng mạng 80 đã bị Skype sử dụng.

+ Tắt tường lửa
Bên cạnh đó, bạn cũng nên tắt cài đặt tường lửa trên Windows, cũng như tất cả các phần mềm Antivirus khác, vì những phần mềm này có thể sẽ chặn cổng 80 hoặc các ứng dụng web server, khiến cho XAMPP không thể hoạt động.

+ Tắt UAC Windows
Đặc biệt, người dùng cũng nên tắt User Account Control trên Windows trước đi cài đặt XAMPP để tránh bị giới hạn quyền truy cập.

Cách sử dụng XAMPP cho Windows

+ Khởi động localhost
Sau khi cài đặt XAMPP, người dùng truy cập thư mục c:xampp và mở file xampp-panel.exe để hiển thị bảng điều khiển. Sau đó, nhấp vào nút Start của hai ứng dụng Apache và MySQL để khởi động Webserver. Khi 2 ứng dụng này chuyển sang màu xanh, có nghĩa là localhost đã được khởi động.

#### GIT: <a href="https://git-scm.com/">Git</a>

Vào trang web tải Git chọn mục Downloads > Chọn Tải xuống Git phiên bản phù hợp > Mở file Git chọn Run > Chọn Next > Chọn Browse, chọn nơi cài đặt ấn Next > Chọn Next > Chọn vị trí lưu trên Start Menu, lần lượt chọn Next > Chọn Install > Nhấn Finish.

### Cài đặt

1. Mở VS Code mở vào một thư mục trống rồi clone chương trình xuống: 
  <img src="data_img/step/Step_vsc.png" alt="">

  ```sh
  git clone https://github.com/assassinnyt2811/spam_sms_web.git
  ```

2. Khởi động localhost trong XAMPP

3. Truy cập vào đường dẫn: `http://localhost:8080/phpmyadmin/`
  <img src="data_img/step/step_1.png" alt="">

4. Tạo database với tên: `smsspamproject`
  <img src="data_img/step/step_2.png" alt="">

5. Chọn vào database `smsspamproject`
  <img src="data_img/step/step_3.png" alt="">

6. Chọn vào import rồi lấy file `smsspamproject.sql` trong thư mục clone về ở `Bước 1`. Chọn xong thì kéo xuống chọn `Import`
  <img src="data_img/step/step_4.png" alt="">
  <img src="data_img/step/step_5.png" alt="">

7. Tải các file mô hình và `tfifd` từ link trong file `README.md` trong thư mục `model` và `tfidf`
  <img src="data_img/step/step_5_1.png" alt="">

8. Trong Visual Studio Code mở thư mục vừa clone về
  <img src="data_img/step/step_6.png" alt="">

9. Sau đó mở terminal lên dùng tổ hợp phím "Ctrl + `", rồi chạy từng câu lệnh để cài đặt các thư viện cần thiết
  ```sh
  python -m pip install --upgrade pip
  pip install setuptools wheel
  pip install -r requirements.txt
  ```

10. Để bắt đầu chạy ta chạy dòng lệnh `python spam_sms_web.py` trong terminal
  ```sh
  python spam_sms_web.py
  ```

11. Truy cập trang web: `http://127.0.0.1:5000/login`
    * Tài khoản admin: `admin`
    * Mật khẩu: `admin`

    * Tài khoản user: `user`
    * Mật khẩu: `12345`

12. Bắt đầu sử dụng web

<!-- <img src="data_img/step/step_7.png" alt=""> -->

<p align="right">(<a href="#readme-top">Trở lại đầu trang</a>)</p>

## Cách sử dụng

Cách sử dụng: <a href="https://drive.google.com/file/d/1si1qK1lBTvyVq8LbXgTp1axuBHxAzRdi/view?usp=sharing" >Link hướng dẫn sử dụng</a>

<p align="right">(<a href="#readme-top">Trở lại đầu trang</a>)</p>


## Các hướng đi

- [x] Bước đầu hình thành hướng giải quyết vấn đề liên quan tới việc giải quyết bài toán phân loại tin nhắn rác.
Tiếp cận dữ liệu. Thực hiện tiền xử lý dữ liệu, thống kê các thông tin của dữ liệu phục vụ trực quan dữ liệu, tiến hành phân chia tổ chức lưu trữ dữ liệu tin nhắn trong một cơ sở dữ liệu phục vụ quá trình khai thác lâu dài.

- [x] Nắm được ý tưởng của ba phương pháp giải bài toán phân loại tin nhắn rác được giao đó là Bayesian Belief Network, Classification by Back propagation và Support Vector Machines. Thực hiện chạy huấn luyện các mô hình và kiểm thử với dữ liệu tin nhắn ở các phiên bản khác nhau từ việc xây dựng thủ công tới gọi mô hình.

- [x] Xây dựng thành công mô hình mạng Bayesian Belief Network bằng thủ công một cấu trúc đơn giản phác thảo được ý tưởng của mô hình mạng Bayesian Belief Network đạt độ chính xác cao trên tập dữ liệu chọn.

- [x] Ứng dụng các mô hình học máy vào phục vụ xây dựng công cụ hỗ trợ ra quyết định phân loại tin nhắn rác, tiền đề cho việc hình thành công cụ bán tự động tới tự động phân loại tin nhắn hỗ trợ các khách hàng sử dụng ngăn chặn tin nhắn rác làm phiền và gây hại, hỗ trợ các công ty viễn thông và các cơ quan quản lý áp dụng trong ngăn chặn tình trạng phát tán tin nhắn rác.

- [x] Hoàn thiện sản phẩm dưới dạng công cụ web app, có giao diện trực quan, dễ sử dụng.
Tổng quan toàn bộ quá trình thực hiện các công việc của nhóm đi từ dữ liệu ‘SMS Spam 

- [ ] Sản phẩm có thể tiếp tục đẩy lên dạng web trực tuyến, đưa bộ công cụ tiếp cận với nhiều đối tượng hơn.
Bổ xung thêm cho công cụ khả năng làm việc với nhiều ngôn ngữ không chỉ có tiếng anh mà còn nhận diện được tin nhắn được viết bằng tiếng việt.

- [ ] Làm tính năng chạy huấn luyện mô hình trực tiếp trên tài khoản admin, thay vì việc huấn luyện ngoài rồi đưa file model lên hệ thống dể quản lý phiên bản đơn thuần như hiện nay.

- [ ] Thu thập dữ liệu, phục vụ cho các hoạt động cải thiện mô hình trong các giai đoạn sau.

<p align="right">(<a href="#readme-top">Trở lại đầu trang</a>)</p>

## Nhóm

Các thành viên nhóm:
- Lã Đức Nam (Leader)
- Phạm Hồng Nghĩa
- Dương Văn Nam
- Phạm Như Khoa
- Nguyễn Đình Kiên
- Phạm Quang Nam

Nếu có đề xuất nào có thể cải thiện điều này, vui lòng rẽ nhánh repo và tạo yêu cầu Pull. Đừng quên cho dự án một ngôi sao! Cảm ơn!

1. Rẽ nhánh Project

2. Tạo luồng với tính năng mới mà bạn sẽ thêm (`git checkout -b explore/your_feature`)

3. Commit thay đổi của bạn (`git commit -m 'Thêm một vài module hay ho'`)

4. Đẩy lên luồng của bạn (`git push origin explore/your_feature`)

5. Mở một Pull Request


<p align="right">(<a href="#readme-top">Trở lại đầu trang</a>)</p>

## Liên hệ

Lã Đức Nam - [@laducnam](https://www.linkedin.com/in/l%C3%A3-%C4%91%E1%BB%A9c-nam-9b27b4219/) - ducnamla2@gmail.com

Project Link: [https://github.com/assassinnyt2811/spam_sms_web](https://github.com/assassinnyt2811/spam_sms_web)

<p align="right">(<a href="#readme-top">Trở lại đầu trang</a>)</p>

## Tài nguyên hữu ích

* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)
* [Box Icons](https://boxicons.com/)
* [Flask Document](https://flask.palletsprojects.com/en/2.2.x/)

<p align="right">(<a href="#readme-top">Trở lại đầu trang</a>)</p>


[stars-shield]: https://github.com/assassinnyt2811/spam_sms_web.svg?style=for-the-badge
[stars-url]: https://github.com/assassinnyt2811/spam_sms_web/stargazers
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/l%C3%A3-%C4%91%E1%BB%A9c-nam-9b27b4219/
[product-screenshot]: data_img/Product.png
[python]: https://img.shields.io/badge/python-000000?style=for-the-badge&logo=python&logoColor=bue
[Next-url]: https://www.python.org/
[fontawesome]: https://img.shields.io/badge/fontawesome-000000?style=for-the-badge&logo=fontawesome&logoColor=blue
[fontawesome-url]: https://fontawesome.com/
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[boxicons]: https://img.shields.io/badge/boxicons-35495E?style=for-the-badge&logo=boxicons&logoColor=blue
[boxicons-url]: https://boxicons.com/
[Javascript]: https://img.shields.io/badge/javascript-DD0031?style=for-the-badge&logo=javascript&logoColor=blue
[Javascript-url]: https://www.w3schools.com/js/
[HTML5]: https://img.shields.io/badge/html5-4A4A55?style=for-the-badge&logo=html5&logoColor=red
[HTML5-url]: https://www.w3schools.com/html/
[CSS3]: https://img.shields.io/badge/css3-4A4A55?style=for-the-badge&logo=css3&logoColor=pink
[CSS3-url]: https://www.w3schools.com/css/
[MYSQL]: https://img.shields.io/badge/mysql-0769AD?style=for-the-badge&logo=mysql&logoColor=yellow
[MYSQL-url]: https://www.mysql.com/
[flask]: https://img.shields.io/badge/flask-DD0031?style=for-the-badge&logo=flask&logoColor=3C2A21
[flask-url]: https://flask.palletsprojects.com/en/2.2.x/
[VSCode]: https://img.shields.io/badge/vscode-0769AD?style=for-the-badge&logo=visualstudiocode&logoColor=white
[VSCode-url]: https://code.visualstudio.com/
[XAMPP]: https://img.shields.io/badge/XAMPP-orange?style=for-the-badge&logo=xampp&logoColor=white
[XAMPP-url]: https://www.apachefriends.org/download.html
[GIT]: https://img.shields.io/badge/git-black?style=for-the-badge&logo=git&logoColor=white
[GIT-url]: https://git-scm.com/
