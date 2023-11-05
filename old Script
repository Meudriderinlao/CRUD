function doGet() {
  return HtmlService.createTemplateFromFile('index').evaluate()
  .addMetaTag('viewport', 'width=device-width, initial-scale=1')
  .setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL)
}
function processForm(formObject){
  var ss= SpreadsheetApp.openById('1cZb3yNmSFUpINUdiul4Y_rdFPTsPX-Bkd2YAWKibfqo');
  var ws=ss.getSheets()[0]
  ws.appendRow([
    new Date(),
    formObject.Header,
    formObject.Number,
    formObject.Department,
    formObject.Type,
    formObject.Description1,
    formObject.Sku1,
    formObject.Qty1,
    formObject.Remarks, 

  ]);
}
