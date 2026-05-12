# TODO

## Step 1: Reports updates (admin_dashboard.html)
- [ ] Replace current Reports cards with:
  - [ ] Revenue Today
  - [ ] Confirmed check-ins (Today)
  - [ ] Revenue Yesterday
  - [ ] Confirmed check-ins (Yesterday)
  - [ ] Today vs Yesterday Change (% / 📊)
  - [ ] Revenue This Week (Mon–Sun)
  - [ ] Revenue (This Month)
  - [ ] Top Room Type (by revenue (range))

## Step 2: Remove refunds completely (admin_dashboard.html)
- [ ] Remove sidebar “Refund Requests”
- [ ] Remove adminRefunds section
- [ ] Remove refund-related functions (renderRefundsPanel/approveRefund/markRefunded/renderRefundStatusPill)
- [ ] Remove refund calls from showAdminSection/deleteBooking/deleteUser
- [ ] Update viewBookingDetails() + generateReport() to remove refund lines

## Step 3: Remove refunds completely (index.html)
- [ ] Remove Manage → Refunds tab
- [ ] Remove requestManageRefund() and all refund rendering
- [ ] Update cancellation flow to not create refundStatus

## Step 4: Validate
- [ ] Open admin_dashboard.html and verify Reports + no refunds UI
- [ ] Open index.html (customer) and verify no refunds UI

