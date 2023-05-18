<div align="right">
  <!-- Language: -->
  <a title="Chinese" href="../README.md">简体中文</a> | <a title="English" href="README_en.md">日本語</a> | <a title="Japanese" href="README_ja.md">日本語</a> | Viet Nam
</div>
<h1 align="center">川虎 Chat 🐯 Chuanhu Chat</h1>
<div align="center">
  <a href="https://github.com/GaiZhenBiao/ChuanhuChatGPT">
    <img src="https://user-images.githubusercontent.com/70903329/227087087-93b37d64-7dc3-4738-a518-c1cf05591c8a.png" alt="Logo" height="156">
  </a>
<p align="center">
    <h3>Giao diện Web UI nhẹ nhàng và thân thiện người dùng cho LLM bao gồm ChatGPT/ChatGLM/LLaMA</h3>
    <p align="center">
      <a href="https://github.com/GaiZhenbiao/ChuanhuChatGPT/blob/main/LICENSE">
        <img alt="Tests Passing" src="https://img.shields.io/github/license/GaiZhenbiao/ChuanhuChatGPT" />
      </a>
      <a href="https://gradio.app/">
        <img alt="GitHub Contributors" src="https://img.shields.io/badge/Base-Gradio-fb7d1a?style=flat" />
      </a>
      <a href="https://t.me/tkdifferent">
        <img alt="GitHub pull requests" src="https://img.shields.io/badge/Telegram-Group-blue.svg?logo=telegram" />
      </a>
      <p>
        Streaming / Các cuộc trò chuyện không giới hạn / Lưu lại lịch sử / Mẫu gợi ý sẵn có / Trò chuyện với tệp tin / Tìm kiếm web <br />
        Hiển thị LaTeX / Hiển thị bảng / Tô sáng mã <br />
        Chế độ tối tự động / Giao diện web linh hoạt / Giao diện giống WeChat <br />
        Điều chỉnh nhiều thông số / Hỗ trợ nhiều khóa API / Hỗ trợ nhiều người dùng <br />
        Tương thích với GPT-4 / Triển khai cục bộ cho LLM
      </p>
      <a href="https://www.youtube.com/watch?v=MtxS4XZWbJE"><strong>Video hướng dẫn</strong></a>
        ·
      <a href="https://www.youtube.com/watch?v=77nw7iimYDE"><strong>Giới thiệu phiên bản 2.0</strong></a>
        ·
      <a href="https://www.youtube.com/watch?v=x-O1jjBqgu4"><strong>Giới thiệu & Hướng dẫn phiên bản 3.0</strong></a>
	||
      <a href="https://huggingface.co/spaces/JohnSmith9982/ChuanhuChatGPT"><strong>Thử nghiệm trực tuyến</strong></a>
      	·
      <a href="https://huggingface.co/login?next=%2Fspaces%2FJohnSmith9982%2FChuanhuChatGPT%3Fduplicate%3Dtrue"><strong>Triển khai một cú nhấp chuột</strong></a>
    </p>
    <p align="center">
      <img alt="Animation Demo" src="https://user-images.githubusercontent.com/51039745/226255695-6b17ff1f-ea8d-464f-b69b-a7b6b68fffe8.gif" />
    </p>
  </p>
</div>

## Gợi ý sử dụng

- Để kiểm soát ChatGPT tốt hơn, hãy sử dụng "System Prompt" (Lời gợi từ hệ thống).
- Để sử dụng "Prompt Template" (Mẫu gợi ý), hãy chọn tệp "Prompt Template Collection" (Bộ sưu tập Mẫu gợi ý) trước, sau đó chọn một gợi ý cụ thể từ menu thả xuống.
- Để thử lại nếu phản hồi không đạt yêu cầu, hãy sử dụng nút` 🔄 Regenerate` (Tạo lại).
- Để bắt đầu một dòng mới trong ô nhập, nhấn phím <kbd>Shift</kbd> + <kbd>Enter</kbd>.
- Để chuyển đổi nhanh giữa lịch sử đầu vào, nhấn phím <kbd>↑</kbd> và <kbd>↓</kbd> trong ô nhập.
- Để triển khai chương trình lên máy chủ, đặt `"server_name": "0.0.0.0", "server_port" <số cổng của bạn>,` trong tệp `config.json`.
- Để nhận một liên kết chia sẻ công khai, đặt "share": true, trong tệp config.json. Lưu ý rằng chương trình phải đang chạy để có thể truy cập qua liên kết công khai.
- Để sử dụng nó trong không gian Hugging Face: Đề nghị **Sao chép Không gian** và chạy chương trình trong Không gian riêng của bạn để có trải nghiệm nhanh hơn và an toàn hơn.
- 
## Quickstart

