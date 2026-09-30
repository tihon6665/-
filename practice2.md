MET 3.

name": "X",
    "id": 2
}

{
    "id": 2,
    "name": "X",
    "username": "Antonette",
    "email": "Shanna@melissa.tv",
    "address": {
        "street": "Victor Plains",
        "suite": "Suite 879",
        "city": "Wisokyburgh",
        "zipcode": "90566-7771",
        "geo": {
            "lat": "-43.9509",
            "lng": "-34.4618"
        }
    },
    "phone": "010-692-6593 x09125",
    "website": "anastasia.net",
    "company": {
        "name": "Deckow-Crist",
        "catchPhrase": "Proactive didactic contingency",
        "bs": "synergize scalable supply-chains"
    }
}

MET4.

{}
200 или 204
{
    "userId": 1,
    "id": 3,
    "title": "ea molestias quasi exercitationem repellat qui ipsa sit aut",
    "body": "et iusto sed quo iure\nvoluptatem occaecati omnis eligendi aut ad\nvoluptatem doloribus vel accusantium quis pariatur\nmolestiae porro eius odio et labore et velit aut"
}
200

MET5.
PUT
{
    "name": "Dup",
    "id": 1
}

{
    "name": "Dup",
    "id": 1
}
POST
"id": 101
"id": 101

MET6.
метод  | безопасен?    | идемпотентен?          | обоснование
GET    |  да           |  да                    | повторное чтение ничего не меняет
POST   |  нет          |  нет                   | два одинаковых запроса создают два ресурса:два нажатия — два заказа
PUT    |  нет          |  да                    | повторная отправка того же тела просто перезаписывает то же состояние
PATCH  |  нет          |  не всегда             | «поле равно значению» идемпотентен, «прибавь десять» — нет
DELETE |  нет          |  да                    | ресурс удалён один раз; повтор получит другой статус, но мир не изменится

MET7.
/api/getUsers действие в: ____ верная пара: ____
/api?action=deleteUser&... действие в: ____ верная пара: ____
/users/5/remove действие в: ____ верная пара: ____
/posts/delete-all
