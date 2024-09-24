# social_media_app_data_analysis

## ER Diagram
<img src='./ER Diagram.png' alt='ER Diagram ' />

##Tables

### Users
| id (🔑)|    Username     | Created_at  |
| ------ |:-------------:| -----:|
| 1      | XYZ       | 2024-09-01 23:18:58.148768 |
| 2     | ABC      |   2024-09-01 23:18:58.148768 |
| 3     | MNO      |    2024-09-01 23:18:58.148768 |


### Follow
| follower_id (🗝️)|   followee_id(🗝️)   | Created_at  |
| ------ |:-------------:| -----:|
| 1      | 5       | 2024-09-01 23:18:58.148768 |
| 2     | 9      |   2024-09-01 23:18:58.148768 |
| 3     | 35      |    2024-09-01 23:18:58.148768 |

### Photos
| id (🔑)|    image_url     | user_id(🗝️) | Created_at  |
| ------ |:-------------:| -----:| -----:|
| 1      | http://elijah.biz | 5| 2024-09-01 23:18:58.148768 |
| 2     |   http://elfwehjah.bez   | 6|   2024-09-01 23:18:58.148768 |
| 3     | http://ecusyf.euc     | 9|    2024-09-01 23:18:58.148768 |
