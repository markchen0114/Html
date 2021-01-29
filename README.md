# Html

Response.ContentType ="application/vnd.ms-excel"

# Javascript
.filter(function (elem, index, self) { return index === self.indexOf(elem); }); //去除重複

//依照Object property排序(遞增)
.sort(function (a, b) {
    let propName = "MstDrugNo";
    return ((a[propName] < b[propName]) ? -1 : ((a[propName] > b[propName]) ? 1 : 0));
});
