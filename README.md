# Python_homework_1
Homework Python

1-7. Создание переменных

    int_item = 10
    comp_item = 18
    mult_int = int_item * 2
    item_2 = True
    item_3 = False
    item_4 = 0
    item_5 = 1
8-19. Создание переменных для валют и их курсов

    usd_item = 'usd'
    usd_usd_rate = 1

    eur_item = 'eur'
    usd_eur_rate = 0.86

    uah_item = 'uah'
    usd_uah_rate = 26.23

    chf_item = 'chf'
    usd_chf_rate = 0.91

    rub_item = 'rub'
    usd_rub_rate = 71.88

    byn_item = 'byn'
    usd_byn_rate = 2.46
20. Условие сравнения mult_int и comp_item

        if mult_int > comp_item:
            print("Переменная mult_int больше", comp_item)
21-23. Создание и применение новой переменной div_int и условие сравнения

    div_int = int_item / 2
    if div_int < comp_item:
        print("Переменная div_int меньше", comp_item)
24. Условие сравнения item_1 и comp_item

        item_1 = int_item + 10
        if item_1 < comp_item:
           print("Переменная item_1 меньше", comp_item)
        else:
           print("Переменная item_1 больше или равна", comp_item)
25-28. Условия сравнения для переменных item_2, item_3, item_4, item_5

    print("Переменная item_2 =", item_2 if item_2 else item_3)
    print("Переменная item_3 =", item_2 if item_3 else item_3)
    print("Переменная item_5 =", item_5 if item_5 else item_4)
    print("Переменная item_4 =", item_5 if item_4 else item_4)
29-30. Условие сравнения для переменной currency_convertor

    currency_convertor = item_2
    if currency_convertor:
31. Внутри if currency_convertor

        currency_usd = usd_item
        target_currency = eur_item
        target_currency_amount = 50
        currency_result = 0
31.1-31.7. Вложенные условия для различных валют

    if target_currency == 'eur':
        currency_result = target_currency_amount * usd_eur_rate
        print(target_currency_amount, eur_item, "=", currency_result, usd_item)
    elif target_currency == 'uah':
        currency_result = target_currency_amount * usd_uah_rate
        print(target_currency_amount, uah_item, "=", currency_result, usd_item)
    elif target_currency == 'chf':
        currency_result = target_currency_amount * usd_chf_rate
        print(target_currency_amount, chf_item, "=", currency_result, usd_item)
    elif target_currency == 'rub':
        currency_result = target_currency_amount * usd_rub_rate
        print(target_currency_amount, rub_item, "=", currency_result, usd_item)
    elif target_currency == 'byn':
        currency_result = target_currency_amount * usd_byn_rate
        print(target_currency_amount, byn_item, "=", currency_result, usd_item)
    else:
        print("Unknow currency")
    else:
        print("Переменная currency_convertor =", item_3)
