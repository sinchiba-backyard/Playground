# Playground
メンバー内のテスト用

- [レの遊び場](レの遊び場.md)

gantt
dateFormat  YYYY-MM-DD
title Gantt チャート

section Aセクション
完了タスク            :done,    des1, 2022-01-06,2022-01-08
進行タスク            :active,  des2, 2022-01-09, 3d
将来タスク            :         des3, after des2, 5d
将来タスク 2          :         des4, after des3, 5d

section Bセクション
完了タスク           :done,    des1, 2022-01-06,2022-01-08
将来タスク           :         des3, after des1, 5d
将来タスク 2         :         des4, after des3, 5d
