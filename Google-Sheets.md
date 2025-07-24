

***Export any google document as file***
```
http://drive.google.com/uc?export=download&id=1KAv7Iw_lquWYTJIN2SS6q3uqGsdllJv2
```

***Export as Different file types***
```
https://docs.google.com/spreadsheets/d/1C5nA3lcOcpd2l6dBGocGGIzae8_C-JcDpjCklyWJKCw/export?format=pdf&gid=1361613251&range=c1:i54
```

***Export any google document as PDF with formatting***
```
    const pdfUrl = "https://docs.google.com/spreadsheets/d/" + SpreadsheetApp.getActiveSpreadsheet().getId() + 
                 "/export?format=pdf&exportFormat=pdf&gid=" + sheet.getSheetId() + 
                 "&portrait=false&size=A4&top_margin=0.20&bottom_margin=0.20&left_margin=0.20&right_margin=0.20&horizontal_alignment=CENTER";
```

***Direct mail with Subject and Mail Body.***
```
<a href="https://mail.google.com/a/0/mail/?tf=cm&to=abhay.patel@email.com&cc&bcc&su=OSS: Lead Filtration over mail&body&fs=1" target="_blank">abhay.patel@email.com</a>
```

***Geo/IP APIs***
```
#QR Code Generater
http://api.qrserver.com/v1/create-qr-code/?data=HelloWorld!&size=100x100
and
https://quickchart.io/qr?text=http://unmixture.com&caption=My below text&captionFontFamily=mono&captionFontSize=10&centerImageUrl=https://cdn-icons-png.flaticon.com/512/1389/1389234.png&centerImageSizeRatio=0.2&dark=000000&light=ffffff&ecLevel=Q&format=svg%20&

#get Address
https://api.bigdatacloud.net/data/reverse-geocode-client

#Get IP
https://api-bdc.net/data/client-ip

#From Geo-Cordinates
https://api.bigdatacloud.net/data/reverse-geocode-client?latitude=37.42159&longitude=-122.0837&localityLanguage=en
```
