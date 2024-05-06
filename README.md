<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 align="center" tabindex="-1" class="heading-element" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/explodinggradients/ragas/blob/main/docs/_static/imgs/logo.png"><img height="200" src="https://github.com/explodinggradients/ragas/raw/main/docs/_static/imgs/logo.png" style="max-width: 100%;"></a>
</h1><a id="user-content---" class="anchor" aria-label="永久链接：" href="#--"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
  <i><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检索增强生成 (RAG) 管道的评估框架</font></font></i>
</p>
<p align="center" dir="auto">
    <a href="https://github.com/explodinggradients/ragas/releases">
        <img alt="GitHub 发布" src="https://camo.githubusercontent.com/b0363594278d3be7fa131530e2f3ae7dd1b9eecd1c493cb6431bc414d092cc5d/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f6578706c6f64696e676772616469656e74732f72616761732e737667" data-canonical-src="https://img.shields.io/github/release/explodinggradients/ragas.svg" style="max-width: 100%;">
    </a>
    <a href="https://www.python.org/" rel="nofollow">
            <img alt="建造" src="https://camo.githubusercontent.com/739db8b875292148bfeb7ac6f277e83e07251132d00a177c85d25f4be780adec/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d616465253230776974682d507974686f6e2d3166343235662e7376673f636f6c6f723d707572706c65" data-canonical-src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg?color=purple" style="max-width: 100%;">
    </a>
    <a href="https://github.com/explodinggradients/ragas/blob/master/LICENSE">
        <img alt="执照" src="https://camo.githubusercontent.com/c1e2e7f623faa7ddd4d181a7d599ceff928611e88069814c00916ad832a25033/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f6578706c6f64696e676772616469656e74732f72616761732e7376673f636f6c6f723d677265656e" data-canonical-src="https://img.shields.io/github/license/explodinggradients/ragas.svg?color=green" style="max-width: 100%;">
    </a>
    <a href="https://colab.research.google.com/github/explodinggradients/ragas/blob/main/docs/quickstart.ipynb" rel="nofollow">
        <img alt="在 Colab 中打开" src="https://camo.githubusercontent.com/f5e0d0538a9c2972b5d413e0ace04cecd8efd828d133133933dfffec282a4e1b/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width: 100%;">
    </a>
    <a href="https://discord.gg/5djav8GGNZ" rel="nofollow">
        <img alt="不和谐邀请" src="https://camo.githubusercontent.com/87c4f083b2dee938b2ad6b076306bd4ef2329640b8e3aaf2ecc4d91dc27718af/68747470733a2f2f646362616467652e76657263656c2e6170702f6170692f7365727665722f35646a61763847474e5a3f7374796c653d666c6174" data-canonical-src="https://dcbadge.vercel.app/api/server/5djav8GGNZ?style=flat" style="max-width: 100%;">
    </a>
    <a href="https://github.com/explodinggradients/ragas/">
        <img alt="下载" src="https://camo.githubusercontent.com/196e8b088932bdaf1b820ca7ab78e04307999f5bd44130bbb392053d8d07a9c8/68747470733a2f2f6261646765732e66726170736f66742e636f6d2f6f732f76312f6f70656e2d736f757263652e7376673f763d313033" data-canonical-src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103" style="max-width: 100%;">
    </a>
</p>
<div class="markdown-heading" dir="auto"><h4 align="center" tabindex="-1" class="heading-element" dir="auto">
    <p dir="auto">
        <a href="https://docs.ragas.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
        </font></font><a href="#shield-installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
        </font></font><a href="#fire-quickstart"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速入门</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
        </font></font><a href="#-community"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
        </font></font><a href="#-open-analytics"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放分析</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
        </font></font><a href="https://huggingface.co/explodinggradients" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">抱脸</font></font></a>
    </p><p dir="auto">
</p></h4><a id="user-content-------------documentation---------installation---------quickstart---------community---------open-analytics---------hugging-face----" class="anchor" aria-label="永久链接：文档 |安装|快速入门 |社区 |开放分析|抱脸" href="#------------documentation---------installation---------quickstart---------community---------open-analytics---------hugging-face----"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🚀 用于评估、监控和提高生产中 LLM 和 RAG 应用性能的专用解决方案，包括用于生产质量监控的定制模型。</font></font><a href="https://cal.com/shahul-ragas/30min" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与创始人交谈</font></font></a></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ragas 是一个框架，可帮助您评估检索增强生成 (RAG) 管道。 RAG 表示一类使用外部数据来增强 LLM 背景的 LLM 申请。现有的工具和框架可以帮助您构建这些管道，但对其进行评估并量化管道性能可能很困难。这就是 Ragas（RAG 评估）发挥作用的地方。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ragas 为您提供基于最新研究的工具，用于评估 LLM 生成的文本，让您深入了解 RAG 管道。 Ragas 可以与您的 CI/CD 集成，以提供持续检查以确保性能。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🛡️安装</font></font></h2><a id="user-content-shield-installation" class="anchor" aria-label="永久链接： :shield: 安装" href="#shield-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从发布：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install ragas</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install ragas" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，从来源：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install git+https://github.com/explodinggradients/ragas</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install git+https://github.com/explodinggradients/ragas" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔥 快速入门</font></font></h2><a id="user-content-fire-quickstart" class="anchor" aria-label="永久链接：:fire：快速入门" href="#fire-quickstart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是一个小示例程序，您可以运行它来查看 ragas 的运行情况！</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">datasets</span> <span class="pl-k">import</span> <span class="pl-v">Dataset</span> 
<span class="pl-k">import</span> <span class="pl-s1">os</span>
<span class="pl-k">from</span> <span class="pl-s1">ragas</span> <span class="pl-k">import</span> <span class="pl-s1">evaluate</span>
<span class="pl-k">from</span> <span class="pl-s1">ragas</span>.<span class="pl-s1">metrics</span> <span class="pl-k">import</span> <span class="pl-s1">faithfulness</span>, <span class="pl-s1">answer_correctness</span>

