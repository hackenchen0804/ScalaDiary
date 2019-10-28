
* 物料代码输入和调整权限已经分开，在Admin console里面可以控制。
![](financial_enter_and_adjust_stock_seprate_3.0.jpg)

* 可以在需求单中的用户权限设置界面中，使用下划线批量删除一个用户已有的所有权限。
![](financial_del_all_rights_in_requisition_about_one_user_3.0.jpg)

* 可以在物料定义中设置物料的采购税率。
![](financial_purchase_vat_in_stock_level_3.0.jpg)

* 可以在仓库定义中，设置Block参数，禁止任何有关该仓库的交易。
![](financial_block_warehouse_3.0.jpg)

* Cost Type中添加Cost Booking Account,如果设置将覆盖采购分类账中AAS的190项。
![](financial_cost_type_account_specified_3.0.jpg)
![](financial_cost_type_account_specified_override_in_pl_3.0.jpg)

* 系统可以添加发票自定义字段
  1. 打开特殊功能418 - PURCHASE LEDGER - ActivateExtendedUser Defined Field for PL Invoice
  ![](financial_add_field_in_pl_invoice_sf418_3.0.jpg)
  2. 在采购分类账的Codes中，定义添加字段的名称和定义
  ![](financial_add_field_in_pl_invoice_define_sf418_3.0.jpg)
  ![](financial_add_field_in_pl_invoice_define_detail_sf418_3.0.jpg)
  3. 在程序中添加字段内容
  ![](financial_add_field_in_pl_invoice_func_sf418_3.0.jpg)

* 系统可以采购订单行添加自定义字段
  1. 打开特殊功能454 - PURCHASE ORDER -Activate extended user-define fields for purchase order line
  ![](financial_add_field_in_po_line_sf454_3.0.jpg)
  2. 再采购订单的Codes中，定义添加字段的名称和定义
  ![](financial_add_field_in_po_line_define_sf454_3.0.jpg)
  ![](financial_add_field_in_po_line_define_detail_sf454_3.0.jpg)
  3. 在程序中添加字段内容，需要修改order template。
  ![](financial_add_field_in_po_line_func_sf454_3.0.jpg)

* 系统提供参数控制当订单头发货日期更新，明细行中的发货日期是否更新。
  ![](financial_update_delivery_date_3.0.jpg)

* snap search中可以查询新增的用户自定义字段
  ![](financial_snap_search_user_define_field_3.0.jpg)

* 当销售订单状态为8同时打开特殊如功能475 -  SALES ORDER - Print Return Notes时，系统提供Print Return Note打印这些订单，同时在历史中也可以重复打印。
  ![](financial_print_return_notes_3.0.jpg)
  ![](financial_print_return_notes_func_3.0.jpg)
  ![](financial_print_return_notes_func_detail_3.0.jpg)
  ![](financial_print_return_notes_func_history_3.0.jpg)

* 设置各种文档产生文件名的模板,文档列表如下：<br/>
1 - Sales Order Invoice/Credit Note<br/>
2 - Consolidated Sales Order Invoice/Credit Note<br/>
3 - Service Order Invoice/Credit Note<br/>
4 - Purchase Order<br/>
5 - Sales Order Invoice/Credit Note (History)<br/>
6 - Advance Invoice<br/>
7 - Prepayment Invoice<br/>
8 - Consolidated Service Order Invoice/Credit Note<br/>
9 - Contract Invoice/Credit Note<br/>
10 - Consolidated Contract Invoice/Credit Note<br/>
11 - Project Invoice<br/>
12 - Sales Order Quotation<br/>
13 - Sales Order Confirmation<br/>
14 - Sales Order Delivery Note<br/>
15 - Proforma Invoice<br/>
16 - Request for Quotation (PC)<br/>
17 - Reminder Confirmation (PC)<br/>
18 - Reminder Delivery (PC)<br/>
19 - Sales Ledger Statement/Reminder<br/>
20 - Purchase Ledger Statement<br/>
21 - Purchase Ledger Cheque Register<br/>
22 - Purchase Ledger Automatic Payment <br/>
23 - Payment Notification per Supplier<br/>
24 - Interest Invoice<br/>
25 - Consolidated Invoice/Credit Note<br/>
  ![](financial_print_filename_template_func_3.2.jpg)
  ![](financial_print_filename_template_func_detail_3.2.jpg)
  ![](financial_print_filename_template_result_3.2.jpg)

* 采购分类账和销售分类账付款反冲
  ![](financial_sl_pl_paid_reserve_sf487_sf488_3.0.jpg)
  ![](financial_sl_pl_paid_reserve_func_3.0.jpg)
  ![](financial_sl_pl_paid_reserve_func1_3.0.jpg)
  ![](financial_sl_pl_paid_reserve_func_step1_3.0.jpg)
  ![](financial_sl_pl_paid_reserve_func_step2_3.0.jpg)
  ![](financial_sl_pl_paid_reserve_func_step3_3.0.jpg)
