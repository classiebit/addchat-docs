# Realtime Notifications

AddChat comes with a custom **Internal** notification system for chatting in realtime. 

<br>

**Internal** notification is a custom real-time notification system built using VueJs, which does not require any additional server setup. It works smoothly behind the scenes.

<br>

**Internal** notification system sends regular `Asynchronous HTTP/S Requests` to the server for getting the latest messages on the fly. For the geeks who wanna know more, it only runs a **single `SELECT`** database query in a **single `Table`** to fetch the latest messages.


>{info} The **total no. of `records`** fetched from **single `SELECT`** query are equal to the **total no. of users chatting simultaneously**.

---

- [Internal Notifications](#Internal-Notifications)


<a name="Internal-Notifications"></a>
## Internal Notifications

Internal notification system fetches the following things in realtime (without page refresh)

1. Latest received messages multiple users
2. Latest messages while user-to-user chatting
3. The message is seen or not

---

>{primary} **Internal** notification system saves **Pusher** monthly subscription fees.

---