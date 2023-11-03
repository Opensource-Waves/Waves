<p align="center">
<img alt="Logo Banner" src="https://github.com/Opensource-Waves/Waves/blob/main/github-logo/Frame%205%20(1).png?sanitize=true"/>
<br/>
<br/>

<a href="https://github.com/jellyfin/jellyfin">
<img alt="GPL 2.0 License" src="https://img.shields.io/github/license/jellyfin/jellyfin.svg"/>
</a>
<a href="https://github.com/jellyfin/jellyfin/releases">
<img alt="Current Release" src="https://img.shields.io/github/release/jellyfin/jellyfin.svg"/>
</a>
<a href="https://translate.jellyfin.org/projects/jellyfin/jellyfin-core/?utm_source=widget">
<img alt="Translation Status" src="https://translate.jellyfin.org/widgets/jellyfin/-/jellyfin-core/svg-badge.svg"/>
</a>
<a href="https://dev.azure.com/jellyfin-project/jellyfin/_build?definitionId=29">
<img alt="Azure Builds" src="https://dev.azure.com/jellyfin-project/jellyfin/_apis/build/status/Jellyfin%20Server"/>
</a>
<a href="https://hub.docker.com/r/jellyfin/jellyfin">
<img alt="Docker Pull Count" src="https://img.shields.io/docker/pulls/jellyfin/jellyfin.svg"/>
</a>
<a href="https://opencollective.com/jellyfin">
<img alt="Donate" src="https://img.shields.io/opencollective/all/jellyfin.svg?label=backers"/>
</a>
<a href="https://features.jellyfin.org">
<img alt="Submit Feature Requests" src="https://img.shields.io/badge/fider-vote%20on%20features-success.svg"/>
</a>
<a href="https://discord.gg/HkWFGr4A" Chat on discord>
<img alt="Chat on Discord" src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white"/>
</a>
<a href="https://www.reddit.com/r/jellyfin">
<img alt="Join our Subreddit" src="https://img.shields.io/badge/reddit-r%2Fjellyfin-%23FF5700.svg"/>
</a>
<a href="https://github.com/jellyfin/jellyfin/releases.atom">
<img alt="Release RSS Feed" src="https://img.shields.io/badge/rss-releases-ffa500?logo=rss" />
</a>
<a href="https://github.com/jellyfin/jellyfin/commits/master.atom">
<img alt="Master Commits RSS Feed" src="https://img.shields.io/badge/rss-commits-ffa500?logo=rss" />
</a>
</p>

<div align="center"><a href='https://ko-fi.com/brick_wall' target='_blank'><img height='30' style='border:0px;height:41px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' margin-top="10px" alt='Buy Me a Coffee at ko-fi.com'/></a></div>
<div align="center">A sleek and minimalistic selfhosted web app for streaming your music library on your local network.</div>

#

### 🛠️ Development

```bash
git clone https://github.com/style77/newsltr.git
cd waves
npm run dev
```

#

### Docker Container 📦

You can run the Docker container with the following command, replacing 8080 with the port of your choice:

```bash
docker run -d -p 8080:8080 ghcr.io/opensource-waves/waves
```

#

### 📁 Folder Structure

Currently supports any format supported by the html 5 audio player, with transcoding support to be added in future builds.

#### Template

<pre>
Music Folder/
  ├── Artist/
  │   ├── Album (Year)/
  │   │   ├── 01 - Song.mp3
  │   │   └── 02 - Song.mp3
  │   └── Album (Year)/
  │       ├── 01 - song.mp3
  │       └── 02 - song.mp3
  └── Artist/
      ├── Album (Year)/
      │   ├── 01 - Song.mp3
      │   └── 02 - Song.mp3
      └── Album (Year)/
          ├── 01 - song.mp3
          └── 02 - song.mp3
</pre>

#### Example

<pre>
Music Folder/
  ├── Blur/
  │   ├── The Great Escape (1995)/
  │   │   ├── 01 - Stereotypes.mp3
  │   │   └── 02 - Country House.mp3
  │   └── Modern Life Is Rubbish (1993)/
  │       ├── 01 - For Tomorrow.mp3
  │       └── 02 - Advert.mp3
  └── Pulp/
      ├── Different Class (1995)/
      │   ├── 01 - Mis-Shapes.mp3
      │   └── 02 - Pencil Skirt.mp3
      └── His 'n' Hers (1994)/
          ├── 01 - Joyriders.mp3
          └── 02 - Lipgloss.mp3
</pre>

#


