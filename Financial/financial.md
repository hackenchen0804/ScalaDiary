
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
