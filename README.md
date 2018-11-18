# code-vuot-linksvip
Code vượt rút gọn link trong linksvip.net
(Code crosses the shortened link)

javascript: url = document.querySelector("#inputLink").value; var pat = /url=(.*?)&/i; var arr = pat.exec(url); if (arr == null ){ alert("Can not bypass"); } else{ window.location.href = atob(arr[1]); }

# Cách sử dụng:(How to use)
1. Truy cập linksvip.net (access linksvip.net)
2. Dán link cần tải về, nhấn Get link (paste link you need download, click Get link)
3. Nhấn F12, chọn tab console và nhập dòng code trên.(Press key F12 then select tab console, copy and paste the code)
4. Nhấn Enter và tận hưởng :D :D :D (Press Enter and see the result ;)) )
5. Lưu code trên vào thanh dấu trang(bookmarks) để dùng cho tiện :D (Save this code to your bookmarks for convenient)
