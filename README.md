# qa_guru_pyton_16_hw_5
Домашнее задание к лекции 5 Selene.

В новом проекте, соответствующему базовому формату «проекта для автотестов», разработай автотест на полное заполнение и отправку формы https://demoqa.com/automation-practice-form, а также проверку заполненных данных в поп-апе

Запушь код в github-репозиторий и дай на него ссылку в качестве ответа на домашнее задание.

Условия:
- Библиотеки, разрешенные к использованию: pytest, selene.
- Тест должен жить в своем модуле python 
- Запрещено создавать свои собственные:
- функции
- кроме функции с тестом и опционально функции-фикстуры с настройкой браузера внутри conftest.py
- переменные
- дополнительные python модули кроме модуля с тестом
- кроме опционального conftest.py

Учитывая ограничения, упомянутые выше – постарайся написать максимально читабельный и легкий в последующей поддержке код. В основном это будет касаться именно подбора локаторов для нахождения соответствующих элементов.

Обрати внимание на то, что твоя задача – написать тест, а не скрипт с шагами ;) 

Также, если это твои первые шаги в автоматизации, постарайся максимально симулировать реальные действия пользователя, например при работе с контролом выбора даты рождения – автоматизируй полностью выбор даты, а не просто впиши ее в поле. Это касается и других полей в форме, например селектов (дропдаунов). 

Если тобой уже было реализовано это задание, еще как бонусное задание ко вводному уроку – можешь, наоборот, поменять стратегию, и вместо того чтобы прокликивать дейтпикер – установи значение даты одним махом. Или наоборот, если раньше ты устанавливал одним махом - теперь прокликай. И убедись, что выполнил все условия этой версии задания.

При нарушении любого из условий выше – задание сразу отправляется на переработку. Не спеши делать больше, чем требуется – курс состоит не из одного занятия, а множества, – еще успеешь улучшить решение. Двигаясь по курсу последовательно, ты также помогаешь наставникам более структурно и оптимально передавать тебе знания через ревью, помогая этим себе же ;)

Удачи!

P.S. В трудную минуту подбора селекторов, заглядывай в этот чат с примером поддержки в контексте составления нужного селектора ;)
