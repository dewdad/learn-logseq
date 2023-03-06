- # Intro to Logseq: A Powerful Tool for Personal and Team Knowledge Management

  [Logseq: A privacy-first, open-source knowledge base](https://logseq.com/) that works on top of local plain-text [Markdown](https://commonmark.org/help/) and [Org-mode](https://orgmode.org/quickstart.html) files. You can use it to write, organize and share your thoughts, manage and track tasks, and build your own digital garden.

  2nd brain tools like Logseq are invaluable because they relfect our knowledge back to us associatively, with bidrectional relationships created by default between pages and blocks. Relationships are also native elements in the authoring process, they are as simple as  [[Logseq]] or ((A bock somewhere in my graph)), that in turn create these relationships in your graph/db.

  This is a great [getting started article](https://blog.logseq.com/how-to-get-started-with-networked-thinking-and-logseq/)  or

  **Intro Material**


  * [Onboarding: Learn the fundamentals of Logseq in 70 minutes](https://hub.logseq.com/getting-started/uQdEHALJo7RWnDLLLP7uux/onboarding-learn-the-fundamentals-of-logseq-in-70-minutes/iPUPLPx7dZgPuASHtqNu2m "https://hub.logseq.com/getting-started/uqdehaljo7rwndlllp7uux/onboarding-learn-the-fundamentals-of-logseq-in-70-minutes/ipuplpx7dzgpuashtqnu2m")
  * Learn by example: download an example graph [GitHub - BangBOOM/logseq_learn_eng](https://github.com/BangBOOM/logseq_learn_eng)

  Plugins
  -------

  These are some of the must have plugins [(install from Market guide)](https://www.appsntips.com/best-logseq-plugins/) you may want to start using straight away

  * [Automatic URL Title plugin](https://github.com/0x7b1/logseq-plugin-automatic-url-title/): This plugin handles raw URLs and converts them into link format using the title of the website and shows the favicon for the pasted URL. A real time-saver for pasting web links into your notes
    ![demo](https://github.com/0x7b1/logseq-plugin-automatic-url-title/raw/main/demo.gif)
  * [Agenda plugin](https://github.com/haydenull/logseq-plugin-agenda): This plugin shows you a calendar view of your tasks and events based on their scheduled or deadline dates. You can also filter by tags or properties to see only relevant items.
    ![Timeline](https://github.com/haydenull/logseq-plugin-agenda/raw/main/screenshots/timeline.png)
  * [OpenAI GPT3 plugin](https://github.com/briansunter/logseq-plugin-gpt3-openai) ([demo](https://briansunter.com/blog/gtp3-openai-logseq-notetaking)): This plugin allows you to generate human-like text using GPT-3 within the Logseq editor.
  * [Kanban plugin](https://github.com/hkgnp/logseq-kanban-plugin): This plugin draws kanban boards using the outliner approach.
  * [logseq-plugin-todo-master](https://github.com/pengx17/logseq-plugin-todo-master): A simple plugin to render a progress bar to gather the overall progress of the TODO markers based on the rendering position.![img](https://github.com/pengx17/logseq-plugin-todo-master/raw/master/legend.png)
  * [logseq-plugin-link-prerview](https://github.com/pengx17/logseq-plugin-link-preview) by pengx17 - add external link preview using OpenGraph metadata
  * [logseq-plugin-tabs](https://github.com/pengx17/logseq-plugin-tabs) by pengx17 - A Logseq plugin which lets you open pages in tabs like working in the browser

  Queries
  -------

  Another powerful feature of Logseq is its query system. Queries are expressions that allow you to search your graph based on various criteria (e.g., tags, properties, dates, text, etc.). They can be used to create dynamic lists, tables, charts, or graphs from your data.
  [Advanced queries](https://mschmidtkorth.github.io/logseq-msk-docs/#/page/queries%2Fadvanced%20queries%2Ftutorial) are written in Datalog, a declarative logic programming language that uses facts and rules to infer new information.
  [Simple queries](https://mschmidtkorth.github.io/logseq-msk-docs/#/page/queries%2Fsimple%20queries) are a shorthand macro that can be used for most common use-cases, e.g.:

  ```
  {{query (and [[my project]] (task NOW LATER))}}
  ```

  [Logseq Query Builder](https://adxsoft.github.io/logseqadvancedquerybuilder/), an online tool and [plugin](https://github.com/adxsoft/logseq-query-builder-plugin) helps you build advanced queries from simple commands contained in a code block. You can choose from various options such as page name, tag name, property name, date range, sort order, limit number, etc., and generate an advanced query with one click. You can also edit the query manually if needed for learning Datalog or further customization. there is also a plugin

## Additionally

* There are lots of [themes](https://github.com/topics/logseq-themes) you can use with Logseq and I personally am very happy with [Ozean](https://github.com/hisea/logseq-ozean-theme)
* [Awesome Logseq resources created by the community &lt;3](https://github.com/logseq/awesome-logseq)
* [https://www.logseqtimes.com/](https://www.logseqtimes.com/) - Unofficial home for news, updates and opinions from the world of Logseq
* [fireSeqSearch](https://github.com/Endle/fireSeqSearch) - Extension that displays logseq results alongside google ones
* [logseq-copilot](https://github.com/EINDEX/logseq-copilot) - Chrome extension that display logseq results next to google ones

### Third Party Integrations

These are integrations that are officially supported by the third party:

* [Readwise](https://github.com/readwiseio/logseq-readwise-official-plugin#readme) - Provides Logseq plugin to export Readwise highlights to Logseq
* [Matter](https://github.com/getmatterapp/logseq-matter#readme) - Provides Logseq plugin to sync Matter highlights with Logseq
* [SamePage](https://samepage.network/docs/logseq/install) - Provides Logseq plugin to sync your graph with SamePage notebooks
* [Snipd](https://hub.logseq.com/integrations/aV9AgETypcPcf8avYcHXQT/feed-your-logseq-graph-using-snipd-podcast-notes/3U63PohVXL24PvbvXUzf2b) - Mobile app that exports Snipd podcast notes to Logseq
* [Omnivore](https://github.com/omnivore-app/logseq-omnivore) - Provides Logseq plugin to fetch Omnivore articles and highlights
* [NeuraCache](https://neuracache.com/) - Mobile app that provides additional flashcard and spaced repetition functionality on Logseq graphs

An intro tgse
* [Snipd](https://hub.logseq.com/integrations/aV9AgETypcPcf8avYcHXQT/feed-your-logseq-graph-using-snipd-podcast-notes/3U63PohVXL24PvbvXUzf2b) - Mobile app that exports Snipd podcast notes tos
* [Snipd](https://hub.logseq.com/integrations/aV9AgETypcPcf8avYcHXQT/feed-your-logseq-graph-using-snipd-podcast-notes/3U63PohVXL24PvbvXUzf2b) - Mobile app that exports Snipd podcast notes to Logseq
