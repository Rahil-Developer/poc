<div>
	<h3>Example 1: "Read the data from an Excel sheet and store it in a MySQL database."</h3>
	<p><a href="https://github.com/Rahil-Developer/poc/blob/main/samplefiles/sample-excel-demo.xlsx"> <b>Download</b> Sample excelsheet format</a></p>

	curl --location 'http://localhost:8080/api/excel/uploadExcel' \
	--header 'Content-Type: multipart/form-data; ' \
	--form 'file=@"/home/root310/Downloads/sample-excel-demo.xlsx"'
	
	curl --location --request GET 'http://localhost:8080/api/excel/downloadExcel' \
	--header 'Content-Type: multipart/form-data; ' \
	--form 'file=@"/home/root310/Downloads/Logical Reasoning - Beginner.xlsx"'
</div>


