# iScala 3.3 库存设置更新
************************
* 在导入转仓交易时，添加了内部交易号。
  ![](stock_add_internal_delivery_note_in_import_transfer_3.0sfp1.jpg)

* 提供新的特殊功能,纠正SC03，SC33与SC07数量差异（特别注意为数量差异，金额差异不被纠正）
  ![](stock_correct_sc33_sc07_diff_sdf50_3.0sfp1.jpg)
  ![](stock_correct_sc33_sc07_diff_sdf50_detail_3.0sfp1.jpg)
  ![](stock_correct_sc33_sc07_diff_sdf50_report_3.0sfp1.jpg)

* 当删除物料代码时，可以同时删除物料库存交易。
  ![](stock_del_stock_transaction_at_stock_item_delete_3.0sfp3.jpg)

* 内部交易号增加到9位，对于条码转仓交易的限制，基本不太可能发生。
  ![](stock_int_dn_length_add_to_9_3.0sfp3.jpg)

* 提供导入客户价格的功能。
  ![](stock_import_customer_price_3.3.jpg)
