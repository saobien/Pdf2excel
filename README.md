# Pdf2excel
PDF to Excel
Chuyển file Pdf dạng bảng thành file Excel
########################################
+ Install thư viện hỗ trợ:
    pip install -r requirements.txt
+ Install ghostscript:
    Vào trang https://ghostscript.com/releases/gsdnld.html
+ if code error with encoding = "utf-8" and save, please open ...site-packages\camelot\core.py and edit line 751 and 752:
#                table.df.to_excel(writer, sheet_name=sheet_name)
#            writer.book.save(filepath)
