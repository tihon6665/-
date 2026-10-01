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
/api/getUsers действие в: нарушенный, верно /api/Users
/api?action=deleteUser&: верно
/users/5/remove действие в: верно
/posts/delete-all: верно

MET8.
на веб версии не открывается терминал

MET9.
на веб версии не открывается терминал

MET10.
{
    "name": "X",
    "id": 101
}

{
    "id": 101
}

MET11.
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 3.2 Final//EN">
<title>405 Method Not Allowed</title>
<h1>Method Not Allowed</h1>
<p>The method is not allowed for the requested URL.</p>

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 3.2 Final//EN">
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try
    again.</p>
оба не прошли

MET12.
A:0
B:2
3:3


