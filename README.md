username: ligw7
password: Lenovo$1qaz2wsx3edc4
url: https://10.96.160.78/cgi-bh/login.cgi

/data/node_app/ldc.com.cn/github/ldc/backend/nodeapp/ldc.com.cn/
qfDQ-6370


./mongoexport -h 127.0.0.1:27021  -d ldcNetExt -c orders --type=csv -f _id,ip,qr_pay_mode,out_trade_no,buyer_id,productId,total_fee,lanId,adCode,createdAt,trade_no,trade_status  -o a.csv
