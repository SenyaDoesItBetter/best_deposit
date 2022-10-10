# best_deposit
per_cent = {'ТКБ': 5.6,
            'СКБ': 5.9,
            'ВТБ': 4.28,
            'СБЕР': 4.0}
money = int(input())
mp = max(per_cent.values())
best = money * mp / 100
print("Максимальная сумма, которую вы можете заработать - " + str(best))
