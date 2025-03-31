<div align="center">
  <!-- Free Fire Logo (Top) -->
  <img src="https://raw.githubusercontent.com/I-SHOW-AKIRU200/I-SHOW-AKIRU/main/FREE-FIRE.png" width="200" alt="Free Fire Logo">
  
  <!-- Team Akiru Logo (Bottom) -->
  <img src="https://raw.githubusercontent.com/I-SHOW-AKIRU200/I-SHOW-AKIRU/main/TEAM-AKIRU.png" width="400" alt="Team Akiru Logo">
</div>

# AKIRU API Documentation

## 🌐 Core APIs

### 1. Player Info API
```http
GET https://akiru-info.vercel.app/akiru-info?uid=2206344781&region=ind

RESPONSE
```json
{
  "credits": "TEAM-AKIRU",
  "data": {
    "Guild": {
      "id": 3035617054,
      "leader": {
        "BannerID": 901026013,
        "account_created": "2019-06-25 06:33:45",
        "booyah_pass_level": 137,
        "id": 1136891304,
        "level": 69,
        "name": "E R O S !!"
      },
      "level": 7,
      "members_count": 55,
      "name": "SUPREME'S !!"
    },
    "basic_info": {
      "AccountEXP": 2351766,
      "AccountType": 1,
      "AvatarID": 902048008,
      "BRRank": 323,
      "BadgeCount": 108,
      "BadgeID": 1001000082,
      "BannerID": 901026013,
      "BrRankPoint": 4752,
      "DiamondValue": 390,
      "Liked": 20583,
      "RankSeason": 44,
      "Region": "IND",
      "TitleID": 904590058,
      "account_created": "2020-07-22 13:59:45",
      "bio": "[FFB900][b] ㅤ ✿ ㅤ ♬ ㅤ ☯︎ [/b][c]\n     999ㅤ999ㅤ999",
      "id": "2206344781",
      "level": 68,
      "name": "꧁༒☬Ákhil༒"
    }
  },
  "status": "success"
}

```http
GET https://akiru-like.vercel.app/like?uid=2206344781&server_name=ind

RESPONSE
```json
{
  "LikesGivenByAPI": 100,
  "LikesafterCommand": 8681,
  "LikesbeforeCommand": 8581,
  "PlayerNickname": "꧁༒☬Ákhil༒",
  "UID": 5177877011,
  "status": 1
}

```http
GET https://akiru-spam.vercel.app/spam-request?uid=2206344781&region=ind

RESPONSE
```json
{
  "nickname": "꧁༒☬Ákhil༒",
  "success": 100,
  "failed": 8,
  "total": 108,
  "status": 1
}

```http
# Option 1 (By Item ID)
GET https://free-fire-item-info-api.vercel.app/akiru-items-info?option=1&items=203047001

# Option 2 (By Item Name - URL Encoded)
GET https://free-fire-item-info-api.vercel.app/akiru-items-info?option=2&items=Sandalwood%20Raja%20(Top)

# Option 3 (By Icon Name)
GET https://free-fire-item-info-api.vercel.app/akiru-items-info?option=3&items=Icon_Name_avatar_male_cos_top_woodcrafter

RESPONSE
```json
[{
  "Icon_Name": "Icon_Name_avatar_male_cos_top_woodcrafter",
  "Icon_URL": "https://item-info-pied.vercel.app/akiru-item-info?item_id=203047001",
  "Item_ID": "203047001",
  "Name": "Sandalwood Raja (Top)"
}]


