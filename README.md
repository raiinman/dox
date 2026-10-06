<!-- project-centered:start -->
<div align="center">

<a name="readme-top"></a>
<h1 align="center">DOX</h1>

<!-- project-header:start -->
<p align="center"><img src="readme-banner.png" alt="dox — original decorative project artwork" width="100%"></p>
<!-- project-header:end -->

<!-- project-badges:start -->
<p align="center"><a href="https://github.com/raiinman/dox"><img src="https://img.shields.io/badge/framework-hierarchical_agent_context-6477AB?logo=github&amp;logoColor=white" alt="framework: hierarchical agent context"></a> <a href="https://github.com/raiinman/dox"><img src="https://img.shields.io/badge/access-public-6477AB?logo=github&amp;logoColor=white" alt="access: public"></a> <a href="#readme-index"><img src="https://img.shields.io/badge/docs-explore_the_index-6477AB?logo=readthedocs&amp;logoColor=white" alt="docs: explore the index"></a></p>
<!-- project-badges:end -->

<!-- project-live-badges:start -->
<p align="center"><a href="https://github.com/raiinman/dox/commits/main"><img src="https://img.shields.io/github/last-commit/raiinman/dox?color=6477AB&amp;logo=git&amp;logoColor=white" alt="GitHub last commit"></a> <a href="https://github.com/raiinman/dox/issues"><img src="https://img.shields.io/github/issues/raiinman/dox?color=6477AB&amp;logo=github&amp;logoColor=white" alt="GitHub open issues"></a> <a href="https://github.com/raiinman/dox/stargazers"><img src="https://badgen.net/github/stars/raiinman/dox?icon=github&amp;color=6477AB" alt="GitHub stars"></a></p>
<!-- project-live-badges:end -->

<!-- project-index:start -->
<a name="readme-index"></a>
<h3 align="center">✦ Explore this project</h3>
<table align="center"><tbody><tr><td align="center"><a href="#readme-overview"><strong>Overview</strong></a></td><td align="center"><a href="#readme-how-dox-works"><strong>How DOX works</strong></a></td></tr><tr><td align="center"><a href="#readme-how-to-use"><strong>How to use</strong></a></td><td align="center"><a href="#readme-credits"><strong>Credits</strong></a></td></tr></tbody></table>
<h4 align="center">Project shortcuts</h4>
<table align="center"><tbody><tr><td align="center"><a href="AGENTS.md"><strong>Agent guidance</strong></a></td><td align="center"><a href="LICENSE"><strong>License</strong></a></td></tr><tr><td align="center" colspan="2"><a href="video-thumbnail.jpg"><strong>video-thumbnail.jpg</strong></a></td></tr></tbody></table>
<!-- project-index:end -->

<a name="readme-overview"></a>
<h2 align="center">Overview</h2>

<p align="center"><a href="#readme-index">↑ Back to index</a></p>

<a name="readme-how-dox-works"></a>
## How DOX works


DOX is a tiny AGENTS.md framework that gives an AI agent precise project context.

The agent keeps a hierarchy of AGENTS.md files as the project changes:

<table align="center"><tbody><tr><td align="center">root AGENTS.md contains project-wide instructions and the top-level index</td></tr><tr><td align="center">child AGENTS.md files contain local instructions for specific areas</td></tr><tr><td align="center">before any edit, the agent walks the docs tree from the root to the area it will touch</td></tr><tr><td align="center">the relevant docs give it exact local guidelines, so it does not edit blindly</td></tr><tr><td align="center">after meaningful changes, it updates the affected AGENTS.md files</td></tr></tbody></table>


The result is simple: traverse the docs, understand the local rules, make precise edits, keep the docs current. Less guessing. Less drift. Less "why did it touch that file?"

<p align="center">
  <a href="https://youtu.be/NVkRkioBXQc">
    <img src="./video-thumbnail.jpg" alt="Watch: One markdown file just fixed AI coding forever." width="640">
  </a>
</p>

<p align="center"><a href="#readme-index">↑ Back to index</a></p>

<a name="readme-how-to-use"></a>
## How to use


<table align="center"><tbody><tr><td align="center">1</td><td align="center">Copy the contents of <a href="./AGENTS.md?plain=1">AGENTS.md</a> into your project's AGENTS.md file.</td></tr></tbody></table>


<br>
That's it. No installation, no dependencies, no package, no runtime. DOX is just a Markdown instruction for AI agents.

It works with any AI agent that supports AGENTS.md files, including Codex, Claude Code, OpenCode, and similar tools.

No AGENTS.md yet? Copy the file into your project root. The agent will see these instructions and will start building the DOX tree.

For an existing project, you can tell your agent: `Initialize DOX tree for this project now.` It will create all the child AGENTS.md files and indexes.

<p align="center"><a href="#readme-index">↑ Back to index</a></p>

<a name="readme-credits"></a>
## Credits


<p align="center">
  Created by <strong><a href="https://www.agent-zero.ai/">Agent Zero</a></strong><br>
  Open-source agentic AI framework<br>
  <a href="https://www.agent-zero.ai/">Website</a> · <a href="https://github.com/agent0ai/agent-zero">GitHub repository</a>
</p>

<p align="center"><a href="#readme-index">↑ Back to index</a> · <a href="#readme-top">Back to top ↑</a></p>

</div>
<!-- project-centered:end -->
