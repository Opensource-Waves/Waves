<p align="center">
<img alt="Logo Banner" src="https://github.com/Opensource-Waves/Waves/blob/main/github-logo/Frame%205%20(1).png?sanitize=true"/>
<br/>
<br/>

<a href="https://github.com/jellyfin/jellyfin">
<img alt="GPL 2.0 License" src="https://img.shields.io/github/license/jellyfin/jellyfin.svg"/>
</a>
<a href="https://ko-fi.com/brick_wall">
<img alt="Support" src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white"/>
</a>
<a href="https://hub.docker.com/r/jellyfin/jellyfin">
<img alt="Docker Pull Count" src="https://img.shields.io/docker/pulls/jellyfin/jellyfin.svg"/>
</a>
<a href="https://discord.gg/HkWFGr4A" Chat on discord>
<img alt="Chat on Discord" src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white"/>
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


