Bối cảnh bài toán:

Một nền tảng bán vé (như Ticketbox, Shopee Event, hoặc VnTicket) cần quản lý:

Người dùng (User): mã người dùng, tên, email, mật khẩu, vai trò (customer, organizer, admin)
Sự kiện (Event): mã sự kiện, tên, mô tả, địa điểm, thời gian bắt đầu – kết thúc, người tổ chức (organizer_id)
Loại vé (TicketType): mã loại vé, tên vé (VIP, Regular...), giá, số lượng tối đa, event_id
Đặt vé (Booking): mã đặt vé, ngày đặt, tổng tiền, trạng thái (pending, paid, canceled)
Chi tiết đặt vé (BookingDetail): số lượng vé, đơn giá, booking_id, ticket_type_id
Thanh toán (Payment): mã thanh toán, phương thức (momo, visa, vnpay), ngày thanh toán, trạng thái, booking_id
Mã giảm giá (Voucher): mã voucher, giá trị giảm, hạn sử dụng, áp dụng cho user_id (hoặc toàn hệ thống)
