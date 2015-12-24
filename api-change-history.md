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


*from 0.0.7 to 0.0.8 by Charlot
1. add /users/forget_password api
2. add /kpis/unit_of_measurements api
3. add /kpis/calculate_methods api
4. add /kpis/timing_frequencies api

*from 0.0.7 to 0.0.8 by lzding
1. change post /follow_kpi to  post /kpis/follow;
2. change post /unfollow_kpi to  post /kpis/unfollow;
3. change post /user_followed_kpis to  post /kpis/user_followed;
4. change post /kpis/follow api return;
5. change post /kpis/unfollow api return;
6. add /kpis/user_created api
7. change post /kpis/user_followed api return;

*from 0.0.8 to 0.0.9 by Charlot
1. change /full_text_search_users to /search/full_text/users
2. change /full_text_search_departments to /search/full_text/departments
3. change /full_text_search_kpis to /search/full_text/kpis
4. change /full_text_search_follwed_kpis to /search/full_text/followed_kpis
5. change /user_kpis to /kpis/users/accesses
6. change /user_kpi_on_departments to /kpis/departments
7. change /kpi to /kpis
8. change /ser_group_lists to /user_groups
9. change /kpi_details to /kpis/details
10. change post /kpis/user_follwed to post /kpis/users/followed;
11. change post /kpis/user_created to post /kpis/users/created;
12. add assignment_id to object assignment
13. add members to department object
14. add get /user_groups/for_kpis api
15. change /user_group_list to /user_groups
16. change /user_groups return


*from 0.0.9 to 0.0.10 by Charlot
1. remove params user_id from /kpis/users/followed
2. remove params user_id from /kpis/users/created
3. add pagination  to /kpis/users/accesses & /kpis/users/followed & /kpis/users/created
4. add /kpis/assigns api;
5. add /kpis/properties api;
6. add get /kpis/users/followed_details to get show on my kpi page;
7. change get /discussions params discussion_id requires to true;
8. change post /discussions return value;
9. change /discussion_members to /discussions/members api;
10. change /discussion_comments to /discussions/comments api;
11. add get /discussions/list api;
12. add get /discussions/for_users api;
13. change get /user_groups/for_kpis api return value;
14. change get /kpis/users/followed_details api return value;


*from 0.0.10 to 0.0.11 by Charlot
1. add get /tasks/entries/list for get user task list
2. remove post /tasks/user_tasks which use to further assign kpi
3. change /task_items to /tasks/entries/items
4. change post /input_data to post /entries
5. add get /kpis/follows to show on 3.2, and result is same with3.1, so data from 3.1 can use on 3.2
6. add field follow_id  and last_updated_at to object followed_kpi
7. add get /alerts/kpi_follows/latest show on 3.2
8. change /discussions api return value
9. change /discussions/comments api params;
10. change /discussions/comments api return value;
11. change get /discussions/list to /discussions/users/accesses api;
12. change get /discussions/for_users to /discussions/users/created api;

