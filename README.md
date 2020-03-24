# Python in Docker

Overview

Pythonインストール済みのイメージです。
VSCodeでPythonの開発環境を構築するため、Black、Flake8などの
パッケージやVsCodeの拡張機能などをDocker起動時にインストールします。

Quick Start

1. VsCodeで「Ctrl + Shift + P」を押下
1. 「Remote-Containers: Open Folder in Container」と入力
1. python-in-dockerをCloneしたディレクトリを選択
1. Dockerが起動して、Pythonが使用可能になる

## Vscode-extend

| extend                                        | role                       |
| --------------------------------------------- | -------------------------- |
| Japanese Language Pack for Visual Studio Code | Japanese Language Display  |
| Python                                        | Can Use Python             |
| Apel for python                               | Real Time Debug for Python |

## Python-Package

| Package | role      |
| ------- | --------- |
| black   | Formatter |
| flake8  | Linter    |