<span class="pl-s1">os</span>.<span class="pl-s1">environ</span>[<span class="pl-s">"OPENAI_API_KEY"</span>] <span class="pl-c1">=</span> <span class="pl-s">"your-openai-key"</span>

<span class="pl-s1">data_samples</span> <span class="pl-c1">=</span> {
    <span class="pl-s">'question'</span>: [<span class="pl-s">'When was the first super bowl?'</span>, <span class="pl-s">'Who won the most super bowls?'</span>],
    <span class="pl-s">'answer'</span>: [<span class="pl-s">'The first superbowl was held on Jan 15, 1967'</span>, <span class="pl-s">'The most super bowls have been won by The New England Patriots'</span>],
    <span class="pl-s">'contexts'</span> : [[<span class="pl-s">'The First AFL–NFL World Championship Game was an American football game played on January 15, 1967, at the Los Angeles Memorial Coliseum in Los Angeles,'</span>], 
    [<span class="pl-s">'The Green Bay Packers...Green Bay, Wisconsin.'</span>,<span class="pl-s">'The Packers compete...Football Conference'</span>]],
    <span class="pl-s">'ground_truth'</span>: [<span class="pl-s">'The first superbowl was held on January 15, 1967'</span>, <span class="pl-s">'The New England Patriots have won the Super Bowl a record six times'</span>]
}

<span class="pl-s1">dataset</span> <span class="pl-c1">=</span> <span class="pl-v">Dataset</span>.<span class="pl-en">from_dict</span>(<span class="pl-s1">data_samples</span>)

<span class="pl-s1">score</span> <span class="pl-c1">=</span> <span class="pl-en">evaluate</span>(<span class="pl-s1">dataset</span>,<span class="pl-s1">metrics</span><span class="pl-c1">=</span>[<span class="pl-s1">faithfulness</span>,<span class="pl-s1">answer_correctness</span>])
<span class="pl-s1">score</span>.<span class="pl-en">to_pandas</span>()</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="
from datasets import Dataset 
import os
from ragas import evaluate
from ragas.metrics import faithfulness, answer_correctness

os.environ[&quot;OPENAI_API_KEY&quot;] = &quot;your-openai-key&quot;

data_samples = {
    'question': ['When was the first super bowl?', 'Who won the most super bowls?'],
    'answer': ['The first superbowl was held on Jan 15, 1967', 'The most super bowls have been won by The New England Patriots'],
    'contexts' : [['The First AFL–NFL World Championship Game was an American football game played on January 15, 1967, at the Los Angeles Memorial Coliseum in Los Angeles,'], 
    ['The Green Bay Packers...Green Bay, Wisconsin.','The Packers compete...Football Conference']],
    'ground_truth': ['The first superbowl was held on January 15, 1967', 'The New England Patriots have won the Super Bowl a record six times']
}

dataset = Dataset.from_dict(data_samples)

score = evaluate(dataset,metrics=[faithfulness,answer_correctness])
score.to_pandas()" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅我们的</font></font><a href="https://docs.ragas.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以了解更多信息。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🫂 社区</font></font></h2><a id="user-content--community" class="anchor" aria-label="永久链接：🫂 社区" href="#-community"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想更多地参与 Ragas，请查看我们的</font></font><a href="https://discord.gg/5djav8GGNZ" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不和谐服务器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这是一个有趣的社区，我们在这里研究法学硕士、检索、生产问题等。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔍 开放分析</font></font></h2><a id="user-content--open-analytics" class="anchor" aria-label="永久链接：🔍 开放分析" href="#-open-analytics"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们跟踪非常基本的使用指标，以指导我们了解用户想要什么、什么有效、什么无效。作为一家年轻的初创公司，我们必须对此非常诚实，这就是我们跟踪这些指标的原因。但作为一家开放式初创公司，我们将收集的所有数据开源。您可以</font></font><a href="https://github.com/explodinggradients/ragas/issues/49" data-hovercard-type="issue" data-hovercard-url="/explodinggradients/ragas/issues/49/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阅读有关此内容的更多信息。</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ragas 不会跟踪任何可用于识别您或您的公司身份的信息</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。您可以具体查看我们在</font></font><a href="/explodinggradients/ragas/blob/main/src/ragas/_analytics.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码中跟踪的内容</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要禁用使用情况跟踪，请将</font></font><code>RAGAS_DO_NOT_TRACK</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标志设置为 true。</font></font></p>
</article></div>
