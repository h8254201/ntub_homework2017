# Controller
  Controller中存在著許多的Action，使用者輸入URL並對照Route找到正確的Action，並將Model處理完的資料傳給View。
# View
  呈現給使用者看的頁面。
# Model
  跟資料庫溝通的地方，例如：資料的新增、修改、刪除、搜尋。
# 流程
  使用者輸入URL後，會先對照Route表並交由Controller找到對應的Action，若URL為正確則導向正確的Action不正確會出現HTTP 404。
  進入Action後會交由Model做資料的處理，例如：搜尋資料…等，待Model處理完後會將處理完的資料丟給Controller/Action，並將他丟給View。
  最後View接到值便呈現給使用者看。
  
