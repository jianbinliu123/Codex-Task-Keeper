# Codex Task Keeper | Codex任务守护器
Codex任务守护器是一款Windows桌面工具，实时监控Codex任务状态:当任务意外暂停时（如遇到model is at capacity、Error running remote compact task等），程序会自动恢复运行，并支持定时中断、后台运行和连续失败保护，帮助用户在/goal模式下无人工介入地、更稳定地运行长时间 Codex 任务。

<p align="center">
  <img src="assets/image.png" alt="CodexTaskKeeper界面" style="max-width: 100%;">
  <br>
  <span style="color: #888888; font-size: 14px;">图：Codex Task Keeper 软件界面</span>
</p>


## 📚 更新记录

<details open>
<summary><strong>🔹 v1.0.0</strong> · 2026-09-08 <span style="color: #2d8cf0; font-weight: bold;">最新</span></summary>

<br>
<strong>✨ 新增功能</strong>
<ul>
  <li>定时中断：支持设定本机守护时间，到时自动中断任务。</li>
  <li>连续失败保护：连续恢复失败 5 次后自动停止，防止死循环。</li>
</ul>
</details>
