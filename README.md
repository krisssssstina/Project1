money = 100000

per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}

deposit=((money/100*per_cent['ТКБ']), (money/100*per_cent['СКБ']), (money/100*per_cent['ВТБ']), (money/100*per_cent['СБЕР']))

print(list(deposit))

print(max(deposit)) 
