# ROKO 4 EVER - Database Collections

## users
- uid
- name
- email
- mobile
- game_uid
- wallet_balance

## tournaments
- tournament_id
- title
- entry_fee
- prize_pool
- room_id
- room_password
- status

## joins
- join_id
- uid
- tournament_id
- joined_at

## wallet_transactions
- transaction_id
- uid
- amount
- type
- status

## results
- result_id
- tournament_id
- uid
- rank
- prize_amount
