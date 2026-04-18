# Open-source Projects You Could Try
Open-source projects from GitHub(or wherever) I plan to explore or experiment with.

仅供参考，有一些可能不好用，但总有好用的，可以启发思路。

## 科研工具类
[MatterViz](https://github.com/janosh/matterviz)：面向材料科学的交互式可视化工具箱，助力周期表、3D晶体结构及分子动态的深入理解。
- 多维交互：周期表热力图、3D晶体结构、原子模型、核结构、散点图与直方图，涵盖材料科学核心数据表现形式  
- VSCode 扩展：支持 CIF、POSCAR、XYZ、TRAJ、HDF5 等多种文件格式，右键菜单及快捷键一键渲染，方便集成研发流程  
- 开发中但功能完善，适合科研人员和开发者探索材料属性的内在规律与周期性特征  
- 基于现代前端技术栈（Svelte、three.js、d3），兼顾性能与交互体验，具备良好扩展性与社区潜力  
- 深层认知：结合元素性质周期性与动态轨迹，助力材料科学从数据到本质的量化与可视化分析  
长期价值在于为材料科学研究提供一套可视化方法论框架，提升科研效率和跨学科协作能力。适合关注材料设计、计算化学与数据可视化的专业人士。

[colors](https://github.com/lcpmgh/colors): 学术期刊配色推荐器，为科研绘图提供专业配色方案。
收录200+顶刊配色方案，涵盖Science、Nature等；支持颜色透明度调节，满足多样化绘图需求；提供云端访问与本地运行双重选择。

[Veusz](https://github.com/veusz/veusz): 为科研人员打造的高效科学绘图工具。
支持超过20种图表类型，满足多样化绘图需求；提供GUI、Python模块、命令行等多种操作方式；支持PDF、SVG、PNG等高质量输出格式。

[lilaq](https://github.com/lilaq-project/lilaq)：用Typst实现高级数据可视化的强大工具。
支持多种复杂图表，如轮廓图、向量场图等；提供丰富的样式定制选项，满足个性化需求；文档完善，提供大量示例和教程，上手容易。

[matplot2tikz](https://github.com/ErwindeGelder/matplot2tikz)：将Python的matplotlib图表无缝转换为LaTeX兼容的TikZ/PGFPlots格式。
输出格式为PGFPlots，保留更多图表信息，易于理解和编辑；支持多种图表类型，包括2D图表和部分3D图表；提供方便的清理功能，优化导出文件的大小和质量。

[Scholar PDF Reader with Annotations](https://github.com/salcc/Scholar-PDF-Reader-with-Annotations)： 为学术研究提供强大的PDF阅读与标注工具。
支持六种颜色高亮标注，满足多样化标注需求；可导入导出JSON格式标注，防止数据丢失；保留原Google Scholar PDF Reader全部功能，如引用预览、AI大纲辅助阅读等。

[Mathpad](https://github.com/Summa-Cogni/Mathpad)：一款为学生和专业人士设计的数学键盘，让输入复杂公式变得轻松简单。
支持112种数学符号和完整希腊字母，涵盖代数、微积分、集合论和逻辑；兼容Windows、macOS和Unix系统；支持多种输出模式，包括Plaintext、LaTeX和Microsoft Office公式编辑器。

[mad-professor-public](https://github.com/LYiHub/mad-professor-public)：一个让读论文不再枯燥的AI伴侣。
拥有暴躁个性的AI教授，让学术阅读充满趣味；支持语音交互，解放双手；一键处理PDF论文，自动翻译并结构化内容。

[Local Deep Research](https://github.com/LearningCircuit/local-deep-research) ：一款基于人工智能的深度研究助手，支持本地运行或云端配置，具备强大的多轮分析和网络搜索能力。它通过智能迭代和多重验证，提供全面的研究结果，适用于学术、商业等多种场景。系统支持多种大语言模型（LLMs），如 Ollama、Claude 和 GPT，并可灵活配置模型选择。其隐私保护功能确保数据在本地处理，同时提供丰富的输出选项，包括详细的研究报告、快速摘要和引用跟踪。此外，项目集成了多种搜索引擎和知识库（如 Wikipedia、arXiv、PubMed），支持本地文档的向量嵌入搜索（RAG），适用于私密文档的高效检索。

[Curie](https://github.com/Just-Curieous/Curie)：Curie 是一个 AI 代理框架，旨在实现自动化和严谨的科学实验。它自动化实验的整个流程，包括假设提出、实验设计、执行、结果分析和结论总结。Curie 注重实验的精确性、可靠性和可重复性，内置验证模块以确保实验的严谨性。该框架适用于机器学习研究、系统分析和科学发现等多个领域，旨在加速科研进程。

[Manim](https://github.com/3b1b/manim)：Manim 是一款专为数学讲解视频打造的程序化动画引擎，支持用代码精确制作复杂的数学动画。用户可通过 Python 脚本灵活控制画面效果，实现公式推导、几何演示等高质量动画输出。Manim 拥有活跃的社区版本，功能更完整、易于上手，适合教育工作者、内容创作者和开发者制作专业的数学可视化视频。无论是教学还是科普，都能显著提升内容的表达力和观赏性。

## 实用工具类
[Process Interactive Kill（pik）](https://github.com/jacek-kurlit/pik)：一款基于 Rust 的命令行交互式进程搜索与终止工具，兼具灵活性与高效性，适合开发者和系统管理员精细化管理进程。
- 支持模糊搜索进程，关键词包含：
  - 进程名（直接输入，如 firefox）
  - 命令路径（以 '/' 前缀，如 /firefox）
  - 启动参数（以 '-' 前缀，如 -foo，需加 -- 传递）
  - 监听端口（以 ':' 前缀，如 :8080）
  - 全局匹配（以 '~' 前缀，如 ~firefox）
  - 精确进程 ID（以 '!' 前缀，如 !1234）
  - 进程家族（父进程及子进程，以 '@' 前缀，如 @1234）
- 结果实时交互式筛选，选中目标进程后可直接用 Ctrl + X 杀死，提升操作效率
- 跨平台设计，Linux、macOS、Windows 理论支持，社区可参与测试与反馈，开源MIT许可
- 多渠道安装支持：Linux 发行版包管理器、Rust cargo、dra 及预编译二进制包
- 配置灵活，支持 config.toml 文件和命令行参数双重配置，满足个性化需求
- 当前仍在开发中，持续迭代完善中，欢迎社区贡献和测试
pik 不仅是 pkill 的交互升级，更通过多维度模糊匹配和家族进程操作，极大提升了进程管理的精准度和友好度，适合复杂场景下多任务高效运维。

[GitSummarize](https://github.com/antarixxx/gitsummarize)：为任何GitHub仓库生成世界级的精美文档。
瞬间生成系统级架构概览；提取业务逻辑与规则，清晰呈现代码结构；支持交互式文档，帮助快速上手复杂代码库。

[git-quick-stats](https://github.com/git-quick-stats/git-quick-stats)：高效提取 Git 仓库统计数据。
- 一站式访问提交记录、贡献者、分支历史等多维度统计，突破繁杂 git 命令的认知壁垒。  
- 支持交互式菜单和丰富命令行参数，满足不同使用习惯与自动化需求。  
- 详尽统计选项涵盖时间（年、月、周、日、小时）、作者、分支、时区等维度，助力深度代码分析。  
- 灵活配置环境变量控制时间范围、输出格式（CSV/JSON）、排除路径及合并提交视图，提升统计精准度。  
- 跨平台支持 Debian、Ubuntu、macOS（Homebrew）、Windows（Cygwin/WSL）及 Docker，部署便捷。  
- 丰富的贡献者建议、代码审查提示，促进团队协作与代码质量提升。  
- MIT 开源协议，文档规范且持续更新，适合长期项目维护与数据驱动决策。  
通过系统化统计方法，git-quick-stats帮助开发者挖掘代码库背后的贡献规律与协作趋势，实现更科学的版本管理和团队管理。

[yamlresume](https://github.com/yamlresume/yamlresume)：用代码管理简历，让简历创作变得轻松又有趣。
用YAML格式编写简历，结构清晰易读；自动生成专业PDF，支持多种模板；开源免费，无供应商锁定。

[CloudPlayPlus Stone](https://github.com/zhuhaichao518/cloudplayplus_stone)：为远程游戏打造的超低延迟、高画质远程桌面软件。
实现2K分辨率60FPS，延迟仅40ms；支持多种硬件解码方案；定制版WebRTC提升性能。

[BilldDesk](https://github.com/galaxy-s10/billd-desk): 一款开源免费的远程桌面控制工具，基于Vue3 + WebRTC + Nodejs + Electron搭建，完美替代ToDesk等付费软件。
无连接时长和次数限制，完全免费；支持多平台操作，包括Windows、macOS、Linux、安卓和iOS；提供屏幕墙、多屏操作等高级功能，无需额外付费。

[DockerComposeMaker (DCM)](https://github.com/ajnart/dcm)：为家庭服务器量身定制的docker-compose.yml文件生成器。
支持超过50种流行的自托管应用；提供多种预设模板，如媒体服务器、开发环境等；简化部署流程，一键生成配置文件。

[ReadYou](https://github.com/Ashinch/ReadYou)：一款基于Material You风格的Android RSS阅读器，让你轻松订阅和管理RSS源。
支持多种第三方服务API，无缝对接云账户；提供夜间版本，抢先体验最新功能；多语言支持，满足不同用户需求。

[Moodiary](https://github.com/ZhuJHua/moodiary)：一个全开源的跨平台日记应用，用Flutter和Rust编写。它能帮你安全地记录和管理日记，解决隐私和数据安全问题。
支持多种文本编辑格式（如Markdown、富文本）；提供强大的数据安全功能，支持密码和生物识别解锁；支持多媒体附件，可添加图片、音频、视频等。

[Docling Parse](https://github.com/docling-project/docling-parse)：专注于从程序化 PDF 中高效提取文本、路径及位图资源的轻量级工具包。  
- 支持字符、单词及行级别文本坐标输出，精准定位文本内容，方便深度版面分析与可视化
- 同时提取路径和位图图像，满足复杂文档结构解析需求  
- 内置可交互式可视化脚本，便于快速验证与展示解析效果  
- 性能显著提升，最新版本解析速度较初版快 5-10 倍，适合大规模文档处理  
- Python 包即装即用，支持命令行和编程接口，灵活集成到多种工作流  
- 完全开源，MIT 许可，社区活跃，持续更新与优化，便于二次开发和创新  
- 适合科研、文档数字化、信息抽取等多场景应用，助力文档数据智能化转型  
基于程序化 PDF 结构，精细提取多层级文本单元与图形元素，融合性能优化与可视化，推动 PDF 内容的结构化理解与应用扩展。

***~~（ps: 实用工具一定要实用~~***
[Mystical_ps](https://github.com/denismm/mystical_ps)：将编程语言变成魔法符咒的奇妙项目。
将PostScript代码转化为视觉化的魔法圈，让代码更直观；提供丰富的符号系统，支持自定义符号；代码布局优化，避免视觉冲突，提升可读性。

[Storm Breaker](https://github.com/ultrasecurity/Storm-Breaker)：伪装成正常网页，诱骗用户授权，从而获取用户的设备信息（无需权限）、地理位置（手机）、摄像头和麦克风访问权限。 使用 PHP、Python 和 JavaScript 开发，提供 Web 界面，方便操作。 新版本需要用户自己配置 Ngrok 才能在外网使用，或者直接部署到自己的服务器上。 适合安全研究人员进行测试，请勿用于非法用途！

[DVMCP](https://github.com/harishsg993010/damn-vulnerable-MCP-server)：DVMCP (Damn Vulnerable Model Context Protocol) 是一个专为教育目的、故意设计存在安全漏洞的项目。它模拟了一个易受攻击的模型上下文协议（MCP）服务器，包含10个难度递增的安全挑战。这些挑战涵盖了提示注入、工具滥用、权限问题、令牌窃取乃至代码执行等多种攻击向量。其核心目标是帮助安全研究员、开发者和AI安全专家识别、理解并学习如何防范在实际MCP应用中可能遇到的安全风险，提升对LLM相关协议安全的认知。

[FilePizza](https://github.com/kern/filepizza)：FilePizza 是一款利用 WebRTC 技术实现的网页端点对点（P2P）文件传输工具。它允许用户直接在浏览器之间传输文件，无需经过中间服务器上传或存储。这种 P2P 模式显著提高了传输速度，并确保了文件传输的私密性和端到端安全性。用户无需安装额外软件，支持多文件（打包为 ZIP 下载）、密码保护、传输进度监控，并兼容主流桌面及移动浏览器。

[VHS](https://github.com/charmbracelet/vhs)：VHS 是一款命令行终端录制工具，可将终端操作过程以脚本方式生成高质量 GIF 动画，非常适用于 CLI 工具集成测试和演示。用户通过编写 .tape 文件，灵活控制终端指令、输出样式、字体、分辨率等参数，实现自动化录制、回放和批量生成多格式演示文件。VHS 支持一键录制、个性化配置、云端发布、集成 CI 流水线等功能，兼容多平台安装，极大提升技术文档、教程和产品演示的可视化效率。

[Vicinae](https://github.com/vicinaehq/vicinae)：Vicinae 是一款基于 C++ 和 Qt 开发的桌面启动器，主打原生、高效和可扩展。它为开发者和高阶用户提供键盘优先的操作体验，支持应用启动、文件搜索、剪贴板与计算器历史、窗口聚焦、表情选择等常用功能。Vicinae 提供类 Raycast 扩展 API，兼容大部分 Raycast 插件，并可通过 React/TypeScript 快速开发自定义扩展，无需浏览器或 Electron。内置主题系统与 dmenu 兼容模式，让系统操作更流畅便捷，适用于追求高效率的桌面用户。

## MCP类
[ScrapeGraphAI](https://github.com/ScrapeGraphAI/Scrapegraph-ai)：基于大型语言模型与图逻辑的Python爬虫库，实现“一次爬取，多次利用”的高效数据提取方案。
- 利用LLM（如OpenAI、Ollama等）和图结构构建灵活爬取管线，支持网页及本地文档（HTML、Markdown、JSON、XML等）  
- 多种爬取模式：单页智能提取（SmartScraperGraph）、多页搜索结果抓取（SearchGraph）、音频生成（SpeechGraph）、自动生成Python脚本（ScriptCreatorGraph）等，满足复杂场景需求  
- 完善集成生态：支持Python、Node.js SDK，兼容Langchain、Llama Index、Zapier、Bubble等主流低代码/无代码平台，极大降低二次开发门槛  
- 简单易用：5行代码快速上手，官方推荐虚拟环境安装，Playwright支持动态网页内容抓取  
- 透明开源，MIT协议授权，活跃社区持续更新，20.5k⭐️，1700+ Fork，适合科研、数据分析、自动化工程长期参考与实践  
- 详尽文档与示例代码覆盖多语言接口，支持多模型并行调用，灵活切换本地或云端LLM，强调方法论与长远适用性  
ScrapeGraphAI通过“语言理解+图结构”策略，将爬虫从传统规则驱动转向智能语义驱动，极大提升数据清洗和结构化效率，是下一代智能数据抽取范式的典范。

[Chrome MCP Server](https://github.com/hangwin/mcp-chrome)：将你的Chrome浏览器变成智能助手，让AI掌控浏览器，实现复杂自动化、内容分析和语义搜索。
直接使用日常Chrome浏览器，无需重新登录；纯本地MCP服务器，确保用户隐私；支持20+工具，包括截图、网络监控、互动操作等。

[FreeCAD-MCP](https://github.com/neka-nat/freecad-mcp): 通过Claude桌面远程控制FreeCAD的高效工具。
实现从2D绘图到3D建模的无缝转换；提供丰富的操作工具，如创建、编辑、删除对象；支持多种操作系统，安装简单。

[Open WebUI Artifacts Overhaul](https://github.com/nick-tonjum/open-webui-artifacts-overhaul)：一个用户友好的AI界面，支持Ollama、OpenAI API等多种AI工具。
编码画布功能，代码输出直观展示，方便开发者快速查看和编辑；支持30多种编程语言，满足多样化需求；提供设计视图和代码视图切换，增强用户体验。

[MultiAgentPPT](https://github.com/johnson7788/MultiAgentPPT)：基于多Agent架构的智能PPT生成系统，输入主题即可自动生成高质量演示文稿。
多Agent并行协作，生成效率提升3倍以上；实时流式返回内容，用户体验更流畅；高质量内容输出，结合外部检索与智能体协作。

[SuperDesign](https://github.com/superdesigndev/superdesign)：AI设计Agent，让设计工作更高效！在IDE中直接生成UI界面、组件和线框图，用自然语言就能搞定设计任务。
无缝集成Cursor、Windsurf、Claude Code和VS Code；本地保存设计，方便管理和复用；支持快速迭代和修改现有UI组件。

[GenCAD](https://github.com/ferdous-alam/GenCAD): 面向生成设计的开源计算机辅助设计工具，助力设计师和工程师高效创建复杂几何结构与创新产品。
- 基于 Python，支持参数化建模与算法驱动设计，灵活构建多样化设计方案。  
- 集成多种几何操作，支持布尔运算、网格生成与优化，满足复杂工程需求。  
- 轻量化架构，易于扩展与自定义，兼容主流 CAD 格式，方便与现有设计流程衔接。  
- 开源免费，活跃社区支持，提供丰富示例与文档，促进设计创新与协作。  
- 适用领域涵盖机械设计、建筑建模、三维打印预处理等多场景应用。  
精准、高效、可定制，GenCAD为数字设计注入强大算力。  

[闲鱼智能监控机器人](https://github.com/dingyufei615/ai-goofish-monitor)：一个基于 Playwright 和AI过滤分析的闲鱼多任务实时监控与智能分析工具，配备了功能完善的 Web 管理界面。
项目亮点：
- 可视化Web界面: 提供完整的Web UI，支持任务的可视化管理、AI标准在线编辑、运行日志实时查看和结果筛选浏览，无需直接操作命令行和配置文件。
- AI驱动的任务创建: 只需用自然语言描述你的购买需求，即可一键创建包含复杂筛选逻辑的全新监控任务。
- 多任务并发: 通过 config.json 同时监控多个关键词，各任务独立运行，互不干扰。
- 实时流式处理: 发现新商品后，立即进入分析流程，告别批处理延迟。
- 深度AI分析: 集成多模态大语言模型（如 GPT-4o），结合商品图文和卖家画像进行深度分析，精准筛选。
- 高度可定制: 每个监控任务均可配置独立的关键词、价格范围、筛选条件和AI分析指令 (Prompt)。
- 即时通知: 通过 ntfy.sh 将符合AI推荐的商品立即推送到你的手机或桌面。
- 健壮的反爬策略: 模拟真人操作，包含多种随机延迟和用户行为，提高稳定性。

## 代码工具类
[Tweakcn](https://github.com/jnsahaj/tweakcn): 一款强大的可视化无代码编辑器，专为Shadcn/ui组件和Tailwind CSS设计。它能帮助开发者快速定制UI组件，让网站脱颖而出。
提供超过300种主题预设，快速上手；支持高级自定义，满足个性化需求；集成Tailwind CSS，提升开发效率。

[Shotgun Code](https://github.com/glebkudr/shotgun_code)：一键将代码库“发射”到大语言模型中，解决AI开发中的上下文缺失问题。
 一键生成完整项目结构和文件内容，节省手动整理时间；支持跨平台（Windows、macOS、Linux），适用性广；提供交互式排除功能，可忽略不必要的文件和文件夹，优化上下文。

[Streaming Markdown](https://github.com/thetarnav/streaming-markdown)：一个流式解析Markdown的库，让你像ChatGPT一样实时渲染Markdown内容。
实时渲染，用户可以即时看到Markdown的格式化效果；支持多种Markdown特性，包括代码块、表格、LaTeX等；仅3kB Gzip大小，轻量级且高效。

[aiosqlitepool](https://github.com/slaily/aiosqlitepool)：高效管理 SQLite 连接，提升异步数据库操作性能的轻量级解决方案。
- 纯 Python 实现，专为 asyncio 设计，兼容 Python 3.7+
- 支持连接池管理，自动复用 SQLite 连接，减少连接创建开销。
- 提供简洁 API，支持异步上下文管理，方便集成到异步应用。
- 轻量无依赖，适合 Web 框架、爬虫、微服务等场景。
- 开源项目，持续维护，社区活跃，易于定制扩展。
适合需要高并发 SQLite 操作的 Python 异步开发者。

[Autumn](https://github.com/useautumn/autumn)：开源的Stripe与应用之间的中间层，用几行代码就能实现任意定价模型。
支持订阅、信用系统、按用量计费等多种模式；无需处理复杂的webhook、升级/降级、取消或支付失败问题；提供云服务和自托管两种部署方式。

[AI Doc Gen](https://github.com/divar-ir/ai-doc-gen)：多智能体驱动的代码库自动文档生成系统，提升代码理解与开发者入门效率。
- 多智能体架构：专门的AI agent负责代码结构、数据流、依赖关系、请求流及API分析，确保文档精准全面。  
- 自动文档生成：支持自动创建结构化README，章节可灵活配置，保持文档始终更新且易维护。  
- GitLab集成：无缝接入GitLab，支持自动分析与合并请求创建，优化团队协作流程。  
- 并发处理：多agent并行执行，加速代码分析与文档生成，适应大型项目需求。  
- 多LLM兼容：兼容OpenAI、OpenRouter及本地模型等多种LLM API，灵活选择最佳模型。  
- 配置灵活：基于YAML配置文件，支持环境变量覆盖，满足不同项目定制需求。  
- 可观测性：内置OpenTelemetry和Langfuse监控，实时追踪分析过程，保障系统稳定性。  
- 技术栈前沿：采用Python 3.13与pydantic-ai进行agent编排，结合GitPython和python-gitlab实现仓库操作。  
从根本上解决文档“腐烂”问题，推动文档与代码同步进化，实现长期维护价值最大化。适合追求高效、自动化文档管理的开发团队及开源项目。

[Claude Code Agent Farm](https://github.com/Dicklesworthstone/claude_code_agent_farm)：多Agent协同提升代码质量的自动化框架
- 并行运行20+ Claude Code agents，最高支持50个，极大加速大规模代码库的自动化改进  
- 三大工作流支持：传统Bug修复、系统化最佳实践落地、多Agent协同复杂开发  
- 先进锁机制保障多Agent无冲突作业，自动管理任务分配和状态同步，避免重复和冲突  
- 涵盖34种主流技术栈（Next.js、Python、Rust、Go、Java、Flutter等），配置丰富，适配广泛项目  
- 实时监控面板直观显示Agent状态、上下文使用率、心跳频率及错误信息，支持tmux多视图操作  
- 自动恢复与上下文管理：Agent异常自动重启，自动清理上下文防止状态溢出，支持一键广播清理命令  
- 配套24套环境搭建脚本，覆盖从前端、后端到DevOps及数据工程，极大简化开发环境配置  
- 细粒度Git集成：支持定制分支、增量提交与详尽HTML运行报告，保证代码变更透明且易追踪  
- 灵活JSON配置系统，支持变量替换与动态块大小调整，满足不同项目和团队的个性化需求  
- 安全稳健：自动备份与恢复Claude设置，文件锁定防止并发冲突，异常清理确保环境干净  
该框架不仅是多Agent任务调度工具，更是面向大规模代码库的智能协同开发平台，充分利用AI并行能力与严格的作业协调机制，解决传统自动化工具难以兼顾的代码冲突与任务重复问题，极大提高代码质量和团队开发效率，具备长期演进和多场景复用价值。

## 教程类

[c/c++ interview](https://github.com/huihut/interview): 📚 C/C++ 技术面试基础知识总结，包括语言、程序库、数据结构、算法、系统、网络、链接装载库等知识及面试经验、招聘、内推等信息。

[leetcode-master](https://github.com/youngyangyang04/leetcode-master): 《代码随想录》LeetCode 刷题攻略：200道经典题目刷题顺序。

[kama-DesignPattern](https://github.com/youngyangyang04/kama-DesignPattern?tab=readme-ov-file): 卡码网-23种设计模式精讲。

[all-rl-algorithms](https://github.com/FareedKhan-dev/all-rl-algorithms)：一站式学习强化学习算法的开源宝库。
18种经典强化学习算法实现，覆盖从基础到前沿；配套Jupyter Notebook，交互式学习，边学边改；简洁易懂的代码，零基础也能轻松上手。

[C++面试&C++学习指南](https://github.com/youngyangyang04/TechCPP): 整理了C++后端研发工程师面试和工作必备的知识点 。

[Transformers Breakdown](https://www.k-a.in/transformers.html)：深入剖析Transformer架构的代码解析项目。
逐行解读Transformer代码，适合初学者快速上手；使用PyTorch实现，代码简洁易懂；包含从输入嵌入到完整Transformer模型的详细解析。

[A Visual Exploration of Gaussian Processes](https://distill.pub/2019/visual-exploration-gaussian-processes/)：用直观可视化方式探索高斯过程的奥秘。
通过交互式图表和实例，让复杂的数学概念变得易于理解；深入浅出地讲解高斯过程在回归问题中的应用；提供丰富的核函数示例，帮助用户更好地配置模型。

[web-rl-playground](https://github.com/awjuliani/web-rl-playground)：一个基于网页的强化学习算法互动演示平台，让初学者轻松上手RL。
支持多种经典RL算法（如Q-Learning、SARSA等），多达6种算法可选；提供丰富的可视化功能，包括状态价值、策略展示和学习进度图表；界面简洁，支持自定义网格世界，操作简单易上手。

[Happy-LLM](https://github.com/datawhalechina/happy-llm)：从零开始的大语言模型原理与实践教程，带你深入探索LLM的世界。
系统性教程，从NLP基础到LLaMA2实现；动手实践，涵盖预训练到微调全流程；结合前沿技术，如RAG和Agent。

[大厂大模型算法岗常考题汇总](https://github.com/yang19527/AwesomeInterview): 汇集海量面试资料，助你高效备考，提升求职竞争力  
- 覆盖编程语言、算法、系统设计、操作系统、数据库、网络、安全等多个技术领域  
- 精选经典面试题与详解，涵盖初级到高级难度，适合不同阶段求职者  
- 收录各大互联网公司真题及面试经验分享，助你把握行业趋势与面试重点  
- 持续更新，社区活跃，支持贡献与交流，打造动态学习平台

[AI-ML-Cheatsheets](https://github.com/analyticalrohit/AI-ML-Cheatsheets): AI/ML 速查手册合集，助力数据科学家与机器学习工程师提升效率与准确性：
- 涵盖机器学习、深度学习、自然语言处理、计算机视觉等核心领域。
- 多语言支持，包含 Python、R、TensorFlow、PyTorch 等主流框架关键知识点。
- 结构清晰，重点突出，便于快速查阅算法原理、模型调优与代码示例。
- 适合初学者入门与资深工程师复习，极大缩短问题定位与解决时间。
- 开源免费，持续更新，社区贡献内容丰富，紧跟技术前沿。

[Statistical Machine Learning for Astronomy](https://arxiv.org/abs/2506.12230) ：一本为天文研究量身打造的统计机器学习教材。核心价值在于通过贝叶斯推断视角，系统地将现代数据分析技术与传统统计方法相结合，为天文研究提供坚实的统计基础。
从概率论到神经网络，逐步构建从经典到现代的统计框架；强调不确定性量化和统计严谨性，助力科学推断；包含677页内容和152幅图表，提供丰富的代码和教程资源。

[kubernetes-for-ml-engineers](https://github.com/Paulescu/kubernetes-for-ml-engineers)：专为机器学习工程师量身打造的Kubernetes入门指南。
仅需几步即可快速搭建本地Kubernetes集群；提供详细的FastAPI应用部署示例，从零到运行仅需9步；代码和配置清晰易懂，适合新手快速上手。

[The Algorithm](https://the-algorithms.com) ：GitHub上最大的算法开源库之一，提供Python实现的各类算法，包括排序、搜索、动态规划等，适合开发者学习和实践。网站提供代码自动补全、语法高亮、交互式编程体验，支持多种编程语言学习。

## 论文与项目整合类

[os-catalog](https://github.com/prathyvsh/os-catalog)：汇聚新型操作系统的宝库，帮你一站式了解前沿的系统创新。
收录了众多小众且极具创意的操作系统；提供丰富的系统截图和详细描述，直观感受系统魅力；从桌面到移动，覆盖多种平台的创新系统。

[Awesome-LLM-Scientific-Discovery](https://github.com/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery)：汇集大型语言模型（LLM）在科学研究中的前沿论文、工具和资源。它为研究人员、开发者和爱好者提供了一个全面的概览，助力探索LLM在科学发现中的应用。
从自动化到自主化的三级框架，清晰划分LLM在科学研究中的角色；涵盖从文献综述到实验规划、数据分析再到假设验证的全流程；提供丰富的研究论文和工具资源，助力快速入门和深入研究。

[Awesome-Blackhat-Tools](https://github.com/UCYBERS/Awesome-Blackhat-Tools): 汇集全球顶级黑客大会官方展示的实用网络安全工具。
涵盖红队、蓝队、应用安全等多领域工具；按地区、年份、类别精细分类，查找方便；提供工具详细信息，助力安全专家高效应用。

[Awesome-Style-Transfer-with-Diffusion-Models](https://github.com/Westlake-AGI-Lab/Awesome-Style-Transfer-with-Diffusion-Models)：一个精心整理的扩散模型风格迁移方法列表，助力图像和视频风格化难题。
涵盖图像合成、视频合成、3D生成等多个领域；提供多种风格迁移方法，包括基于文本和图像的驱动方式；汇集了超过50种最新研究成果。

[AgentsMeetRL](https://github.com/thinkwee/AgentsMeetRL)：一个超实用的开源项目集合，专门整理了基于强化学习训练LLM Agent的开源资源。
涵盖多领域项目，包括数学、搜索、对话等；涉及多种强化学习框架和算法；提供详细的项目信息，方便开发者快速上手。

[best-of-robot-simulators](https://github.com/knmcguire/best-of-robot-simulators)：为机器人仿真领域提供了一份精心整理的优质项目榜单。
涵盖83个开源项目；涉及9大类别，从通用机器人仿真器到AI训练仿真器一应俱全；定期更新，保持最新资讯

[awesome-VLLMs](https://github.com/JackYFL/awesome-VLLMs)：汇集视觉语言大模型（VLLMs）应用的资源库。
涵盖从基础研究到实际应用的广泛论文；持续更新，紧跟最新研究动态；提供跨领域的应用案例，助力多场景落地。

[Awesome-AI-Scientist](https://github.com/ResearAI/Awesome-AI-Scientist)：为AI科学家、研究人员和工程师提供一站式研究资源导航。
汇集了超过500篇AI研究论文和工具；涵盖从知识构建到论文写作的全流程AI辅助；提供多个研究自动化基准测试和社区讨论平台。

[Awesome-Unified-Multimodal-Models](https://github.com/AIDC-AI/Awesome-Unified-Multimodal-Models)：一站式汇聚前沿多模态统一模型资源，助力研究人员和开发者快速掌握领域动态。
涵盖2023年至2025年的最新多模态模型，紧跟技术前沿；提供丰富论文、数据集和评估基准，资源全面；细分多种模型架构与任务类型，便于精准定位需求。

[Awesome-video-super-resolution-diffusion](https://github.com/yjsunnn/Awesome-video-super-resolution-diffusion)：视频超分辨率领域的资源库。它为研究者和开发者提供了一站式的视频超分辨率（VSR）资源，涵盖论文、开源代码和数据集。
收集了2024-2025年最新的VSR研究成果；提供多个高质量数据集，如OpenVid-1M（100万视频对）和WebVid-2M（250万文本-视频对）；一站式资源，方便查找和使用。

[awesome-bfm-papers](https://github.com/yuanmingqi/awesome-bfm-papers)：行为基础模型（BFM）领域的精选资源宝库。它汇集了前沿的学术论文、教程、代码和项目，为研究者和开发者提供一站式的学习和研究平台。
涵盖多个研究方向，包括预训练、目标驱动学习、内在奖励驱动学习等；提供丰富的代码和教程资源，助力快速上手；持续更新，紧跟学术前沿动态。

[awesome-isaac-sim](https://github.com/sjtuyinjie/awesome-isaac-sim)：NVIDIA Isaac Sim资源大集合，助力机器人仿真与AI研究。
汇集了从Isaac Gym到Isaac Sim的丰富资源；包含多篇顶级会议论文及代码；提供官方教程与仿真框架。

[Awesome-VLA-Papers](https://github.com/Psi-Robot/Awesome-VLA-Papers)：汇集了视觉-语言-行动（VLA）模型领域的经典论文和相关资源。
涵盖从基础模型到前沿应用的广泛内容；提供详细的研究分类，便于快速定位；包含语言、视觉和机器人操作等多个领域的最新进展。

[Awesome Long-Chain-of-Thought Reasoning with Tools](https://github.com/ChengpengLi1003/Awesome-Long-Chain-of-Thought-Reasoning-with-tools)：全面掌握长链思维推理工具的精选资源合集，助力复杂推理与多步骤任务的高效解决💡
- 汇聚当前最前沿的长链思维推理方法与工具，涵盖理论框架、开源代码及实用示例。  
- 包含多种可集成的推理工具，支持多步逻辑推导与复杂问题分解，提升模型推理能力。  
- 资源涵盖自然语言处理、知识图谱、自动化推理等多个领域，适合研究者与开发者深入探索。  
- 持续更新，整合社区贡献，助力构建更强大的智能推理系统。  
- 开源项目，方便快速上手，支持二次开发与个性化定制。

[Open UI](https://github.com/openui/open-ui)：Open UI 是一个致力于推动用户界面（UI）开放标准的社区项目，旨在通过研究和规划，改进网页表单控件及其他网站级 UI 控件的设计、样式和行为。它通过记录流行第三方框架中的通用组件模式，并结合 HTML、CSS、JavaScript 和 Web API 技术，为开发者提供更强大的底层架构支持。Open UI 的愿景是帮助开发者创建现代自定义用户界面，同时确保其可访问性、性能和安全性。该项目通过向 WHATWG、CSSWG 等标准组织提交改进建议，推动相关技术的标准化和浏览器实现。

## AI部署
[SmolVLM-realtime-webcam](https://github.com/ngxson/smolvlm-realtime-webcam)：实时摄像头目标检测的高效解决方案。
基于SmolVLM 500M模型，实时性极强；通过llama.cpp服务器轻松部署；支持GPU加速，性能大幅提升。

[EmbodiedGen](https://github.com/HorizonRobotics/EmbodiedGen)：一个生成3D世界引擎的工具包，能够利用生成式AI创建多样化的3D资产和场景。
支持从图像和文本生成3D模型；提供丰富的纹理生成功能；涵盖从场景到布局的多模块生成能力。

[memvid-rs](https://github.com/AllenDang/memvid-rs)：它将文本文件转化为视频文件，通过QR码和神经网络语义检索，实现高效存储和精准搜索。
150倍以上GPU加速，M1 Max仅需9秒完成编码；100%语义搜索准确率，完美理解“比特币发明者”等复杂问题；零依赖单二进制文件，跨平台部署，支持多种文件格式。

[OpenMusic](https://github.com/ivcylc/OpenMusic)：前沿的文本到音乐生成项目，让音乐创作变得轻而易举。
零样本长音乐生成，无需额外训练即可创作无限时长音乐；支持多种训练策略，满足不同需求；提供详细的训练和推理教程，新手也能快速上手。

[plamo-translate-cli](https://github.com/pfnet/plamo-translate-cli): 一款强大的本地化翻译命令行工具，基于plamo-2-translate模型，支持16+种语言互译，轻松集成到脚本和工作流中。

[docext](https://github.com/NanoNets/docext): 一款无需OCR的本地部署文档信息提取工具，通过视觉语言模型轻松提取文档中的结构化信息。
完全本地化部署，保障数据隐私；支持多页文档处理，满足复杂文件需求；提供REST API接口，方便与现有系统集成。

[ContextGem](https://github.com/shcherbak-ai/contextgem)：让从文档中提取结构化数据变得轻而易举的LLM框架。
自动化动态提示，无需手动编写复杂代码；提供强大的数据建模和验证功能，减少开发时间；支持多语言输入输出，无需额外提示。


[MoviiGen 1.1](https://github.com/ZulutionAI/MoviiGen1.1)：打造电影级画质的视频生成模型，让视频创作更专业、更高效。
超越竞品的电影美学表现，尤其在氛围营造、镜头运动和细节保留上表现卓越；清晰度提升14.6%，真实感增强4.3%，适合高保真场景；支持720P和1080P分辨率，保持高质量输出。

[seed-Prover](https://github.com/ByteDance-Seed/Seed-Prover)，聚焦数学自动定理证明的前沿突破：
- Seed-Prover 是团队参与 IMO 2025 国际数学奥林匹克的官方系统，成功解决 4 道难题（P2 几何、P3 数论、P4 数论、P5 组合/代数），展示了 AI 在严谨数学证明中的实用性和高效性。  
- P2 题几何证明仅用 2 秒生成并验证，P3 和 P4 题的数论证明分别用 Lean 形式化语言完成，代码行数达 2000 和 4000 行，体现深度形式化能力。  
- P5 题的证明创新性强，算法生成的证明与人类传统解法存在差异，体现 AI 方法在数学创新上的潜力。  
- 另有 Delta-Prover 项目，专注于测试时生成形式证明的技术研究，推动自动化数学系统的性能极限。  
- 全部证明基于 Lean v4.14.0，采用 Apache-2.0 开源许可，方便社区复用与二次开发。  
Seed-Prover 不仅是数学 AI 形式化证明的里程碑，也为数学研究方法论带来新的视角，推动数学与人工智能深度融合。长期来看，这类工具将成为数学家、科研人员的强力助手，实现复杂数学问题的自动验证和创新发现。

## 全模态·语音与声纹

涵盖 TTS（文字转语音）、SVC（声音转换）、音频处理等方向。

### TTS 文字转语音

[fish-speech](https://github.com/fishaudio/fish-speech)：SOTA 开源 TTS 模型，支持零样本克隆和多语言合成。
基于自回归变换器架构，结合 LLaMA 风格的语言模型与音频解码器；支持中文、英文、日文等多语言；提供高效的推理工具和预训练模型，适合需要高质量语音合成的应用场景。

[vits2](https://github.com/daniilrobnikov/vits2)：VITS2 的非官方实现，通过对抗学习和架构设计提升单阶段 TTS 的质量与效率。
改进的单阶段模型设计，解决传统两阶段系统的复杂性问题；支持多说话人建模，保持语音特征相似度；降低对音素转换的依赖，实现更端到端的语音合成；提供官方 Demo 和论文参考，适合研究者和开发者探索高质量 TTS。

### SVC 声音转换

[so-vits-svc](https://github.com/svc-develop-team/so-vits-svc)：SoftVC VITS 歌声转换模型，让歌声风格转换变得简单。
专注歌声转换（SVC）而非 TTS，支持将一种音色/风格的歌声转换为另一种；基于 SoftVC 特征提取和 VITS 声学模型；提供可视化编辑器、说话人混合时间轴等功能；社区活跃，有多个衍生项目（如 MoeVoiceStudio、voice-changer）提供更好用的 UI 和实时转换能力。

[DragonianVoice](https://github.com/PriesiaMioShirakana/DragonianVoice)：多个 SVC/TTS 模型的 C++ 推理库，提供高效的本地部署方案。
一站式支持多种主流模型：TTS（Vits、EmotionalVits、BERTVits2、GPtSoVits）和 SVC（SoVitsSvc、RVC、DiffusionSvc、FishDiffusion、ReflowSvc）；基于 ONNX 框架，支持 C/C++/C# 调用；与 fish-speech 联动提供 ggml 版本的 fish-speech.cpp；适合需要高性能本地推理的应用场景。

### 音频处理工具

[audio-slicer](https://github.com/flutydeer/audio-slicer)：简洁高效的音频切片工具，基于静音检测自动分割音频。
提供 GUI 界面，操作直观；支持自定义静音阈值、最小/最大片段长度等参数；适合为 TTS/SVC 训练准备数据集，将长音频自动切分为适合的短片段；Python 实现，依赖简洁，易于集成到工作流。
