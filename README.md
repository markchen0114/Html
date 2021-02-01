# Html

Response.ContentType ="application/vnd.ms-excel"

# Javascript
.filter(function (elem, index, self) { return index === self.indexOf(elem); }); //去除重複

//依照Object property排序(遞增)
.sort(function (a, b) {
    let propName = "MstDrugNo";
    return ((a[propName] < b[propName]) ? -1 : ((a[propName] > b[propName]) ? 1 : 0));
});

//safari 回上一頁不會觸發$.ready (back forward cache), 因此在onpageshow時reload
window.onpageshow = function(event) {
 	if (event.persisted) {
       	window.location.reload(); 
   	}
};
