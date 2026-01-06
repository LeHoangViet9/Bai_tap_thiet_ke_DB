Bối cảnh bài toán:

Ghi lại các giao dịch chi tiêu / thu nhập
Phân loại theo danh mục (Category), ví (Wallet), phương thức thanh toán (Payment_Method)
Theo dõi báo cáo tài chính, ngân sách tháng, và mục tiêu tiết kiệm
 

Các thực thể chính:

User: id, họ tên, email, ngày tạo tài khoản
Wallet: id, tên ví (Tiền mặt, Ngân hàng ACB...), số dư ban đầu, loại tiền tệ, user_id
Category: id, tên danh mục (ăn uống, di chuyển, lương...), loại (thu/chi)
Transaction: id, ngày giao dịch, số tiền, mô tả, loại (thu/chi), wallet_id, category_id, user_id
Budget: id, tháng, năm, giới hạn chi tiêu, user_id, category_id
Goal: id, tên mục tiêu (mua xe, du lịch...), số tiền cần, hạn đạt, user_id
Recurring_Transaction (tuỳ chọn): lưu giao dịch lặp lại hàng tháng (ví dụ: tiền thuê nhà, lương)
