<div>
	<h3>Example 1: "Read the data from an Excel sheet and store it in a MySQL database."</h3>
	<p><a href=""> <b>Download</b> Sample excelsheet format</a></p>

	curl --location 'http://localhost:8080/api/excel/uploadExcel' \
	--header 'Content-Type: multipart/form-data; ' \
	--form 'file=@"/home/root310/Downloads/sample-excel-demo.xlsx"'
</div>


