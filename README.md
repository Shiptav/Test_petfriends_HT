# Test_petfriends_HT

1	Проверяем что запрос api ключа c неправильным логин и паролем возвращает статус 403	/api/key

2	Проверяем что запрос api ключа c неправильным  password возвращает статус код 403	/api/key

3	Проверяем что запрос api ключа c неправильным  email возвращает статус код 403	/api/key

4	Проверяем что запрос питомцев с неправильным ключем возвращает статус код 403	get/api/pets

5	Проверяем что работает запрос питомцев когда filter = my_pets статус код 200	get/api/pets

6	Проверяем что нельзя добавить питомца с некорректными данными возраст код 400	post/api/pets	баг

7	Проверяем что нельзя добавить питомца с неправильным ключем возвращает статус код 403	post/api/pets

8	Проверяем что можно добавить питомца простым способом без фото (описан метод) статус код 200	/api/create_pet_simple

9	Проверяем возможность что можно добавить фото питомца  (описан метод) статус код 200	/api/pets/set_photo/{pet_id}

10	Проверяем что нельзя добавить фото питомца если данные о фото неправильные статус код 400	/api/pets/set_photo/{pet_id}	баг

![image](https://user-images.githubusercontent.com/119760330/225447270-81856699-698e-44fc-a68d-96b286ef94d7.png)

