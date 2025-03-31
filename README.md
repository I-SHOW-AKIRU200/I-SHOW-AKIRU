<div align="center">
  <!-- Free Fire Logo (Top - 200px) -->
  <a href="https://github.com/I-SHOW-AKIRU200/I-SHOW-AKIRU">
    <img src="https://raw.githubusercontent.com/I-SHOW-AKIRU200/I-SHOW-AKIRU/main/FREE-FIRE.png" alt="Free Fire Logo" width="200">
  </a>
  
  <br> <!-- Line break between logos -->
  
  <!-- Team Akiru Logo (Bottom - 400px) -->
  <a href="https://github.com/I-SHOW-AKIRU200/I-SHOW-AKIRU">
    <img src="https://raw.githubusercontent.com/I-SHOW-AKIRU200/I-SHOW-AKIRU/main/TEAM-AKIRU.png" alt="Team Akiru Logo" width="400">
  </a>
</div>

<br> <!-- Space before content -->


<!-- Rest of your README content goes here -->

# 🔥 AKIRU API Suite

## 📊 Player APIs

### 1. Player Info
```http
GET https://akiru-info.vercel.app/akiru-info?uid=2206344781&region=ind
```
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
```

### 2. Like System
```http
GET https://akiru-like.vercel.app/like?uid=2206344781&server_name=ind
```
```json
{
  "LikesGivenByAPI": 100,
  "LikesafterCommand": 8681,
  "LikesbeforeCommand": 8581,
  "PlayerNickname": "꧁༒☬Ákhil༒",
  "UID": 5177877011,
  "status": 1
}
```

### 3. Visit Tracker
```http
GET https://akiru-visit.vercel.app/visit?uid=2206344781&region=ind
```
```json
{
  "FailedVisits": 31,
  "PlayerNickname": "꧁༒☬Ákhil༒",
  "SuccessfulVisits": 255,
  "TotalVisits": 286,
  "UID": 2206344781
}
```

## 🛠️ Utility APIs

### 1. Item Info (3 Options)
```http
GET https://free-fire-item-info-api.vercel.app/akiru-items-info?option=1&items=203047001
GET https://free-fire-item-info-api.vercel.app/akiru-items-info?option=2&items=Sandalwood%20Raja%20(Top)
GET https://free-fire-item-info-api.vercel.app/akiru-items-info?option=3&items=Icon_Name_avatar_male_cos_top_woodcrafter
```
```json
[{
  "Icon_Name": "Icon_Name_avatar_male_cos_top_woodcrafter",
  "Icon_URL": "https://item-info-pied.vercel.app/akiru-item-info?item_id=203047001",
  "Item_ID": "203047001",
  "Name": "Sandalwood Raja (Top)"
}]
```

### 2. Rank Info
```http
GET https://akiru.vercel.app/AKIRU-rank-info?uid=2206344781&region=ind
```
```json
{
  "AccountName": "꧁༒☬Ákhil༒",
  "AccountRegion": "IND",
  "BrRankPoint": 3875,
  "Credit": "TEAM-AKIRU",
  "CsRankPoint": "Elite Master 1 Star"
}
```

## 🌍 Web Services

<div align="center">

| Service | URL |
|---------|-----|
| AKIRU AI | [https://akiru-ai.vercel.app/](https://akiru-ai.vercel.app/) |
| Outfit Info | [https://outfit-info-web.vercel.app/](https://outfit-info-web.vercel.app/) |
| Wishlist Manager | [https://wishlist-add-web.vercel.app/](https://wishlist-add-web.vercel.app/) |
| Emote ID Finder | [https://thachmora.site/freefire](https://thachmora.site/freefire) |
| JWT | [https://akiru-jwt.vercel.app/AKIRU-JWT-GENERATOR](https://akiru-jwt.vercel.app/AKIRU-JWT-GENERATOR) |

</div>

## 📜 Credits
All APIs are developed and maintained by **TEAM-AKIRU**  
© 2025 AKIRU Services | [Terms of Service](https://t.me/ishowakiru5)
```
