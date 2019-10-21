# iScala 3.3 通用设置更新
************************
* iScala中供应商发票长度扩展至25位，更加有利于输入。
![](general_supplier_invoice_length_to_25_3.0.jpg)

* iScala中，如果打开特殊功能426 - Deny Negative Quantity，则系统禁止在除状态为8的销售订单外输入负数数量，这一设置有利于采用条码的公司。
![](general_limit_negative_qty_in_so_with_sp426_3.0f1.jpg)

* 当打开特殊功能422- Posting within transaction时，如果在过账中发生网络或者系统问题，系统会回滚发生错误的交易.
![](general_restore_post_with_error_3.0.jpg)

* 当打开特殊功能424 - Controlled credit order entry和特殊功能322 - Invoice lines history时，credit order只能从已存在的订单里面选取。
![](general_select_negative_qty_from_old_so_3.0f1.jpg)

* 可以在ddf上打印出发票创建日期和时间以及打印份数计数。当打开特殊功能425 - Exclude company data in draft documents,打印草图时不含有数字签名。 
![](general_new_ddf_in_invoice_dn_3.0f1.jpg)

* 通过打开特殊功能429-Protect Orders on Delivery Note或者特殊功能388-Protect Invoiced Order,然后通过Admin console中System Utilities下面的Access to orders printed on delivery note（当打印发货单后，是否可以修改订单）或者Access to invoice orders（当打印发票后，是否可以修改订单）就可以控制。
![](general_limit_adjust_after_dn_or_invoice_3.0f1.jpg)
![](general_limit_adjust_after_dn_detail_3.0f1.jpg)
![](general_limit_adjust_after_invoice_detail_3.0f1.jpg)

* 系统增强GL transaction发生错误（主要是凭证自身问题，如Consolidate Transaction），数据库数据回滚。
![](general_transaction_errors_rollback_3.0f3.jpg)

* 系统增加Audit功能，用于记录字段变化历史的跟踪。
  1. 设置Audit基本参数，包括建立独立的数据库和更新频率。
![](general_create_and_schedule_audit_db_3.2.jpg)
![](general_select_audit_content_3.2.jpg)
  2. 查看Audit结果的3中方法，包括通过字段查询，通过功能查询和通过Admin console查询。
![](general_audit_view_with_field_3.2.jpg)
![](general_audit_view_with_field_detail_3.2.jpg)
![](general_audit_view_with_function_3.2.jpg)
![](general_audit_view_with_function_detail_3.2.jpg)
![](general_audit_view_with_admin_console_3.2.jpg)

* <font color="red">系统增加自动运行功能，包括关闭发票，Post凭证等等。（无License）</font><br/>
![](general_job_schedule_setting_3.3.jpg)
![](general_job_schedule_setting_detail_3.3.jpg)

* 系统增加Epicor Learning Center便于学习
https://erpcustomer.epicor.com

* 系统提供Excel导入功能

![](general_import_with_excel_3.3.jpg)
![](general_import_template_setting_with_excel_3.3.jpg)
