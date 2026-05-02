Ao-Agent/
├── README.md
├── docs/
│   ├── architecture.md
│   ├── soul-prompt.md      # 阿鳌的灵魂设定
│   └── deployment.md
├── src/
│   ├── core/
│   │   ├── agent.js
│   │   ├── emotion.js      # 情感分析模块
│   │   └── memory.js       # 长期记忆管理
│   ├── modules/
│   │   ├── economic.js     # 经济洞察模块
│   │   └── scheduler.js    # 定时任务管理
│   └── channels/
│       └── wechat.js       # 微信接入适配
├── config/
│   └── default.yaml
└── scripts/
    └── deploy.sh
