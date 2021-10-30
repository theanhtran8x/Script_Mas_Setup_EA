- Mass_Setup_EA_v0.1.ex4: Dùng để setup EA hàng loạt loạt cho các cặp tiền
- CloseCharts_v0.1.ex4: Dùng để close tất cả các chart đang mở

- Một số input:
   - templates\00.tpl: Đây là template chứa tất cả Indicator và EA. (Có thể tạo file này bằng cách click phải vô chart, chọn Template, Save Template)
   - MQL4\Files\all_symbol.csv: File chứa tất cả các symbol cần chạy (nếu symbol là AUDUSDm hay AUDUSDfx, thì chỉ cần viết AUDUSD trong file all_symbol.csv). Nếu file này không tồn tại thì script sẽ chạy với các cặp tiền trong MarketWatch.
   - Copy file Mass_Setup_EA_v0.1.ex4 vào MQL4\Script

- Cách chạy: Sau khi chuẩn bị xong các input ở trên. Mở 1 chart, click phải vào script Mass_Setup_EA_v0.1.ex4 và chọn Excute on Chart
