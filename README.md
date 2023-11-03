<p align="center">
<img alt="Logo Banner" src="https://github.com/Opensource-Waves/Waves/blob/main/github-logo/Frame%205%20(1).png?sanitize=true"/>
<br/>
<br/>


<a href="https://ko-fi.com/brick_wall">
<img alt="Support" src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white"/>
</a>
<a href="https://hub.docker.com/repository/docker/greenestgoat/opensource-waves/">
<img alt="Docker" src="https://camo.githubusercontent.com/6b7f701cf0bea42833751b754688f1a27b6090fdf90bf2b226addff01be817f0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f636b65722d2532333064623765642e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d646f636b6572266c6f676f436f6c6f723d7768697465"/>
</a>
<a href="https://discord.gg/HkWFGr4A" Chat on discord>
<img alt="Chat on Discord" src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white"/>
</a>
</p>

<!--<div align="center"><a href='https://ko-fi.com/brick_wall' target='_blank'><img height='30' style='border:0px;height:41px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' margin-top="10px" alt='Buy Me a Coffee at ko-fi.com'/></a></div>-->
<div align="center">A sleek and minimalistic selfhosted web app for streaming your music library on your local network.</div>

#

### 💻 Dependencies

#

### 🛠️ Development

```bash
git clone https://github.com/Opensource-Waves/Waves
cd waves
npm run dev
```

#

### 📦 Docker Container

You can run the Docker container with the following command, replacing 8080 with the port of your choice:

```bash
docker run -d -p 8080:8080 ghcr.io/greenestgoat/opensource-waves
```

#

### 📁 Folder Structure

Currently supports any format supported by the [html 5 audio player](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Audio_codecs), with transcoding support to be added in future releases.

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


