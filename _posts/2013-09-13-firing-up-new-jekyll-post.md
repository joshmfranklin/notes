---
layout: post
title:  "Firing up Jekyll"
date:   2013-09-13 09:41:00
tags: git, github, Jekyll
---

As promised I will be continuing to post my progress using Jekyll and other new development learnings I have gleaned since diving into this new realm of design/development.

It has been about a week since posting my first note to my new Jekyll based blog and I thought I would walk through the steps needed to push a new post. Thanks to [Brett Chalupa](http://brettchalupa.com) for the assist!

### Getting into Jekyll

<ol>
	<li>
		<p>Start up terminal or another third party application such as iTerm</p>
	</li>
	<li>
		<p>Once you are in the terminal <code>cd</code> into your Jekyll blog file with <code>cd blog</code></p>
		<p><strong>NOTE</strong>: <em>After you have changed to your blog directory you will also be in gh-pages (GitHub Pages)</em></p>
	</li>
	<li>
		<p>Next start up a local Jekyll server by using <code>jekyll serve --watch</code></p>
		<p><strong>NOTE</strong>: <em>This will set up a local server for your to view your posts naitively in browser.</em></p>
	</li>
	<li>
		<p>Start up your desired text editor from terminal (mine is Sublime Text 2) with <code>sublime .</code>
	</li>
</ol>

Once sublime is open you are free to create a new markdown file in your posts folder. I am just getting the hang of utilizing markdown to style posts. The markdown [wiki](http://en.wikipedia.org/wiki/Markdown) page is a good spot to start if you are new to markdown.

From here, you can utilize your git commands to add, commit, and push new posts to your site via gh-pages! 

### Pushing changes to gh-pages with git

<ol>
	<li>
		<p>Complete new blog post or changes to your jekyll site</p>
	</li>
	<li>
		<p>Swith over to terminal and use <code>git add .</code> or <code>git add [filename]</code>, this will add your file contents to the staging area before you commit them.</p>
	</li>
	<li>
		<p>Next you will commit these changes with <code>git commit -m</code>, the <code>-m</code> allows you to attached a message to the git commit, such as "new blog post" or "update to post css". Place your message after the -m within parentheses. The entire commit message should be<br><code>git commit -m "commit message"</code></p>
	</li>
	<li>
		<p>After you have commited your git content you will push it to gh-pages. To do this simply use <code>git push gh-pages</code>, your changes should then be added yo your active blog and be ready for viewing!</p>
	</li>
</ol>

That should do it for the steps needed for getting into your Jekyll based site and pushing changes through git to gh-pages. 








