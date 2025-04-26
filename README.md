# 🚀 Impulsiona Aí - A Kwai API

Access public social data from Kwai easily with the **Impulsiona Aí API**.  
Search for users, explore posts, track hashtags, discover music, and monitor trends — all from a single powerful REST API!

🌐 [Access it on RapidAPI →](https://rapidapi.com/contato-zE4IVOM1K/api/kwai6)

---

## 📚 About the API

The **Impulsiona Aí** provides a complete suite of endpoints to interact with publicly available Kwai data.  
You can retrieve profiles, posts, followers, comments, trending hashtags, topics, and music information.

This API is ideal for:
- Trend analysis platforms
- Social media dashboards
- Content aggregation apps
- Research and data mining

---

## 🚀 Getting Started

### 1. Subscribe to the API
Go to the [RapidAPI Hub](https://rapidapi.com/contato-zE4IVOM1K/api/kwai6) and subscribe to the API.

### 2. Obtain Your API Key
After subscribing, retrieve your `X-RapidAPI-Key` and `X-RapidAPI-Host` from the dashboard.

### 3. Make Requests
Use the API Key to authenticate all your requests.

---

## 💻 Example Request (cURL)

```bash
curl --request GET \
  --url 'https://kwai6.p.rapidapi.com/getProfileByUserId?userId=0' \
  --header 'X-RapidAPI-Key: apiKey' \
  --header 'X-RapidAPI-Host: kwai6.p.rapidapi.com'
```

## ✨ Key Features
- Search users, posts, hashtags, and music.
- Retrieve user profiles, followers, and following lists.
- Fetch comments and post engagement data.
- Discover trending music and social content.
- Monitor real-time trending topics.

## 📖 Common Use Cases
- Get detailed user profile information by user ID.
- Retrieve lists of posts from specific users.
- Search for and analyze trending hashtags and music.
- Collect comments from a particular post.
- Explore and monitor trending topics and popular content on Kwai.

## 📝 Notes
- All endpoints operate via GET requests.
- Pagination supported through count and pcursor query parameters.
- API Key authentication required (X-RapidAPI-Key and X-RapidAPI-Host headers).

## 📩 Need Help?
If you encounter any issues or need assistance, feel free to contact us through RapidAPI's messaging system.

## 📄 License
This project is licensed under the [MIT License](https://github.com/impulsionaai/kwai/blob/main/LICENSE).
