Python版本：
Python 2.7

Python模块安装：
- OpenPyXL [ https://pypi.python.org/pypi/openpyxl ][1]
- Connector/Python [https://dev.mysql.com/downloads/connector/python/][2]

脚本调用命令：
	$ python /path/to/parse_gift_excel.py /path/to/example.xlsx

其他：
- 该脚本目前只支持Excel 2010（后缀名为xlsx），如果是老版本（如Excel 1997/2003/2007），请先转化为2010版本。
- Excel表格请严格按照模板来配置
- Excel单元格（数据部分）不可以留空

[1]:	https://pypi.python.org/pypi/openpyxl
[2]:	https://dev.mysql.com/downloads/connector/python/