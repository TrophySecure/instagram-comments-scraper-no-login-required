[Instagram Comments Scraper No Login Required](https://apify.com/data-slayer/instagram-comments-scraper-no-login-required?fpr=data)

Extract Instagram comments from any public post without authentication. This cookieless scraper enables social media analysts to gather audience sentiment, engagement metrics, and competitive intelligence at scale — no Instagram account required.

## 📺 Video Tutorial: How it Works

[Video](https://www.youtube.com/embed/zdMdCLIkFRg?enablejsapi=1&rel=0)

---

## Inputs

| Field | Type | Description |
| --- | --- | --- |
| postCode | String | Instagram post shortcode, post ID, or full post URL (e.g., "C1AbCdEfGhI" or "[https://www.instagram.com/p/C1AbCdEfGhI/](https://www.instagram.com/p/C1AbCdEfGhI/)") |

## Outputs

**Formats**: JSON, CSV, Excel

**Key Fields**:

- `id` - Unique comment identifier
- `text` - Comment content
- `like_count` - Number of likes on the comment
- `created_at` - Unix timestamp of comment creation
- `is_pinned` - Whether the comment is pinned by the post author
- `is_ranked_comment` - Indicates if the comment is algorithmically ranked
- `mentions` - Array of @mentioned usernames
- `hashtags` - Array of hashtags used in the comment
- `user.id` - Commenter's Instagram user ID
- `user.username` - Commenter's Instagram handle
- `user.full_name` - Commenter's display name
- `user.is_verified` - Verification badge status
- `user.is_private` - Whether the commenter's profile is private
- `user.profile_pic_url` - Profile picture URL

## How to Use

**Step 1**: Enter the Instagram post code, ID, or full URL in the `postCode` input field.

**Step 2**: Configure optional parameters such as maximum comments to extract or sorting preferences.

**Step 3**: Run the scraper and download your data in JSON, CSV, or Excel format for immediate analysis.

## Sample Output

```
[
  {
    "id": "18064427546538949",
    "text": "This is exactly what we needed! 🔥",
    "like_count": 127,
    "created_at": 1765579165,
    "is_pinned": false,
    "is_ranked_comment": true,
    "mentions": [],
    "hashtags": [],
    "user": {
      "id": "57536451028",
      "username": "marketing_pro_2024",
      "full_name": "Sarah Mitchell",
      "is_verified": false,
      "is_private": false,
      "profile_pic_url": "https://scontent-bru2-1.cdninstagram.com/v/t51.2885-19/profile_pic.jpg"
    }
  },
  {
    "id": "17858885652504626",
    "text": "@brandname love this approach! When's the next drop?",
    "like_count": 43,
    "created_at": 1765679459,
    "is_pinned": false,
    "is_ranked_comment": true,
    "mentions": ["@brandname"],
    "hashtags": [],
    "user": {
      "id": "48783447503",
      "username": "tech_enthusiast",
      "full_name": "Alex Chen",
      "is_verified": true,
      "is_private": false,
      "profile_pic_url": "https://scontent-bru2-1.cdninstagram.com/v/t51.2885-19/verified_profile.jpg"
    }
  }
]
```

---

## Key Features

🔒 **Cookieless / No Login Required** - Access public Instagram comment data without authentication, eliminating account suspension risks and credential management overhead.

📈 **Scalable Architecture** - Process thousands of comments from viral posts with enterprise-grade infrastructure designed for high-volume data extraction.

✅ **Rich Comment Data** - Capture complete comment metadata including text, like counts, timestamps, mentions, hashtags, user profiles, verification status, and engagement metrics.

⚡ **Fast & Reliable** - Optimized extraction engine delivers consistent performance with built-in retry logic and error handling for production workflows.

📊 **Export-Ready Formats** - Download structured data in JSON, CSV, or Excel formats for immediate analysis in BI tools, sentiment analysis platforms, or custom dashboards.

## Use Cases

**Social Media Managers**: Monitor brand mentions and audience sentiment across competitor posts to identify trending topics, measure campaign resonance, and respond to customer feedback in real-time.

**Market Research Analysts**: Aggregate thousands of comments from industry influencers to uncover consumer pain points, product preferences, and emerging market trends for strategic planning.

**Growth Marketers**: Analyze engagement patterns on viral content to reverse-engineer successful post strategies, identify high-value audience segments, and optimize content calendars for maximum reach.

## Important Considerations

This scraper works exclusively with public Instagram profiles. Private accounts and restricted content cannot be accessed.

## 🧩 Other Instagram Actors by Data Slayer

| Actor | What it does | Link |
| --- | --- | --- |
| Instagram Followers Scraper | Extract follower lists from any account | [Try it](https://apify.com/data-slayer/instagram-followers-scraper---no-login) |
| Instagram Following Scraper | See who any account follows | [Try it](https://apify.com/data-slayer/instagram-following) |
| Instagram Posts Scraper | Extract posts from any profile | [Try it](https://apify.com/data-slayer/instagram-posts) |
| Instagram Likes Scraper | Extract users who liked any post | [Try it](https://apify.com/data-slayer/instagram-likes) |
| Instagram Reels Scraper | Search and extract Instagram Reels | [Try it](https://apify.com/data-slayer/instagram-search-reels) |
| Instagram Profile Scraper | Get full profile data with contact info | [Try it](https://apify.com/data-slayer/instagram-user-info-scraper-cookieless) |
| Instagram User Search | Search Instagram users by keyword | [Try it](https://apify.com/data-slayer/instagram-search-users) |
| Instagram Hashtag Scraper | Discover hashtags and media counts | [Try it](https://apify.com/data-slayer/instagram-hashtags-scraper-no-login-required) |
| Instagram Location Posts | Extract posts from any location | [Try it](https://apify.com/data-slayer/instagram-location-posts) |

**Need verified emails?** Our [LinkedIn Post Engagers Email Finder](https://apify.com/data-slayer/linkedin-post-to-verified-leads) and [LinkedIn Audience Email Finder](https://apify.com/data-slayer/linkedin-influencer-audience-to-verified-leads) extract verified work emails from LinkedIn engagement data.

## 💬 Feedback and Support

We actively maintain this actor and ship improvements based on user feedback. If you run into any issues or have ideas for new features:

- Create an issue on the Actor's **Issues tab** in Apify Console
- Rate the actor if it helped you — it helps others find it too

We typically respond within 24 hours.

---

---