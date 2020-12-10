Notes
CoinMarketCap:
- Free:
    Listings Lastest: cho phép những thông tin mới nhất về cryptocurrencies --> không hữu ích lắm
    
- not Free: 
    OHLCV Historical: Open High Low Close Volume, không free --> xài trang khác
    OHLCV Lastest: không useful lại còn không free
    Quotes Historical: như những trang khác
==> CoinMarketCap gói Basic hầu như không được gì

CoinGecko: Free 
- Lấy được giá của coin so với coin khác
- Lấy được price, market_cap và volume historical (đã test từ tháng 12/2015)
- Giá trị OHLC chỉ lấy được tối đa 1 năm
- Có những API khác nhưng chỉ là bản beta nên không dám dùng

Poloniex: có Public API để lấy data và Private API để trade --> dùng làm bot được
    Dữ liệu được xét theo từng cặp coin
- Có thể lấy được order book, nhưng tối đa chỉ có 100
- Có thể lấy được lịch sử Trade trong 1 khoảng thời gian, nhưng tối đa được 1000
- Lấy được dữ liệu OHLC, có thể tuỳ chỉnh khoảng thời gian của candlestick. Đã chạy thử từ tháng 12/2015, thu được nhiều data hơn so với CoinGecko vì có thể tuỳ chọn khoảng thời gian của candlestick
Phần Private API tạm thời chưa đụng tới.
Có Websocket API để cập nhật data theo thời gian thực

Binance: nhìn phức tạp, nhiều API cho việc quản lý wallet và trading
- Old Trade Lookup: cho phép lấy những lịch sử trade, tối đa 1000
- Candlestick data: cũng tối đa 1000


iexCloud:
- data khủng cỡ Binance, có thể lấy được hầu hết thông tin về stock và công ty của stock đó --> nhiều quá không biết xài cái nào
- OHLC chỉ trả về giá trị trong 1 ngày
- có lươn Technical Indicators
- các thông tin như Cryptocurrency Book hay Quote chỉ cho giá trị trong 1 ngày
- bản Free: 
    + Unlimited Investors Exchange Data --> đọc không hiểu nó là về cái gì
    + Unlimited Sandbox Testing --> free và unlimited, 10 request per second
    + Core Data: Intraday US Stock Price, Historical US Stock Price 5Y, Historical Intl Stock Price 5Y, Earnings last, Dividends last, Splits, Reference Data, Mutual Funds, OTC, News, Crypto --> ghi rõ những gì Free, đỡ mất công tìm như các trang khác.
- Intraday Price: thông tin OHLC, volume, numOfTrade trong ngày --> trong ngày thì không useful
- Historical Price: thông tin OHLC, volume, tối đa 5 năm (Free)
- Splits (Basic): Split Event, những cái last reported chỉ included with paid
- Reference Data: not useful
- Mutual Funds: thông tin về các Mutual Funds, ngoài ra không có data gì hấp dẫn
- OTC: thông tin các OTC
- News: thông tin các bài báo về stocks. historical không available for free
- Crypto: không có historical

- Bản $9/mo thì fully access to Core Data.

MarketStack: giao diện có vẻ rõ ràng hơn
- bản Free chỉ cho truy cập Historical data trong vòng 1 năm
- các field tương tự những trang khác.
- có code hướng dẫn cho các ngôn ngữ

Google Finance: xài được trong GG Sheet
