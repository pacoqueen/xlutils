xlutils
=======

Forked from [http://www.python-excel.org/](https://github.com/python-excel/xlutils)


Sample
------

    from xlutils.xlutils import copy
    from xlwt import xlwt
    from xlrd import xlrd
    wb = copy.copy(xlrd.open_workbook("/tmp/Formulario solicitud crédito.xls", formatting_info = True))
    s = wb.get_sheet(0)
    s
    s.cols
    s.write(2, 0, "TEST TEST TEST")
    wb.save("/tmp/test.xls")


