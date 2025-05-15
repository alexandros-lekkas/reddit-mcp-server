# Reddit MCP Server ⚙️

A Model Context Protocol (MCP) that provides tools for fetching and creating Reddit content.

![image](https://github.com/user-attachments/assets/705c63ef-5d3c-4a68-8d3b-18dfda0a29f2)

## 🧑‍💻 About

https://www.linkedin.com/feed/update/urn:li:activity:7328864060534419457/

![image](https://github.com/user-attachments/assets/687e9075-0ea2-4211-a1f2-71af1e6824e4)

## 🔧 Available Tools (Features)

**Read-only Tools (Client Credentials):**

- `get_user_info(username)` - Get detailed user analysis with engagement insights
- `get_top_posts(subreddit, time_filter, limit)` - Get and analyze top posts
- `get_subreddit_stats(subreddit)` - Get comprehensive subreddit analysis
- `get_trending_subreddits()` - Get list of trending subreddits

**Read-write Tools (User Credentials):**

- `create_post(subreddit, title, content, flair, is_self)` - Create an optimized post
- `reply_to_post(post_id, content, subreddit)` - Add a reply with engagement insights
- `reply_to_comment(comment_id, content, subreddit)` - Add a strategic reply

## 📃 Available Commands

- `npm run dev` - Builds and runs inspection server (allows you to test MCP without an agent)
- `npm run build` - Builds the server for production
- `npm run start` - Starts the server in production mode

## 📚 Credits

- Credit goes to the [Python Reddit MCP Server](https://github.com/Arindam200/reddit-mcp) by Arindam200 for the inspiration and implementation of these tools. This repository is, at the moment, simply a Node.js port of the Python implementation.

- Credit goes to [Eugene Sh](https://medium.com/@eugenesh4work/how-to-build-an-mcp-server-fast-a-step-by-step-tutorial-e09faa5f7e3b) for the tutorial on how to build an MCP server (which was used as a reference for this implementation).
