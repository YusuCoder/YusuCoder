<!-- header: animated typing line -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=36BCF7&center=true&vCenter=true&width=620&lines=Hi,+I'm+Rustam;L2+Support+Engineer+%40+Uzum+Market;42+Heilbronn+student;I+read+databases+for+a+living;Currently+compiling:+C%2B%2B" alt="typing intro" />
</p>

<!-- intro as a psql session -->
```sql
-- connecting...
rustam=# \conninfo
You are connected to database "life" as user "rustam" on host "tashkent.uz" at port "5432".

rustam=# SELECT name, role, school, based_in, status
rustam-#   FROM developers
rustam-#  WHERE handle = 'YusuCoder';

  name  |            role            |    school    | based_in |            status
--------+----------------------------+--------------+----------+------------------------------
 Rustam | L2 Support Engineer @ Uzum | 42 Heilbronn | Tashkent | learning C++, debugging prod
(1 row)
```

<!-- what I actually do, as a query plan -->
```sql
rustam=# EXPLAIN ANALYZE SELECT * FROM my_day;

 Nested Loop  (cost=0.00..∞ rows=many)
   ->  Seq Scan on jsm_tickets          (filter: status = 'open')
   ->  Index Scan on orders, sellers,
                     payments, inventory (cond: "why is this broken?")
   ->  Hash Join on microservices        (found: root cause)
 Planning Time: 1 coffee
 Execution Time: until it's fixed
```

<!-- side projects, shell-style -->
```console
minishell$ ls -la ~/projects
```

| permissions | project | what it is | lang |
|---|---|---|---|
| `drwxr-xr-x` | [**cub3d**](https://github.com/YusuCoder/cub3d) | Raycasting 3D engine, Wolfenstein-style | C |
| `drwxr-xr-x` | [**minishell**](https://github.com/YusuCoder/minishell) | My own tiny bash — pipes, redirects, signals | C |
| `drwxr-xr-x` | [**portfolio**](https://github.com/YusuCoder/portfolio) | Personal site → [yusucoder.vercel.app](https://yusucoder.vercel.app/) | Web |

<!-- tech stack in one line instead of 10 img tags -->
```console
minishell$ which --all tools
```
<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,java,postgres,mysql,linux,git,firebase,figma,androidstudio&perline=10" alt="stack" />
</p>

<!-- personality, as error output -->
```sql
rustam=# SELECT * FROM schedule WHERE activity = 'rest_day';
ERROR:  relation "rest_day" does not exist
HINT:   You probably meant "gym". Discipline is not optional.
```

<!-- stats -->
<details>
<summary><b>📊 SELECT * FROM github_stats;</b></summary>
<br>
<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=YusuCoder&show_icons=true&theme=tokyonight&hide_border=true" alt="stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YusuCoder&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="top langs" />
</p>
</details>

<!-- contact on exit -->
```sql
rustam=# \q
-- connection closed. open a new one below 👇
```

<p align="center">
  <a href="mailto:ryusupov788@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://t.me/RY00101"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/rustam-yusupov-1b0693226/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://twitter.com/RustamYusupovv"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="https://www.instagram.com/r.ilhomovic/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=YusuCoder&label=rows+fetched&color=36BCF7&style=flat" alt="profile views" />
</p>
