*from 0.0.5 to 0.0.6 by Charlot
1. change /users/brief_info to /users/brief_infos;
   add paginate params;
   change return department from single object to object array;
2. change get /users_infos to /users/infos
3. disable post /users/infos (which use to create user)
4. change put /users/infos
5. change post /set_passport to  post /users/set_password;
   change parameter new_password from optional to required;
   change code from 200 to 201
6. change /user_departments to /users/departments
7. change /department_members to /departments/members
8. change /set_department_manager to /departments/set_manager
9. add post&put&delete /departments to create&upate&delete department
10. add post /departments/add_users to add department users
11. add post /departments/remove_user to remove user from department
12. add post /departments/remove_manager to remove department manager


*from 0.0.6 to 0.0.7 by Charlot
1. add /users/forget_password api
2. add /kpis/unit_of_measurements api
3. add /kpis/calculate_methods api
4. add /kpis/timing_frequencies api

*from 0.0.7 to 0.0.8 by lzding
1. change post /follow_kpi to  post /kpis/follow;
2. change post /unfollow_kpi to  post /kpis/unfollow;
3. change post /user_followed_kpis to  post /kpis/user_followed;
1. change post /kpis/follow api return;
2. change post /kpis/unfollow api return;
