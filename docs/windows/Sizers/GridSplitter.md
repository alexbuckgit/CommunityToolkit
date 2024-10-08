---
title: GridSplitter
author: michael-hawker
description: The GridSplitter control provides an easy-to-use Splitter that redistributes space between columns or rows of a Grid Control.
keywords: ContentSizer, SizerBase, Control, Layout, Expander
dev_langs:
  - csharp
category: Controls
subcategory: Sizers
discussion-id: 96
issue-id: 101
icon: Assets/GridSplitter.png
---

# GridSplitter

The control automatically detects the targeted columns/rows to resize, while dragging the control it starts to resize the columns/rows and redistributes space between columns/rows,
you can manually specify the `ResizeDirection` (`Auto` / `Column` / `Row`) and the `ResizeBehavior` to select which columns/rows to resize.

`GridSplitter` control will resize the targeted rows or columns

:::code language="xaml" source="~/../code-windows/components/Sizers/samples/GridSplitterPage.xaml":::

:::code language="csharp" source="~/../code-windows/components/Sizers/samples/GridSplitterPage.xaml.cs":::


