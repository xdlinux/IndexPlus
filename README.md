IndexPlus
====
西电开源社区网站首页雏型，旨在整合西电开源社区网络资源

Feature
---
目前仅包括软件源部分

* 正在同步的软件源图表会有一圈淡绿色,背景为淡黄色
* 同步失败了会有明显的红色
* 鼠标移到图标上会有详细信息，包括软件仓库链接，查看日志，上游源和上次同步时间，预留了Description字段
* 全部是静态代码，软件源同步完成后写到 http://xdlinux.info/m_status.json ，前端通过AJAX进行数据交互

Todo
---
* 通过RSS 整合 BBS, Wiki, Github 信息
* 与 xdtuxbot 增加数据交互
* 一个简单的信息发布系统

License
---
COPYRIGHT (c) Xidian Open Source Community < xdl@xdlinux.info >

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
