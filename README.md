# 平铺窗口管理器

## 项目名称

实现一个简单的平铺式管理的Wayland合成器

## 项目描述

实现一个 Wayland 合成器项目，使用平铺式的窗口布局策略来管理窗口的位置和大小，仅要求支持 XDG Shell 协议，对 XWayland 程序不做要求。

1. 可参照任意已有的平铺式窗口管理器的行为，比如 i3、sway、hyprland 等
2. 可使用基本的开发库作为底层实现，如 wlroots

## 项目导师

张丁元 `<zhangdingyuan@uniontech.com>`

## 赛题分类
未归类运行时支撑

## 难度

高

## 参考文档

1. https://wayland-book.com/
2. https://wayland.freedesktop.org/

## 预期目标

程序运行后自动展示一个终端窗口，在终端窗口中输入命令可启动其它程序，新打开的Wayland窗口与已有的窗口无遮挡

## 从题目中能学到什么

1. Wayland的架构设计和工作原理
2. 窗口管理的本质
3. Linux图形程序方面的基本知识

## 涉及领域

1. Linux DRM
2. Wayland
