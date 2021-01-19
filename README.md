
## users テーブル

| Column     | Type   | Options     |
| --------   | ------ | ----------- |
| email      | string |  not null   |
| password   | string |  not null   |
| name       | string |  not null   |
| profile    | text   |  not null   |
| occupation | text   |  not null   |
| position   | text   |  not null   |



## prototypes テーブル

| Column     | Type   | Options     |
| -----------| ------ | ----------- |
| title      | string | not null    |
| catch_copy | text   | not null    | 
| concent    | text   | not null    |
| image      | Activestorange       |
| user       | references           |





## comments テーブル

| Column    | Type       | Options  |                      
| ------    | ---------- | ---------|
| text      | references | not null |
| user      | references | 
| prototype | references |

