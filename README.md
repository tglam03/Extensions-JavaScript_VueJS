# Setting Extensions Vuejs

Truy cập branch `master`  
Cài đặt extensions: Nhập `@recommended` vào input tìm kiếm của extensions sau đó tải tất cả.

## Chú thích setting:
> Chú ý: Extensions **Tailwind Fold** sẽ đóng mở các class. Hãy cài đặt phím tắt phù hợp.

### Cấu hình chi tiết:

- `"css.lint.unknownAtRules": ""`: Kiểm soát cảnh báo cho các quy tắc CSS không xác định.  
- `"editor.codeActionsOnSave": { "source.fixAll": "" }`: Tự động sửa lỗi khi lưu file.  
- `"editor.defaultFormatter": "esbenp.prettier-vscode"`: Đặt formatter mặc định là Prettier.  
- `"editor.scrollbar.vertical": "default"`: Đặt chế độ thanh cuộn dọc về mặc định.  
- `"editor.scrollbar.horizontal": "de"`: **(Có lỗi cú pháp)** thiết lập thanh cuộn ngang không hợp lệ.  
- `"editor.cursorBlinking": "solid"`: Đặt kiểu nhấp nháy của con trỏ thành dạng cố định (solid).  

### Zen Mode (Chế độ Zen)

- `"zenMode.showTabs": "single"`: Hiển thị một tab duy nhất khi ở chế độ Zen.  
- `"zenMode.centerLayout": true`: Bố cục mã nguồn được căn giữa màn hình.  
- `"zenMode.fullScreen": true`: Bật chế độ toàn màn hình trong Zen Mode.  

### Các thiết lập chung của Editor (Trình chỉnh sửa)

- `"workbench.colorTheme": "Tokyo Night"`: Đặt chủ đề màu là Tokyo Night.  
- `"workbench.activityBar.location": "default"`: Để thanh hoạt động (activity bar) ở vị trí mặc định (bên trái).  
- `"workbench.hover.delay": 500`: Đặt độ trễ hiển thị hộp hover (500ms).  
- `"workbench.sash.hoverDelay": 500`: Độ trễ hiển thị điểm điều chỉnh (sash) khi di chuột qua là 500ms.  
- `"workbench.editor.empty.hint": "hidden"`: Ẩn gợi ý khi không có file nào mở.  
- `"workbench.statusBar.visible": true`: Hiển thị thanh trạng thái (status bar).  
- `"workbench.startupEditor": "none"`: Không hiển thị editor khi khởi động.  
- `"workbench.preferredDarkColorTheme": "Tokyo Night"`: Chọn chủ đề tối ưu tiên là Tokyo Night.  
- `"workbench.layoutControl.enabled": true`: Cho phép điều chỉnh bố cục giao diện.  
- `"editor.scrollbar.scrollByPage": true`: Bật chế độ cuộn theo trang.  

### Các thiết lập khác cho Editor

- `"editor.formatOnSave": true`: Tự động định dạng mã nguồn khi lưu file.  
- `"editor.glyphMargin": true`: Hiển thị một vùng bên trái nơi có thể thêm breakpoint khi debug.  
- `"editor.folding": true`: Cho phép thu gọn hoặc mở rộng đoạn mã.  
- `"editor.lineNumbers": "off"`: Tắt hiển thị số dòng trong editor.  
- `"editor.minimap.enabled": true`: Hiển thị sơ đồ nhỏ (minimap) của mã nguồn bên cạnh.  
- `"editor.scrollbar.verticalScrollbarSize": 0`: Ẩn thanh cuộn dọc bằng cách đặt kích thước của nó thành 0.  
- `"editor.scrollbar.horizontalScrollbarSize": 0`: Ẩn thanh cuộn ngang bằng cách đặt kích thước của nó thành 0.  
- `"editor.mouseWheelScrollSensitivity": 1`: Độ nhạy khi cuộn bằng chuột được giữ mặc định.  
- `"editor.fastScrollSensitivity": 1`: Độ nhạy cuộn nhanh khi nhấn giữ Alt (hoặc phím tương ứng).  
- `"editor.smoothScrolling": true`: Bật cuộn mượt khi duyệt qua mã nguồn.  
- `"editor.stickyScroll.enabled": true`: Duy trì hiển thị phần đầu của các khối mã khi cuộn xuống.  
- `"editor.fontFamily": "'CaskaydiaMono Nerd Font Mono'"`: Đặt font chữ cho editor là CaskaydiaMono Nerd Font Mono.  
- `"editor.fontLigatures": true`: Bật tính năng ligatures cho font (biến đổi ký tự đặc biệt như !== thành biểu tượng liền).  
- `"editor.lightbulb.enabled": "off"`: Tắt biểu tượng gợi ý lightbulb khi có đề xuất code actions.  
- `"breadcrumbs.enabled": true`: Bật thanh breadcrumbs giúp điều hướng theo cấu trúc file.  
- `"editor.guides.bracketPairs": "active"`: Hiển thị đường dẫn màu cho dấu ngoặc khớp đang được chọn.  
- `"editor.lineHeight": 2`: Đặt chiều cao dòng là 2px.  
- `"editor.fontWeight": "normal"`: Đặt độ dày font chữ ở mức bình thường.  
- `"editor.guides.indentation": true`: Hiển thị đường dẫn cho các cấp độ thụt lề.  
- `"editor.guides.highlightActiveIndentation": true`: Đánh dấu thụt lề hiện tại.  
- `"editor.wordWrapColumn": 50`: Giới hạn số cột cho mỗi dòng khi bật word wrap.  
- `"editor.wordWrap": "on"`: Bật chế độ tự ngắt dòng khi quá dài.  
- `"editor.renderControlCharacters": true`: Hiển thị các ký tự điều khiển như tab hoặc ký tự đặc biệt.  
- `"editor.accessibilitySupport": "off"`: Tắt hỗ trợ trợ năng tự động.  
