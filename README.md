# OCR_WebService

-----------------------------------------------
Dot net 4.5.1 and Tesseract 3.04
-----------------------------------------------

1. Prepare "Tesseract-OCR\tessdata"
2. PM> Install-Package Tesseract
3. Install "vc_redist.x64.exe" --> VC++ 2015, VCRuntime140.dll
4. Under bin\debug\x64 and debug\x32
    "liblept172.dll" for platform x64
    "libtesseract304.dll"

-----------------------------------------------
TEST
-----------------------------------------------
URL: http://localhost:1058/OCR/PostFile  
-- Use Postman(Tabbed Postman - REST Client, Chrome extension) to send file 
-- Post 1 or more image file(tiff, jpg, png, bmp, ...)
-- Receve extracted text 

