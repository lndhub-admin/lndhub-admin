<!-- ### Hi there 👋 -->

## LndHub Admin is a Node.js Lightning Network Toolbox

Using LndHub's accounting for 

> #### accounts ( wallets ( users ) ). 

---

This repo will contain 
- Collect HowTo's and Snippets
- Code Repo fo Admin Extension Components
- Documetation "Best Practices" and Deploy for production

---

## The Design of extensions / Extensions

There is a ```/LndHub/extensions/*``` folder where one can extend LndHub and run in same memory area as LndHub,
> #### ```/LndHub/extensions/admin```
> https://github.com/lndhub-admin/LndHub-Admin-Extension

and there is ```/LndHub-Extensions``` that lives outside of the LndHub folder (for babel build reasons) 
invocated in its own memory area while sharing the Redis DB and use API calls to LndHub-Admin core.
> #### ```/LndHub-Extensions/*```



The ```/LndHub-Extensions/*``` can use any Language and Framework while authenticating to LndHub-Admin core API.


 ![LndHub Admin Toolbox](/media/LNHAT-ROUND-libs.png)


TG : https://t.me/joinchat/L31KXn9TlDNmMTY0

<!--
**lndhub-admin/lndhub-admin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
