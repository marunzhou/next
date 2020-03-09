{"title":"标题","meta":{"title":"标题","description":"\n<p>展示不同级别的标题。</p>\n","order":"1"},"codes":{"jsx":"import { Typography } from '@alifd/next';\n\nconst { H1, H2, H3, H4, H5, H6 } = Typography;\n\nReactDOM.render(\n  <div>\n    <H1>h1. Fusion Design</H1>\n    <H2>h2. Fusion Design</H2>\n    <H3>h3. Fusion Design</H3>\n    <H4>h4. Fusion Design</H4>\n    <H5>h5. Fusion Design</H5>\n    <H6>h6. Fusion Design</H6>\n  </div>,\n  mountNode,\n);\n"},"body":"\n\n```jsx\nimport { Typography } from '@alifd/next';\n\nconst { H1, H2, H3, H4, H5, H6 } = Typography;\n\nReactDOM.render(\n  <div>\n    <H1>h1. Fusion Design</H1>\n    <H2>h2. Fusion Design</H2>\n    <H3>h3. Fusion Design</H3>\n    <H4>h4. Fusion Design</H4>\n    <H5>h5. Fusion Design</H5>\n    <H6>h6. Fusion Design</H6>\n  </div>,\n  mountNode,\n);\n```","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar H1 = _next.Typography.H1,\n    H2 = _next.Typography.H2,\n    H3 = _next.Typography.H3,\n    H4 = _next.Typography.H4,\n    H5 = _next.Typography.H5,\n    H6 = _next.Typography.H6;\n\n\nReactDOM.render(React.createElement(\n  'div',\n  null,\n  React.createElement(\n    H1,\n    null,\n    'h1. Fusion Design'\n  ),\n  React.createElement(\n    H2,\n    null,\n    'h2. Fusion Design'\n  ),\n  React.createElement(\n    H3,\n    null,\n    'h3. Fusion Design'\n  ),\n  React.createElement(\n    H4,\n    null,\n    'h4. Fusion Design'\n  ),\n  React.createElement(\n    H5,\n    null,\n    'h5. Fusion Design'\n  ),\n  React.createElement(\n    H6,\n    null,\n    'h6. Fusion Design'\n  )\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Typography <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n<span class=\"token keyword\">const</span> <span class=\"token punctuation\">{</span> <span class=\"token constant\">H1</span><span class=\"token punctuation\">,</span> <span class=\"token constant\">H2</span><span class=\"token punctuation\">,</span> <span class=\"token constant\">H3</span><span class=\"token punctuation\">,</span> <span class=\"token constant\">H4</span><span class=\"token punctuation\">,</span> <span class=\"token constant\">H5</span><span class=\"token punctuation\">,</span> <span class=\"token constant\">H6</span> <span class=\"token punctuation\">}</span> <span class=\"token operator\">=</span> Typography<span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n  <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">H1</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">h1. Fusion Design</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">H1</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">H2</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">h2. Fusion Design</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">H2</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">H3</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">h3. Fusion Design</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">H3</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">H4</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">h4. Fusion Design</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">H4</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">H5</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">h5. Fusion Design</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">H5</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span><span class=\"token class-name\">H6</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">h6. Fusion Design</span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span><span class=\"token class-name\">H6</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n  </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span>\n  mountNode<span class=\"token punctuation\">,</span>\n<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}