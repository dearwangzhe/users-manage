// 获取所有用户信息
http://localhost:3000/users

//获取id为1的用户信息
http://localhost:3000/users/1

//获取公司的所有信息
http://localhost:3000/companies

//获取所有公司id为1的用户
http://localhost:3000/companies/1/users

//根据公司名字获取信息
http://localhost:3000/companies?name=Apple

//根据多个名字获取公司信息
http://localhost:3000/companies?name=Apple&name=Microsoft

//获取一页中只有两条数据
http://localhost:3000/companies?_page=1&_limit=2


//升序排序 asc  desc降序
http://localhost:3000/companies?_sort=name&_order=asc

//获取年龄为18和18以上的
http://localhost:3000/users?age_gte=18

//获取年龄在15和16之间的
http://localhost:3000/users?age_gte=15&age_lte=16

//搜索用户信息  Herry
http://localhost:3000/users?q=h

