<div align="center">
    <img src="https://i.imgur.com/tQrygFc.png" width="128px" style="max-width:100%;">
    <h3 style="font-size: 2rem; margin-bottom: 0">Game-Linter Music Master README</h3>
    <h4 style="margin-top: 0">Revision 1</h4>
<a  href="https://www.codacy.com/gh/Game-Linter/Discord-Music-Master/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Game-Linter/Discord-Music-Master&amp;utm_campaign=Badge_Grade"><img src="https://app.codacy.com/project/badge/Grade/8ce4f4a7f73e49339485747ec0c298e7"/></a>
	<a href="https://github.com/Game-Linter/Discord-Music-Master/actions/workflows/ci.yml"><img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/game-linter/Discord-Music-Master/ci"></a>
<a href="https://app.fossa.com/projects/git%2Bgithub.com%2FGame-Linter%2FDiscord-Music-Master?ref=badge_shield" alt="FOSSA Status"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FGame-Linter%2FDiscord-Music-Master.svg?type=shield"/></a>
	<a href="https://dev.azure.com/BELKAMELMOHAMED/Game-Linter%20Music%20Master/_build/latest?definitionId=1"><img alt="Azure DevOps builds" src="https://dev.azure.com/BELKAMELMOHAMED/Game-Linter/_apis/build/status/Game-Linter%20CI-CD"></a>
	<a href="https://game-linter.com"><img alt="Website" src="https://img.shields.io/website?down_color=red&down_message=Offline&up_color=green&up_message=Online&url=https%3A%2F%2Fgame-linter.com"></a>
	<a href="https://github.com/Game-Linter/Discord-Music-Master/blob/master/LICENSE.md"><img alt="GitHub" src="https://img.shields.io/github/license/game-linter/Discord-Music-Master"></a>
	<a href="https://discord.gg/QFrgdV3"><img alt="Discord" src="https://img.shields.io/discord/626833340560965652"></a>
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/game-linter/discord-music-master">
    <br />
    <br />
	<b> Feel like supporting hosting and developement of this project??</b>
    <br />
	<br/>
	<a href="https://www.buymeacoffee.com/quasimodo64" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="display: flex; justify-content: center" ></a>
</div>
<html lang="en">
	    <body>
    	<h1>Play almost any type of songs</h1>
    	<h4>Types of inputs</h4>
    	<ul>
    		<li>Normal youtube query or search</li>
    		<li>Youtube url or short youtube url</li>
          	<li>Youtube public playlist</li>
    		<li>Spotify track url</li>
    		<li>
    			Spotify Playlist URL
    		</li>
          <li>
    			Spotify Album URL
    		</li>
    	</ul>
    	<h4>Play inputs</h4>
    	<p><code>__audio [input]</code></p>
    <p></p>
      <h4>Play the given input instantly even if the queue is full so you don't have to wait for the queue to finish. When done, the bot will continue the previous queue</h4>
    	<p><code>__audionow [input]</code></p>
    	<h4>Pause</h4>
    	<p><code>__pause</code></p>
    	<h4>Skip</h4>
    	<p><code><code>__skip</code></code></p>
    	<h4>Resume</h4>
    	<p><code><code>__resume</code></code></p>
    	<h4>Quit</h4>
    	<p><code>__fuckoff</code></p>
    	<h4>Save playlist for server</h4>
    	<p><code>__save [nameOfPlaylist] [linkToPlaylist]</code></p>
    	<h4>Load Saved Playlist</h4>
    	<p><code>__load [nameOfPlaylist]</code></p>
   	<h4>Restart current song</h4>
    	<p><code>__restart</code></p>
	<h4>Help</h4>
    	<p><code>__help</code></p>
	<h4>Get Lyrics (if they exist)</h4>
    	<p><code>__lyrics</code></p>
    	<h4>Autoplay Toggle (playing Recommended Songs)</h4>
    	<p><code>__autoplay</code></p>
    	<h4>Loop Toogle current song forever or until you type the command again</h4>
    	<p><code>__loop</code></p>
      	<h4>Shuffle current queue</h4>
      	<p><code>__shuffle</code></p>
      <h3>Note 1:</h3>
      <p><code>The bot will leave the channel if left alone or moved to a channel by it self</code></p>
      <h3>Note 2:</h3>
      <p><code>The bot will keep playing related and recommended music to the currently playing track, as long as the queue is empty</code></p>
      <h3>Note: 3</h3>
      <p><code>The bot prioritize in order:</code></p>
      <ol>
      	<li>Loop if enabled</li>
        <li>Queue if not empty</li>
        <li>Autoplay which is enabled by default</li>
      </ol>
      <h1>Contributing</h1>
      <p>
      Game-Linter Music Master is a community project We invite your participation through issues and pull requests! You can peruse the <a href="https://github.com/darklight147/discord-music/blob/master/.github/CONTRIBUTING.md">
    	Contribution Guidelines
      </a>
      </p>
      <div>
      <h1> Developement </h1>
	      You need the latest version of <a href="https://www.typescriptlang.org/download" target="__blank">Typescript</a> <br/>
Clone the project and run:

```sh
yarn --frozen-lockfile
```

Replace all the `REMOVED` in config folder with your credentials

Then run:

```sh
yarn start
```

</div>
      <h3>Everything is Licensed under
      <a href="https://github.com/darklight147/discord-music/blob/master/LICENSE.md">AGPL-3.0 License</a>
      </h3>
    </body>

</html>


[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FGame-Linter%2FDiscord-Music-Master.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FGame-Linter%2FDiscord-Music-Master?ref=badge_large)