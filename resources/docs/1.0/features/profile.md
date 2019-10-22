# Profile

--- 

![Addchat User Profile](https://addchat-docs.classiebit.com/images/profile.jpg "Addchat User Profile")

---


AddChat does not modify any of your website's database tables or data. It only fetch `user-id` and `email` from `users` table **(read-only)**. AddChat manages every user info like name, profile picture, online status, etc, in a separate table called `ac_profiles`. In the profile, the user can update-

1. Name
2. Profile picture
3. Online status

---

>{info} As of now, the user `online status` is managed manually by the user. In the next version, it'll gonna be automatic, so that whenever a user comes online the status will be updated automatically.