# 等鸟 · 观鸟社区体验版

谐音"候鸟"，"等"字对应实时蹲守。中国新手观鸟者的「实时鸟讯地图 + 鸟讯审核」社区小程序。

- 体验版入口（Cloudflare Pages）：https://dengniao1.pages.dev/
- 产品方案：.claude/观鸟产品/产品方案.md（仓库外，仅内部）
- 体验版为内置演示数据（33 种鸟、16 条鸟讯、22 条手册记录），地图需联网加载

## 更新体验版

编辑 `demo/index.html` 后运行 `scripts/make_experience_copy.py`，将生成的
`demo/public/index.html` 复制到本目录，提交推送即可。
