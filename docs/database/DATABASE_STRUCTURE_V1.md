# DATABASE STRUCTURE V1

## USERS
- uid
- name
- email
- phone
- profile_image
- wallet_balance

## TOURNAMENTS
- tournament_id
- title
- game_name
- entry_fee
- prize_pool
- slots

## REGISTRATIONS
- registration_id
- tournament_id
- uid
- team_name

## WALLET
- transaction_id
- uid
- amount
- type

## WITHDRAWALS
- withdrawal_id
- uid
- amount
- status
