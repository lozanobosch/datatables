# FM CAAS datatables 
Filemaker CaaS ( Code as a Service) Proof of Concept 

```
# cleanup rev
Changed db init script lin 14, to point to the forked version

Let(
	_baseurl = "https://raw.githubusercontent.com/fsans/datatables/main/";

	List (
		_baseurl & "1_template.txt";
		_baseurl & "2_app.txt";
		_baseurl & "3_fmapi.txt";
		_baseurl & "4_css.txt";
		_baseurl & "5_libs.txt";
		_baseurl & "6_data.txt";
		_baseurl & "9_sprite.txt"
	)
)
