# My Video World 🤩🌍 — beginner website

This is a simple responsive personal video website. It includes a homepage, featured video, categories, search, video cards, and a popup video player.

## Preview it on your computer
1. Download and unzip `my_video_world_website.zip`.
2. Open the folder.
3. Double-click `index.html`. It should open in your browser.
4. An internet connection is needed for the remote photos, font, and embedded YouTube videos.

## Add your own videos
1. Open `script.js` in a text editor.
2. Find the `const videos = [` section near the top.
3. Each video is an object with `title`, `category`, `id`, `image`, `views`, and `date`.
4. Replace the sample title with your title.
5. Set `id` to the YouTube video ID. For a link like `https://www.youtube.com/watch?v=AbCdEf12345`, the ID is `AbCdEf12345`.
6. You can use a thumbnail image URL in `image`, or leave a sample image temporarily.
7. Save the file and refresh `index.html`.

Example:
{
  title: "My First Video",
  category: "Vlogs",
  id: "YOUR_YOUTUBE_VIDEO_ID",
  image: "https://example.com/your-thumbnail.jpg",
  views: "New upload",
  date: "Today"
}

Use a category such as `Vlogs`, `Travel`, `Education`, `Gaming`, `Tech`, or `Food`. You can add more categories in `index.html` and matching videos in `script.js`.

## Publish it online for free
A beginner-friendly option is GitHub Pages:
1. Create/sign in to a GitHub account.
2. Create a new public repository named `my-video-world`.
3. Upload `index.html`, `style.css`, and `script.js` to the repository root.
4. Open the repository's Settings → Pages.
5. Under the build/deployment section, choose deploy from the `main` branch and the root folder, then save.
6. GitHub will show the public website URL when publishing is ready.

## Important notes
- This first version is a static website. It does not have a private admin panel or a form to upload video files directly.
- Videos are embedded from YouTube. To add a video, edit `script.js` and use its YouTube ID.
- If you want to upload large video files directly to your own website, you'll need video storage and a backend/service. That can cost money and needs extra setup.
- Only add videos you own or have permission to share. Check the privacy settings of any video you embed.
