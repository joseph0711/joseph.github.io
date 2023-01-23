---
title: "如何在Github建立Codespace"
date: "2023-01-23"
tags:
    - github
    - codespace
comments: true
excerpt: "此篇文章將導引您在Github建立Codespace及相關設定。"
---

## 本篇重點
- What is Github Codespace
- Pricing for Github Codespace
- 如何在Repository新增
- 如何與本地端IDE或終端機連結Github Codespace

## 問題背景
- 過往開發總是在本地端做開發，再透過其他套件(Ex. Docker Image)來部署至雲端。
- 為了使開發流程朝向雲端化，而有了使用Github Codespace的動機。

## What is Github Codespace?
- Github Codespace是由Github公司所發展出的服務，將開發環境放置在雲端上。可透過Repository去新增一個Codespace，約莫等待1-2分鐘系統設定後，即可使用線上版的VS Code線上編輯器。

- 當建立一個Github Codespace時，背景會建立一個Linux 由 Github 控管的 Docker container，而VS code也會相對應的自動新增相關開發工具。若有其他Linux版本的需求，可透過其他方式去做客製化。

- 以下為Github Codespace流程圖，若有興趣可至官方文件參考。
![alt](/assets/images/GithubCodespace/codespaces-diagram.png)

## Pricing for Github Codespace
- 個人使用基本上皆為免費，但每個月皆有quota上限，如下表。

| 方案                 | 每月儲存空間上限    | 每月核心使用時數上限 |
| ------------------ | ----------- | ---------- |
| 個人Github Codespace | 15 GB-month | 120        |


## 如何在Repository新增
- 僅需在Reposiory右上角點選`Code`，再點選`Create Codespace on main`即可新增。

## 如何與本地端IDE或終端機連結Github Codespace
可參考以下連結。
- [Visual Studio Code x Github Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/using-github-codespaces-in-visual-studio-code#prerequisites)

- [JetBrains IDEs x Github Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/using-github-codespaces-in-your-jetbrains-ide#prerequisites)

- [Github CLI](https://docs.github.com/en/codespaces/developing-in-codespaces/using-github-codespaces-with-github-cli#using-github-cli)