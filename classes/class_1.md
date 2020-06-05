# Meal

## Attributes
- course (array)
- cost (float)
- is_available (boolean)
- name (string)
- prepare_date (datetime)
- inventory (integer)

## Methods
- senior_discount (change cost by 50% `cost = cost*.50` )
- run_out (changes `is_available = false`)
- new_prep (changes `prepare_date = prepare_date.now`)
- sell (changes `inventory = inventory - 1`)