```shell
git clone https://github.com/GaiZhenbiao/ChuanhuChatGPT.git
cd ChuanhuChatGPT
pip install -r requirements.txt
```

Sau đó, tạo một bản sao của config_example.json, đổi tên thành config.json, và sau đó điền API-Key của bạn và các cài đặt khác trong tệp.

```shell
python ChuanhuChatbot.py
```

Một cửa sổ trình duyệt sẽ mở ra và bạn sẽ có thể trò chuyện với ChatGPT.

> **Ghi chú**
> 
> Vui lòng kiểm tra trang wiki của chúng tôi để biết hướng dẫn chi tiết.

## Khắc phục sự cố
Khi gặp sự cố, bạn nên thử kéo thủ công các thay đổi mới nhất của dự án này trước. Các bước thực hiện như sau:

1. Tải xuống bản ghi mã mới nhất bằng cách nhấp vào `Download ZIP` trên trang web, hoặc
```shell
git pull https://github.com/GaiZhenbiao/ChuanhuChatGPT.git main -f
```
2. Thử cài đặt các phụ thuộc lại (vì dự án này có thể đã giới thiệu các phụ thuộc mới)
```
pip install -r requirements.txt
```
3. Cập nhật Gradio
```
pip install gradio --upgrade --force-reinstall
```

Nói chung, bạn có thể giải quyết hầu hết các vấn đề bằng cách làm theo các bước này.

Nếu vấn đề vẫn tồn tại, vui lòng tham khảo trang này: Câu hỏi thường gặp (FAQ)

Trang này liệt kê gần như tất cả các vấn đề và giải pháp có thể. Vui lòng đọc kỹ nó
Trang này liệt kê gần như tất cả các vấn đề và giải pháp có thể. Vui lòng đọc kỹ nó.

## Thêm thông tin
Thêm thông tin có thể được tìm thấy trong [wiki](https://github.com/GaiZhenbiao/ChuanhuChatGPT/wiki) của chúng tôi:

- [Cách đóng góp một bản dịch](https://github.com/GaiZhenbiao/ChuanhuChatGPT/wiki/Localization)
- [Cách đóng gópn](https://github.com/GaiZhenbiao/ChuanhuChatGPT/wiki/贡献指南)
- [Cách trích dẫn dự án này](https://github.com/GaiZhenbiao/ChuanhuChatGPT/wiki/使用许可#如何引用该项目)
- [Nhật ký thay đổi dự án](https://github.com/GaiZhenbiao/ChuanhuChatGPT/wiki/更新日志)
- [Giấy phép dự án](https://github.com/GaiZhenbiao/ChuanhuChatGPT/wiki/使用许可)
- 
## Biểu đồ Starchart

[![Star History Chart](https://api.star-history.com/svg?repos=GaiZhenbiao/ChuanhuChatGPT&type=Date)](https://star-history.com/#GaiZhenbiao/ChuanhuChatGPT&Date)

## Người đóng góp
<a href="https://github.com/GaiZhenbiao/ChuanhuChatGPT/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=GaiZhenbiao/ChuanhuChatGPT" />
</a>

## Nhà tài trợ

🐯 Nếu bạn thấy dự án này hữu ích, hãy cân nhắc mua cho tôi một lon coca hoặc một tách cà phê~

<a href="https://www.buymeacoffee.com/ChuanhuChat" ><img src="https://img.buymeacoffee.com/button-api/?text=Mua cho tôi một cốc cà phê&emoji=&slug=ChuanhuChat&button_colour=219d53&font_colour=ffffff&font_family=Poppins&outline_colour=ffffff&coffee_colour=FFDD00" alt="Mua cho tôi một cốc cà phê" width="250"></a>

<img width="250" alt="image" src="https://user-images.githubusercontent.com/51039745/226920291-e8ec0b0a-400f-4c20-ac13-dafac0c3aeeb.JPG">
