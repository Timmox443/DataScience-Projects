<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>loan_default_predicition</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>




<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>



<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
  scrollbar-width: thin;
}

/*
 * Webkit scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-corner {
  background: var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-thumb {
  background: rgb(var(--jp-scrollbar-thumb-color));
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-right: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-bottom: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar */

[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-corner,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-corner {
  background-color: transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-thumb,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid transparent;
  border-right: var(--jp-scrollbar-endpad) solid transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid transparent;
  border-bottom: var(--jp-scrollbar-endpad) solid transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny::-webkit-scrollbar,
.jp-scrollbar-tiny::-webkit-scrollbar-corner {
  background-color: transparent;
  height: 4px;
  width: 4px;
}

.jp-scrollbar-tiny::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:horizontal {
  border-left: 0px solid transparent;
  border-right: 0px solid transparent;
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:vertical {
  border-top: 0px solid transparent;
  border-bottom: 0px solid transparent;
}

/*
 * Phosphor
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Widget, /* </DEPRECATED> */
.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  cursor: default;
}


/* <DEPRECATED> */ .p-Widget.p-mod-hidden, /* </DEPRECATED> */
.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-CommandPalette, /* </DEPRECATED> */
.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-CommandPalette-search, /* </DEPRECATED> */
.lm-CommandPalette-search {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-content, /* </DEPRECATED> */
.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-CommandPalette-header, /* </DEPRECATED> */
.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}


/* <DEPRECATED> */ .p-CommandPalette-item, /* </DEPRECATED> */
.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}


/* <DEPRECATED> */ .p-CommandPalette-itemIcon, /* </DEPRECATED> */
.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemContent, /* </DEPRECATED> */
.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}


/* <DEPRECATED> */ .p-CommandPalette-itemShortcut, /* </DEPRECATED> */
.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemLabel, /* </DEPRECATED> */
.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-close-icon {
	border:1px solid transparent;
  background-color: transparent;
  position: absolute;
	z-index:1;
	right:3%;
	top: 0;
	bottom: 0;
	margin: auto;
	padding: 7px 0;
	display: none;
	vertical-align: middle;
  outline: 0;
  cursor: pointer;
}
.lm-close-icon:after {
	content: "X";
	display: block;
	width: 15px;
	height: 15px;
	text-align: center;
	color:#000;
	font-weight: normal;
	font-size: 12px;
	cursor: pointer;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-DockPanel, /* </DEPRECATED> */
.lm-DockPanel {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-widget, /* </DEPRECATED> */
.lm-DockPanel-widget {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-tabBar, /* </DEPRECATED> */
.lm-DockPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-DockPanel-handle, /* </DEPRECATED> */
.lm-DockPanel-handle {
  z-index: 2;
}


/* <DEPRECATED> */ .p-DockPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-DockPanel-handle:after, /* </DEPRECATED> */
.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}


/* <DEPRECATED> */ .p-DockPanel-overlay, /* </DEPRECATED> */
.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}


/* <DEPRECATED> */ .p-DockPanel-overlay.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Menu, /* </DEPRECATED> */
.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-Menu-content, /* </DEPRECATED> */
.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-Menu-item, /* </DEPRECATED> */
.lm-Menu-item {
  display: table-row;
}


/* <DEPRECATED> */
.p-Menu-item.p-mod-hidden,
.p-Menu-item.p-mod-collapsed,
/* </DEPRECATED> */
.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}


/* <DEPRECATED> */
.p-Menu-itemIcon,
.p-Menu-itemSubmenuIcon,
/* </DEPRECATED> */
.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}


/* <DEPRECATED> */ .p-Menu-itemLabel, /* </DEPRECATED> */
.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}


/* <DEPRECATED> */ .p-Menu-itemShortcut, /* </DEPRECATED> */
.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-MenuBar, /* </DEPRECATED> */
.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-MenuBar-content, /* </DEPRECATED> */
.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}


/* <DEPRECATED> */ .p--MenuBar-item, /* </DEPRECATED> */
.lm-MenuBar-item {
  box-sizing: border-box;
}


/* <DEPRECATED> */
.p-MenuBar-itemIcon,
.p-MenuBar-itemLabel,
/* </DEPRECATED> */
.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-ScrollBar, /* </DEPRECATED> */
.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-ScrollBar-button, /* </DEPRECATED> */
.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-track, /* </DEPRECATED> */
.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-thumb, /* </DEPRECATED> */
.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-SplitPanel-child, /* </DEPRECATED> */
.lm-SplitPanel-child {
  z-index: 0;
}


/* <DEPRECATED> */ .p-SplitPanel-handle, /* </DEPRECATED> */
.lm-SplitPanel-handle {
  z-index: 1;
}


/* <DEPRECATED> */ .p-SplitPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-SplitPanel-handle:after, /* </DEPRECATED> */
.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabBar, /* </DEPRECATED> */
.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='horizontal'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
  align-items: flex-end;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='vertical'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
  align-items: flex-end;
}


/* <DEPRECATED> */ .p-TabBar-content, /* </DEPRECATED> */
.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='horizontal'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='vertical'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
}


/* <DEPRECATED> */
.p-TabBar-tabIcon,
.p-TabBar-tabCloseIcon,
/* </DEPRECATED> */
.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-TabBar-tabLabel, /* </DEPRECATED> */
.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}


.lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing : border-box;
}


/* <DEPRECATED> */ .p-TabBar-tab.p-mod-hidden, /* </DEPRECATED> */
.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}


.lm-TabBar-addButton.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-TabBar.p-mod-dragging .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='horizontal'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='vertical'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging .p-TabBar-tab.p-mod-dragging,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

.lm-TabBar-tabLabel .lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing : border-box;
  background: inherit;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabPanel-tabBar, /* </DEPRECATED> */
.lm-TabPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-TabPanel-stackedPanel, /* </DEPRECATED> */
.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

@charset "UTF-8";
html{
  -webkit-box-sizing:border-box;
          box-sizing:border-box; }

*,
*::before,
*::after{
  -webkit-box-sizing:inherit;
          box-sizing:inherit; }

body{
  font-size:14px;
  font-weight:400;
  letter-spacing:0;
  line-height:1.28581;
  text-transform:none;
  color:#182026;
  font-family:-apple-system, "BlinkMacSystemFont", "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Open Sans", "Helvetica Neue", "Icons16", sans-serif; }

p{
  margin-bottom:10px;
  margin-top:0; }

small{
  font-size:12px; }

strong{
  font-weight:600; }

::-moz-selection{
  background:rgba(125, 188, 255, 0.6); }

::selection{
  background:rgba(125, 188, 255, 0.6); }
.bp3-heading{
  color:#182026;
  font-weight:600;
  margin:0 0 10px;
  padding:0; }
  .bp3-dark .bp3-heading{
    color:#f5f8fa; }

h1.bp3-heading, .bp3-running-text h1{
  font-size:36px;
  line-height:40px; }

h2.bp3-heading, .bp3-running-text h2{
  font-size:28px;
  line-height:32px; }

h3.bp3-heading, .bp3-running-text h3{
  font-size:22px;
  line-height:25px; }

h4.bp3-heading, .bp3-running-text h4{
  font-size:18px;
  line-height:21px; }

h5.bp3-heading, .bp3-running-text h5{
  font-size:16px;
  line-height:19px; }

h6.bp3-heading, .bp3-running-text h6{
  font-size:14px;
  line-height:16px; }
.bp3-ui-text{
  font-size:14px;
  font-weight:400;
  letter-spacing:0;
  line-height:1.28581;
  text-transform:none; }

.bp3-monospace-text{
  font-family:monospace;
  text-transform:none; }

.bp3-text-muted{
  color:#5c7080; }
  .bp3-dark .bp3-text-muted{
    color:#a7b6c2; }

.bp3-text-disabled{
  color:rgba(92, 112, 128, 0.6); }
  .bp3-dark .bp3-text-disabled{
    color:rgba(167, 182, 194, 0.6); }

.bp3-text-overflow-ellipsis{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal; }
.bp3-running-text{
  font-size:14px;
  line-height:1.5; }
  .bp3-running-text h1{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h1{
      color:#f5f8fa; }
  .bp3-running-text h2{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h2{
      color:#f5f8fa; }
  .bp3-running-text h3{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h3{
      color:#f5f8fa; }
  .bp3-running-text h4{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h4{
      color:#f5f8fa; }
  .bp3-running-text h5{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h5{
      color:#f5f8fa; }
  .bp3-running-text h6{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h6{
      color:#f5f8fa; }
  .bp3-running-text hr{
    border:none;
    border-bottom:1px solid rgba(16, 22, 26, 0.15);
    margin:20px 0; }
    .bp3-dark .bp3-running-text hr{
      border-color:rgba(255, 255, 255, 0.15); }
  .bp3-running-text p{
    margin:0 0 10px;
    padding:0; }

.bp3-text-large{
  font-size:16px; }

.bp3-text-small{
  font-size:12px; }
a{
  color:#106ba3;
  text-decoration:none; }
  a:hover{
    color:#106ba3;
    cursor:pointer;
    text-decoration:underline; }
  a .bp3-icon, a .bp3-icon-standard, a .bp3-icon-large{
    color:inherit; }
  a code,
  .bp3-dark a code{
    color:inherit; }
  .bp3-dark a,
  .bp3-dark a:hover{
    color:#48aff0; }
    .bp3-dark a .bp3-icon, .bp3-dark a .bp3-icon-standard, .bp3-dark a .bp3-icon-large,
    .bp3-dark a:hover .bp3-icon,
    .bp3-dark a:hover .bp3-icon-standard,
    .bp3-dark a:hover .bp3-icon-large{
      color:inherit; }
.bp3-running-text code, .bp3-code{
  font-family:monospace;
  text-transform:none;
  background:rgba(255, 255, 255, 0.7);
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
  color:#5c7080;
  font-size:smaller;
  padding:2px 5px; }
  .bp3-dark .bp3-running-text code, .bp3-running-text .bp3-dark code, .bp3-dark .bp3-code{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#a7b6c2; }
  .bp3-running-text a > code, a > .bp3-code{
    color:#137cbd; }
    .bp3-dark .bp3-running-text a > code, .bp3-running-text .bp3-dark a > code, .bp3-dark a > .bp3-code{
      color:inherit; }

.bp3-running-text pre, .bp3-code-block{
  font-family:monospace;
  text-transform:none;
  background:rgba(255, 255, 255, 0.7);
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
  color:#182026;
  display:block;
  font-size:13px;
  line-height:1.4;
  margin:10px 0;
  padding:13px 15px 12px;
  word-break:break-all;
  word-wrap:break-word; }
  .bp3-dark .bp3-running-text pre, .bp3-running-text .bp3-dark pre, .bp3-dark .bp3-code-block{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
  .bp3-running-text pre > code, .bp3-code-block > code{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:inherit;
    font-size:inherit;
    padding:0; }

.bp3-running-text kbd, .bp3-key{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#5c7080;
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  font-family:inherit;
  font-size:12px;
  height:24px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  line-height:24px;
  min-width:24px;
  padding:3px 6px;
  vertical-align:middle; }
  .bp3-running-text kbd .bp3-icon, .bp3-key .bp3-icon, .bp3-running-text kbd .bp3-icon-standard, .bp3-key .bp3-icon-standard, .bp3-running-text kbd .bp3-icon-large, .bp3-key .bp3-icon-large{
    margin-right:5px; }
  .bp3-dark .bp3-running-text kbd, .bp3-running-text .bp3-dark kbd, .bp3-dark .bp3-key{
    background:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#a7b6c2; }
.bp3-running-text blockquote, .bp3-blockquote{
  border-left:solid 4px rgba(167, 182, 194, 0.5);
  margin:0 0 10px;
  padding:0 20px; }
  .bp3-dark .bp3-running-text blockquote, .bp3-running-text .bp3-dark blockquote, .bp3-dark .bp3-blockquote{
    border-color:rgba(115, 134, 148, 0.5); }
.bp3-running-text ul,
.bp3-running-text ol, .bp3-list{
  margin:10px 0;
  padding-left:30px; }
  .bp3-running-text ul li:not(:last-child), .bp3-running-text ol li:not(:last-child), .bp3-list li:not(:last-child){
    margin-bottom:5px; }
  .bp3-running-text ul ol, .bp3-running-text ol ol, .bp3-list ol,
  .bp3-running-text ul ul,
  .bp3-running-text ol ul,
  .bp3-list ul{
    margin-top:5px; }

.bp3-list-unstyled{
  list-style:none;
  margin:0;
  padding:0; }
  .bp3-list-unstyled li{
    padding:0; }
.bp3-rtl{
  text-align:right; }

.bp3-dark{
  color:#f5f8fa; }

:focus{
  outline:rgba(19, 124, 189, 0.6) auto 2px;
  outline-offset:2px;
  -moz-outline-radius:6px; }

.bp3-focus-disabled :focus{
  outline:none !important; }
  .bp3-focus-disabled :focus ~ .bp3-control-indicator{
    outline:none !important; }

.bp3-alert{
  max-width:400px;
  padding:20px; }

.bp3-alert-body{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-alert-body .bp3-icon{
    font-size:40px;
    margin-right:20px;
    margin-top:0; }

.bp3-alert-contents{
  word-break:break-word; }

.bp3-alert-footer{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:reverse;
      -ms-flex-direction:row-reverse;
          flex-direction:row-reverse;
  margin-top:10px; }
  .bp3-alert-footer .bp3-button{
    margin-left:10px; }
.bp3-breadcrumbs{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  cursor:default;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:wrap;
      flex-wrap:wrap;
  height:30px;
  list-style:none;
  margin:0;
  padding:0; }
  .bp3-breadcrumbs > li{
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex; }
    .bp3-breadcrumbs > li::after{
      background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M10.71 7.29l-4-4a1.003 1.003 0 00-1.42 1.42L8.59 8 5.3 11.29c-.19.18-.3.43-.3.71a1.003 1.003 0 001.71.71l4-4c.18-.18.29-.43.29-.71 0-.28-.11-.53-.29-.71z' fill='%235C7080'/%3e%3c/svg%3e");
      content:"";
      display:block;
      height:16px;
      margin:0 5px;
      width:16px; }
    .bp3-breadcrumbs > li:last-of-type::after{
      display:none; }

.bp3-breadcrumb,
.bp3-breadcrumb-current,
.bp3-breadcrumbs-collapsed{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  font-size:16px; }

.bp3-breadcrumb,
.bp3-breadcrumbs-collapsed{
  color:#5c7080; }

.bp3-breadcrumb:hover{
  text-decoration:none; }

.bp3-breadcrumb.bp3-disabled{
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-breadcrumb .bp3-icon{
  margin-right:5px; }

.bp3-breadcrumb-current{
  color:inherit;
  font-weight:600; }
  .bp3-breadcrumb-current .bp3-input{
    font-size:inherit;
    font-weight:inherit;
    vertical-align:baseline; }

.bp3-breadcrumbs-collapsed{
  background:#ced9e0;
  border:none;
  border-radius:3px;
  cursor:pointer;
  margin-right:2px;
  padding:1px 5px;
  vertical-align:text-bottom; }
  .bp3-breadcrumbs-collapsed::before{
    background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cg fill='%235C7080'%3e%3ccircle cx='2' cy='8.03' r='2'/%3e%3ccircle cx='14' cy='8.03' r='2'/%3e%3ccircle cx='8' cy='8.03' r='2'/%3e%3c/g%3e%3c/svg%3e") center no-repeat;
    content:"";
    display:block;
    height:16px;
    width:16px; }
  .bp3-breadcrumbs-collapsed:hover{
    background:#bfccd6;
    color:#182026;
    text-decoration:none; }

.bp3-dark .bp3-breadcrumb,
.bp3-dark .bp3-breadcrumbs-collapsed{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumbs > li::after{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumb.bp3-disabled{
  color:rgba(167, 182, 194, 0.6); }

.bp3-dark .bp3-breadcrumb-current{
  color:#f5f8fa; }

.bp3-dark .bp3-breadcrumbs-collapsed{
  background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-breadcrumbs-collapsed:hover{
    background:rgba(16, 22, 26, 0.6);
    color:#f5f8fa; }
.bp3-button{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  font-size:14px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  padding:5px 10px;
  text-align:left;
  vertical-align:middle;
  min-height:30px;
  min-width:30px; }
  .bp3-button > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-button > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-button::before,
  .bp3-button > *{
    margin-right:7px; }
  .bp3-button:empty::before,
  .bp3-button > :last-child{
    margin-right:0; }
  .bp3-button:empty{
    padding:0 !important; }
  .bp3-button:disabled, .bp3-button.bp3-disabled{
    cursor:not-allowed; }
  .bp3-button.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button.bp3-align-right,
  .bp3-align-right .bp3-button{
    text-align:right; }
  .bp3-button.bp3-align-left,
  .bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-button:not([class*="bp3-intent-"]){
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    color:#182026; }
    .bp3-button:not([class*="bp3-intent-"]):hover{
      background-clip:padding-box;
      background-color:#ebf1f5;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
    .bp3-button:not([class*="bp3-intent-"]):active, .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      background-color:#d8e1e8;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      outline:none; }
      .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active:hover, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-button.bp3-intent-primary{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover, .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover{
      background-color:#106ba3;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      background-color:#0e5a8a;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-primary:disabled, .bp3-button.bp3-intent-primary.bp3-disabled{
      background-color:rgba(19, 124, 189, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-success{
    background-color:#0f9960;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-success:hover, .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-success:hover{
      background-color:#0d8050;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      background-color:#0a6640;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-success:disabled, .bp3-button.bp3-intent-success.bp3-disabled{
      background-color:rgba(15, 153, 96, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-warning{
    background-color:#d9822b;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover, .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover{
      background-color:#bf7326;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      background-color:#a66321;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-warning:disabled, .bp3-button.bp3-intent-warning.bp3-disabled{
      background-color:rgba(217, 130, 43, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-danger{
    background-color:#db3737;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover, .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover{
      background-color:#c23030;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      background-color:#a82a2a;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-danger:disabled, .bp3-button.bp3-intent-danger.bp3-disabled{
      background-color:rgba(219, 55, 55, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
    stroke:#ffffff; }
  .bp3-button.bp3-large,
  .bp3-large .bp3-button{
    min-height:40px;
    min-width:40px;
    font-size:16px;
    padding:5px 15px; }
    .bp3-button.bp3-large::before,
    .bp3-button.bp3-large > *,
    .bp3-large .bp3-button::before,
    .bp3-large .bp3-button > *{
      margin-right:10px; }
    .bp3-button.bp3-large:empty::before,
    .bp3-button.bp3-large > :last-child,
    .bp3-large .bp3-button:empty::before,
    .bp3-large .bp3-button > :last-child{
      margin-right:0; }
  .bp3-button.bp3-small,
  .bp3-small .bp3-button{
    min-height:24px;
    min-width:24px;
    padding:0 7px; }
  .bp3-button.bp3-loading{
    position:relative; }
    .bp3-button.bp3-loading[class*="bp3-icon-"]::before{
      visibility:hidden; }
    .bp3-button.bp3-loading .bp3-button-spinner{
      margin:0;
      position:absolute; }
    .bp3-button.bp3-loading > :not(.bp3-button-spinner){
      visibility:hidden; }
  .bp3-button[class*="bp3-icon-"]::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    color:#5c7080; }
  .bp3-button .bp3-icon, .bp3-button .bp3-icon-standard, .bp3-button .bp3-icon-large{
    color:#5c7080; }
    .bp3-button .bp3-icon.bp3-align-right, .bp3-button .bp3-icon-standard.bp3-align-right, .bp3-button .bp3-icon-large.bp3-align-right{
      margin-left:7px; }
  .bp3-button .bp3-icon:first-child:last-child,
  .bp3-button .bp3-spinner + .bp3-icon:last-child{
    margin:0 -7px; }
  .bp3-dark .bp3-button:not([class*="bp3-intent-"]){
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover, .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"])[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-large{
      color:#a7b6c2; }
  .bp3-dark .bp3-button[class*="bp3-intent-"]{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:active, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:disabled, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-disabled{
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.3); }
    .bp3-dark .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
      stroke:#8a9ba8; }
  .bp3-button:disabled::before,
  .bp3-button:disabled .bp3-icon, .bp3-button:disabled .bp3-icon-standard, .bp3-button:disabled .bp3-icon-large, .bp3-button.bp3-disabled::before,
  .bp3-button.bp3-disabled .bp3-icon, .bp3-button.bp3-disabled .bp3-icon-standard, .bp3-button.bp3-disabled .bp3-icon-large, .bp3-button[class*="bp3-intent-"]::before,
  .bp3-button[class*="bp3-intent-"] .bp3-icon, .bp3-button[class*="bp3-intent-"] .bp3-icon-standard, .bp3-button[class*="bp3-intent-"] .bp3-icon-large{
    color:inherit !important; }
  .bp3-button.bp3-minimal{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-button.bp3-minimal:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button.bp3-minimal:active, .bp3-button.bp3-minimal.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button.bp3-minimal:disabled, .bp3-button.bp3-minimal:disabled:hover, .bp3-button.bp3-minimal.bp3-disabled, .bp3-button.bp3-minimal.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-minimal{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-minimal:hover, .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button.bp3-minimal:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-minimal:disabled, .bp3-dark .bp3-button.bp3-minimal:disabled:hover, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover, .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover, .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover, .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover, .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button.bp3-outlined{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    border:1px solid rgba(24, 32, 38, 0.2);
    -webkit-box-sizing:border-box;
            box-sizing:border-box; }
    .bp3-button.bp3-outlined:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button.bp3-outlined:active, .bp3-button.bp3-outlined.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button.bp3-outlined:disabled, .bp3-button.bp3-outlined:disabled:hover, .bp3-button.bp3-outlined.bp3-disabled, .bp3-button.bp3-outlined.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button.bp3-outlined:disabled.bp3-active, .bp3-button.bp3-outlined:disabled:hover.bp3-active, .bp3-button.bp3-outlined.bp3-disabled.bp3-active, .bp3-button.bp3-outlined.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-outlined{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-outlined:hover, .bp3-dark .bp3-button.bp3-outlined:active, .bp3-dark .bp3-button.bp3-outlined.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button.bp3-outlined:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-outlined:active, .bp3-dark .bp3-button.bp3-outlined.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-outlined:disabled, .bp3-dark .bp3-button.bp3-outlined:disabled:hover, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button.bp3-outlined:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:hover, .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:hover, .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:hover, .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:hover, .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
    .bp3-button.bp3-outlined:disabled, .bp3-button.bp3-outlined.bp3-disabled, .bp3-button.bp3-outlined:disabled:hover, .bp3-button.bp3-outlined.bp3-disabled:hover{
      border-color:rgba(92, 112, 128, 0.1); }
    .bp3-dark .bp3-button.bp3-outlined{
      border-color:rgba(255, 255, 255, 0.4); }
      .bp3-dark .bp3-button.bp3-outlined:disabled, .bp3-dark .bp3-button.bp3-outlined:disabled:hover, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover{
        border-color:rgba(255, 255, 255, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-primary{
      border-color:rgba(16, 107, 163, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
        border-color:rgba(16, 107, 163, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary{
        border-color:rgba(72, 175, 240, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
          border-color:rgba(72, 175, 240, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-success{
      border-color:rgba(13, 128, 80, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
        border-color:rgba(13, 128, 80, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success{
        border-color:rgba(61, 204, 145, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
          border-color:rgba(61, 204, 145, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-warning{
      border-color:rgba(191, 115, 38, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
        border-color:rgba(191, 115, 38, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning{
        border-color:rgba(255, 179, 102, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
          border-color:rgba(255, 179, 102, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-danger{
      border-color:rgba(194, 48, 48, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
        border-color:rgba(194, 48, 48, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger{
        border-color:rgba(255, 115, 115, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
          border-color:rgba(255, 115, 115, 0.2); }

a.bp3-button{
  text-align:center;
  text-decoration:none;
  -webkit-transition:none;
  transition:none; }
  a.bp3-button, a.bp3-button:hover, a.bp3-button:active{
    color:#182026; }
  a.bp3-button.bp3-disabled{
    color:rgba(92, 112, 128, 0.6); }

.bp3-button-text{
  -webkit-box-flex:0;
      -ms-flex:0 1 auto;
          flex:0 1 auto; }

.bp3-button.bp3-align-left .bp3-button-text, .bp3-button.bp3-align-right .bp3-button-text,
.bp3-button-group.bp3-align-left .bp3-button-text,
.bp3-button-group.bp3-align-right .bp3-button-text{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto; }
.bp3-button-group{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex; }
  .bp3-button-group .bp3-button{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    position:relative;
    z-index:4; }
    .bp3-button-group .bp3-button:focus{
      z-index:5; }
    .bp3-button-group .bp3-button:hover{
      z-index:6; }
    .bp3-button-group .bp3-button:active, .bp3-button-group .bp3-button.bp3-active{
      z-index:7; }
    .bp3-button-group .bp3-button:disabled, .bp3-button-group .bp3-button.bp3-disabled{
      z-index:3; }
    .bp3-button-group .bp3-button[class*="bp3-intent-"]{
      z-index:9; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:focus{
        z-index:10; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:hover{
        z-index:11; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:active, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-active{
        z-index:12; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:disabled, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-disabled{
        z-index:8; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:first-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:first-child){
    border-bottom-left-radius:0;
    border-top-left-radius:0; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    border-bottom-right-radius:0;
    border-top-right-radius:0;
    margin-right:-1px; }
  .bp3-button-group.bp3-minimal .bp3-button{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-button-group.bp3-minimal .bp3-button:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button-group.bp3-minimal .bp3-button{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
      color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
      color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button-group .bp3-popover-wrapper,
  .bp3-button-group .bp3-popover-target{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button-group .bp3-button.bp3-fill,
  .bp3-button-group.bp3-fill .bp3-button:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-vertical{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    vertical-align:top; }
    .bp3-button-group.bp3-vertical.bp3-fill{
      height:100%;
      width:unset; }
    .bp3-button-group.bp3-vertical .bp3-button{
      margin-right:0 !important;
      width:100%; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:first-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:first-child{
      border-radius:3px 3px 0 0; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:last-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:last-child{
      border-radius:0 0 3px 3px; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:not(:last-child){
      margin-bottom:-1px; }
  .bp3-button-group.bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    margin-right:1px; }
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-button:not(:last-child){
    margin-bottom:1px; }
.bp3-callout{
  font-size:14px;
  line-height:1.5;
  background-color:rgba(138, 155, 168, 0.15);
  border-radius:3px;
  padding:10px 12px 9px;
  position:relative;
  width:100%; }
  .bp3-callout[class*="bp3-icon-"]{
    padding-left:40px; }
    .bp3-callout[class*="bp3-icon-"]::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      color:#5c7080;
      left:10px;
      position:absolute;
      top:10px; }
  .bp3-callout.bp3-callout-icon{
    padding-left:40px; }
    .bp3-callout.bp3-callout-icon > .bp3-icon:first-child{
      color:#5c7080;
      left:10px;
      position:absolute;
      top:10px; }
  .bp3-callout .bp3-heading{
    line-height:20px;
    margin-bottom:5px;
    margin-top:0; }
    .bp3-callout .bp3-heading:last-child{
      margin-bottom:0; }
  .bp3-dark .bp3-callout{
    background-color:rgba(138, 155, 168, 0.2); }
    .bp3-dark .bp3-callout[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
  .bp3-callout.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15); }
    .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-primary .bp3-heading{
      color:#106ba3; }
    .bp3-dark .bp3-callout.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-primary .bp3-heading{
        color:#48aff0; }
  .bp3-callout.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15); }
    .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-success .bp3-heading{
      color:#0d8050; }
    .bp3-dark .bp3-callout.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-success .bp3-heading{
        color:#3dcc91; }
  .bp3-callout.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15); }
    .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-warning .bp3-heading{
      color:#bf7326; }
    .bp3-dark .bp3-callout.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-warning .bp3-heading{
        color:#ffb366; }
  .bp3-callout.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15); }
    .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-danger .bp3-heading{
      color:#c23030; }
    .bp3-dark .bp3-callout.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-danger .bp3-heading{
        color:#ff7373; }
  .bp3-running-text .bp3-callout{
    margin:20px 0; }
.bp3-card{
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
  padding:20px;
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-card.bp3-dark,
  .bp3-dark .bp3-card{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-0{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }
  .bp3-elevation-0.bp3-dark,
  .bp3-dark .bp3-elevation-0{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-1{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-1.bp3-dark,
  .bp3-dark .bp3-elevation-1{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-elevation-2{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-2.bp3-dark,
  .bp3-dark .bp3-elevation-2{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4); }

.bp3-elevation-3{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-3.bp3-dark,
  .bp3-dark .bp3-elevation-3{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-elevation-4{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-4.bp3-dark,
  .bp3-dark .bp3-elevation-4{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:hover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  cursor:pointer; }
  .bp3-card.bp3-interactive:hover.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:hover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:active{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  opacity:0.9;
  -webkit-transition-duration:0;
          transition-duration:0; }
  .bp3-card.bp3-interactive:active.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:active{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-collapse{
  height:0;
  overflow-y:hidden;
  -webkit-transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-collapse .bp3-collapse-body{
    -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-collapse .bp3-collapse-body[aria-hidden="true"]{
      display:none; }

.bp3-context-menu .bp3-popover-target{
  display:block; }

.bp3-context-menu-popover-target{
  position:fixed; }

.bp3-divider{
  border-bottom:1px solid rgba(16, 22, 26, 0.15);
  border-right:1px solid rgba(16, 22, 26, 0.15);
  margin:5px; }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-dialog-container{
  opacity:1;
  -webkit-transform:scale(1);
          transform:scale(1);
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  min-height:100%;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none;
  width:100%; }
  .bp3-dialog-container.bp3-overlay-enter > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5); }
  .bp3-dialog-container.bp3-overlay-enter-active > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear-active > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-dialog-container.bp3-overlay-exit > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-dialog-container.bp3-overlay-exit-active > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }

.bp3-dialog{
  background:#ebf1f5;
  border-radius:6px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:30px 0;
  padding-bottom:20px;
  pointer-events:all;
  -webkit-user-select:text;
     -moz-user-select:text;
      -ms-user-select:text;
          user-select:text;
  width:500px; }
  .bp3-dialog:focus{
    outline:0; }
  .bp3-dialog.bp3-dark,
  .bp3-dark .bp3-dialog{
    background:#293742;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }

.bp3-dialog-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background:#ffffff;
  border-radius:6px 6px 0 0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  min-height:40px;
  padding-left:20px;
  padding-right:5px;
  z-index:30; }
  .bp3-dialog-header .bp3-icon-large,
  .bp3-dialog-header .bp3-icon{
    color:#5c7080;
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px; }
  .bp3-dialog-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:inherit;
    margin:0; }
    .bp3-dialog-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-dialog-header{
    background:#30404d;
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-dialog-header .bp3-icon-large,
    .bp3-dark .bp3-dialog-header .bp3-icon{
      color:#a7b6c2; }

.bp3-dialog-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  line-height:18px;
  margin:20px; }

.bp3-dialog-footer{
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  margin:0 20px; }

.bp3-dialog-footer-actions{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:end;
      -ms-flex-pack:end;
          justify-content:flex-end; }
  .bp3-dialog-footer-actions .bp3-button{
    margin-left:10px; }
.bp3-multistep-dialog-panels{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }

.bp3-multistep-dialog-left-panel{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:1;
      -ms-flex:1;
          flex:1;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column; }
  .bp3-dark .bp3-multistep-dialog-left-panel{
    background:#202b33; }

.bp3-multistep-dialog-right-panel{
  background-color:#f5f8fa;
  border-left:1px solid rgba(16, 22, 26, 0.15);
  border-radius:0 0 6px 0;
  -webkit-box-flex:3;
      -ms-flex:3;
          flex:3;
  min-width:0; }
  .bp3-dark .bp3-multistep-dialog-right-panel{
    background-color:#293742;
    border-left:1px solid rgba(16, 22, 26, 0.4); }

.bp3-multistep-dialog-footer{
  background-color:#ffffff;
  border-radius:0 0 6px 0;
  border-top:1px solid rgba(16, 22, 26, 0.15);
  padding:10px; }
  .bp3-dark .bp3-multistep-dialog-footer{
    background:#30404d;
    border-top:1px solid rgba(16, 22, 26, 0.4); }

.bp3-dialog-step-container{
  background-color:#f5f8fa;
  border-bottom:1px solid rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-dialog-step-container{
    background:#293742;
    border-bottom:1px solid rgba(16, 22, 26, 0.4); }
  .bp3-dialog-step-container.bp3-dialog-step-viewed{
    background-color:#ffffff; }
    .bp3-dark .bp3-dialog-step-container.bp3-dialog-step-viewed{
      background:#30404d; }

.bp3-dialog-step{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:#f5f8fa;
  border-radius:6px;
  cursor:not-allowed;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin:4px;
  padding:6px 14px; }
  .bp3-dark .bp3-dialog-step{
    background:#293742; }
  .bp3-dialog-step-viewed .bp3-dialog-step{
    background-color:#ffffff;
    cursor:pointer; }
    .bp3-dark .bp3-dialog-step-viewed .bp3-dialog-step{
      background:#30404d; }
  .bp3-dialog-step:hover{
    background-color:#f5f8fa; }
    .bp3-dark .bp3-dialog-step:hover{
      background:#293742; }

.bp3-dialog-step-icon{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:rgba(92, 112, 128, 0.6);
  border-radius:50%;
  color:#ffffff;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:25px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:25px; }
  .bp3-dark .bp3-dialog-step-icon{
    background-color:rgba(167, 182, 194, 0.6); }
  .bp3-active.bp3-dialog-step-viewed .bp3-dialog-step-icon{
    background-color:#2b95d6; }
  .bp3-dialog-step-viewed .bp3-dialog-step-icon{
    background-color:#8a9ba8; }

.bp3-dialog-step-title{
  color:rgba(92, 112, 128, 0.6);
  -webkit-box-flex:1;
      -ms-flex:1;
          flex:1;
  padding-left:10px; }
  .bp3-dark .bp3-dialog-step-title{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-active.bp3-dialog-step-viewed .bp3-dialog-step-title{
    color:#2b95d6; }
  .bp3-dialog-step-viewed:not(.bp3-active) .bp3-dialog-step-title{
    color:#182026; }
    .bp3-dark .bp3-dialog-step-viewed:not(.bp3-active) .bp3-dialog-step-title{
      color:#f5f8fa; }
.bp3-drawer{
  background:#ffffff;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0;
  padding:0; }
  .bp3-drawer:focus{
    outline:0; }
  .bp3-drawer.bp3-position-top{
    height:50%;
    left:0;
    right:0;
    top:0; }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter, .bp3-drawer.bp3-position-top.bp3-overlay-appear{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%); }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter-active, .bp3-drawer.bp3-position-top.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit-active{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-bottom{
    bottom:0;
    height:50%;
    left:0;
    right:0; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter-active, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-left{
    bottom:0;
    left:0;
    top:0;
    width:50%; }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter, .bp3-drawer.bp3-position-left.bp3-overlay-appear{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%); }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter-active, .bp3-drawer.bp3-position-left.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit-active{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-right{
    bottom:0;
    right:0;
    top:0;
    width:50%; }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter, .bp3-drawer.bp3-position-right.bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter-active, .bp3-drawer.bp3-position-right.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right):not(.bp3-vertical){
    bottom:0;
    right:0;
    top:0;
    width:50%; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right).bp3-vertical{
    bottom:0;
    height:50%;
    left:0;
    right:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-dark,
  .bp3-dark .bp3-drawer{
    background:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }

.bp3-drawer-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border-radius:0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  min-height:40px;
  padding:5px;
  padding-left:20px;
  position:relative; }
  .bp3-drawer-header .bp3-icon-large,
  .bp3-drawer-header .bp3-icon{
    color:#5c7080;
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px; }
  .bp3-drawer-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:inherit;
    margin:0; }
    .bp3-drawer-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-drawer-header{
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-drawer-header .bp3-icon-large,
    .bp3-dark .bp3-drawer-header .bp3-icon{
      color:#a7b6c2; }

.bp3-drawer-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  line-height:18px;
  overflow:auto; }

.bp3-drawer-footer{
  -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  padding:10px 20px;
  position:relative; }
  .bp3-dark .bp3-drawer-footer{
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4); }
.bp3-editable-text{
  cursor:text;
  display:inline-block;
  max-width:100%;
  position:relative;
  vertical-align:top;
  white-space:nowrap; }
  .bp3-editable-text::before{
    bottom:-3px;
    left:-3px;
    position:absolute;
    right:-3px;
    top:-3px;
    border-radius:3px;
    content:"";
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-editable-text.bp3-editable-text-editing::before{
    background-color:#ffffff;
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#137cbd; }
  .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4); }
  .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#0f9960; }
  .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4); }
  .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#d9822b; }
  .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4); }
  .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#db3737; }
  .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4); }
  .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15); }
  .bp3-dark .bp3-editable-text.bp3-editable-text-editing::before{
    background-color:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#48aff0; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4);
            box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#3dcc91; }
  .bp3-dark .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4);
            box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#ffb366; }
  .bp3-dark .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4);
            box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#ff7373; }
  .bp3-dark .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4);
            box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-editable-text-input,
.bp3-editable-text-content{
  color:inherit;
  display:inherit;
  font:inherit;
  letter-spacing:inherit;
  max-width:inherit;
  min-width:inherit;
  position:relative;
  resize:none;
  text-transform:inherit;
  vertical-align:top; }

.bp3-editable-text-input{
  background:none;
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0;
  white-space:pre-wrap;
  width:100%; }
  .bp3-editable-text-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input:focus{
    outline:none; }
  .bp3-editable-text-input::-ms-clear{
    display:none; }

.bp3-editable-text-content{
  overflow:hidden;
  padding-right:2px;
  text-overflow:ellipsis;
  white-space:pre; }
  .bp3-editable-text-editing > .bp3-editable-text-content{
    left:0;
    position:absolute;
    visibility:hidden; }
  .bp3-editable-text-placeholder > .bp3-editable-text-content{
    color:rgba(92, 112, 128, 0.6); }
    .bp3-dark .bp3-editable-text-placeholder > .bp3-editable-text-content{
      color:rgba(167, 182, 194, 0.6); }

.bp3-editable-text.bp3-multiline{
  display:block; }
  .bp3-editable-text.bp3-multiline .bp3-editable-text-content{
    overflow:auto;
    white-space:pre-wrap;
    word-wrap:break-word; }
.bp3-divider{
  border-bottom:1px solid rgba(16, 22, 26, 0.15);
  border-right:1px solid rgba(16, 22, 26, 0.15);
  margin:5px; }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-control-group{
  -webkit-transform:translateZ(0);
          transform:translateZ(0);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:stretch;
      -ms-flex-align:stretch;
          align-items:stretch; }
  .bp3-control-group > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select,
  .bp3-control-group .bp3-input,
  .bp3-control-group .bp3-select{
    position:relative; }
  .bp3-control-group .bp3-input{
    border-radius:inherit;
    z-index:2; }
    .bp3-control-group .bp3-input:focus{
      border-radius:3px;
      z-index:14; }
    .bp3-control-group .bp3-input[class*="bp3-intent"]{
      z-index:13; }
      .bp3-control-group .bp3-input[class*="bp3-intent"]:focus{
        z-index:15; }
    .bp3-control-group .bp3-input[readonly], .bp3-control-group .bp3-input:disabled, .bp3-control-group .bp3-input.bp3-disabled{
      z-index:1; }
  .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input{
    z-index:13; }
    .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input:focus{
      z-index:15; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select select,
  .bp3-control-group .bp3-select select{
    -webkit-transform:translateZ(0);
            transform:translateZ(0);
    border-radius:inherit;
    z-index:4; }
    .bp3-control-group .bp3-button:focus,
    .bp3-control-group .bp3-html-select select:focus,
    .bp3-control-group .bp3-select select:focus{
      z-index:5; }
    .bp3-control-group .bp3-button:hover,
    .bp3-control-group .bp3-html-select select:hover,
    .bp3-control-group .bp3-select select:hover{
      z-index:6; }
    .bp3-control-group .bp3-button:active,
    .bp3-control-group .bp3-html-select select:active,
    .bp3-control-group .bp3-select select:active{
      z-index:7; }
    .bp3-control-group .bp3-button[readonly], .bp3-control-group .bp3-button:disabled, .bp3-control-group .bp3-button.bp3-disabled,
    .bp3-control-group .bp3-html-select select[readonly],
    .bp3-control-group .bp3-html-select select:disabled,
    .bp3-control-group .bp3-html-select select.bp3-disabled,
    .bp3-control-group .bp3-select select[readonly],
    .bp3-control-group .bp3-select select:disabled,
    .bp3-control-group .bp3-select select.bp3-disabled{
      z-index:3; }
    .bp3-control-group .bp3-button[class*="bp3-intent"],
    .bp3-control-group .bp3-html-select select[class*="bp3-intent"],
    .bp3-control-group .bp3-select select[class*="bp3-intent"]{
      z-index:9; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:focus{
        z-index:10; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:hover{
        z-index:11; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:active{
        z-index:12; }
      .bp3-control-group .bp3-button[class*="bp3-intent"][readonly], .bp3-control-group .bp3-button[class*="bp3-intent"]:disabled, .bp3-control-group .bp3-button[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"].bp3-disabled{
        z-index:8; }
  .bp3-control-group .bp3-input-group > .bp3-icon,
  .bp3-control-group .bp3-input-group > .bp3-button,
  .bp3-control-group .bp3-input-group > .bp3-input-left-container,
  .bp3-control-group .bp3-input-group > .bp3-input-action{
    z-index:16; }
  .bp3-control-group .bp3-select::after,
  .bp3-control-group .bp3-html-select::after,
  .bp3-control-group .bp3-select > .bp3-icon,
  .bp3-control-group .bp3-html-select > .bp3-icon{
    z-index:17; }
  .bp3-control-group .bp3-select:focus-within{
    z-index:5; }
  .bp3-control-group:not(.bp3-vertical) > *:not(.bp3-divider){
    margin-right:-1px; }
  .bp3-control-group:not(.bp3-vertical) > .bp3-divider:not(:first-child){
    margin-left:6px; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > *:not(.bp3-divider){
    margin-right:0; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > .bp3-button + .bp3-button{
    margin-left:1px; }
  .bp3-control-group .bp3-popover-wrapper,
  .bp3-control-group .bp3-popover-target{
    border-radius:inherit; }
  .bp3-control-group > :first-child{
    border-radius:3px 0 0 3px; }
  .bp3-control-group > :last-child{
    border-radius:0 3px 3px 0;
    margin-right:0; }
  .bp3-control-group > :only-child{
    border-radius:3px;
    margin-right:0; }
  .bp3-control-group .bp3-input-group .bp3-button{
    border-radius:3px; }
  .bp3-control-group .bp3-numeric-input:not(:first-child) .bp3-input-group{
    border-bottom-left-radius:0;
    border-top-left-radius:0; }
  .bp3-control-group.bp3-fill{
    width:100%; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-fill > *:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-vertical{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-control-group.bp3-vertical > *{
      margin-top:-1px; }
    .bp3-control-group.bp3-vertical > :first-child{
      border-radius:3px 3px 0 0;
      margin-top:0; }
    .bp3-control-group.bp3-vertical > :last-child{
      border-radius:0 0 3px 3px; }
.bp3-control{
  cursor:pointer;
  display:block;
  margin-bottom:10px;
  position:relative;
  text-transform:none; }
  .bp3-control input:checked ~ .bp3-control-indicator{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
  .bp3-control:hover input:checked ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
  .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    background:#0e5a8a;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control:hover input:checked ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    background-color:#0e5a8a;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-control:not(.bp3-align-right){
    padding-left:26px; }
    .bp3-control:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-26px; }
  .bp3-control.bp3-align-right{
    padding-right:26px; }
    .bp3-control.bp3-align-right .bp3-control-indicator{
      margin-right:-26px; }
  .bp3-control.bp3-disabled{
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-control.bp3-inline{
    display:inline-block;
    margin-right:20px; }
  .bp3-control input{
    left:0;
    opacity:0;
    position:absolute;
    top:0;
    z-index:-1; }
  .bp3-control .bp3-control-indicator{
    background-clip:padding-box;
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    border:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    cursor:pointer;
    display:inline-block;
    font-size:16px;
    height:1em;
    margin-right:10px;
    margin-top:-3px;
    position:relative;
    -webkit-user-select:none;
       -moz-user-select:none;
        -ms-user-select:none;
            user-select:none;
    vertical-align:middle;
    width:1em; }
    .bp3-control .bp3-control-indicator::before{
      content:"";
      display:block;
      height:1em;
      width:1em; }
  .bp3-control:hover .bp3-control-indicator{
    background-color:#ebf1f5; }
  .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
    background:#d8e1e8;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    cursor:not-allowed; }
  .bp3-control input:focus ~ .bp3-control-indicator{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:2px;
    -moz-outline-radius:6px; }
  .bp3-control.bp3-align-right .bp3-control-indicator{
    float:right;
    margin-left:10px;
    margin-top:1px; }
  .bp3-control.bp3-large{
    font-size:16px; }
    .bp3-control.bp3-large:not(.bp3-align-right){
      padding-left:30px; }
      .bp3-control.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
        margin-left:-30px; }
    .bp3-control.bp3-large.bp3-align-right{
      padding-right:30px; }
      .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
        margin-right:-30px; }
    .bp3-control.bp3-large .bp3-control-indicator{
      font-size:20px; }
    .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-top:0; }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
  .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
  .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    background:#0e5a8a;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    background-color:#0e5a8a;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-control.bp3-checkbox .bp3-control-indicator{
    border-radius:3px; }
  .bp3-control.bp3-checkbox input:checked ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M12 5c-.28 0-.53.11-.71.29L7 9.59l-2.29-2.3a1.003 1.003 0 00-1.42 1.42l3 3c.18.18.43.29.71.29s.53-.11.71-.29l5-5A1.003 1.003 0 0012 5z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M11 7H5c-.55 0-1 .45-1 1s.45 1 1 1h6c.55 0 1-.45 1-1s-.45-1-1-1z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-radio .bp3-control-indicator{
    border-radius:50%; }
  .bp3-control.bp3-radio input:checked ~ .bp3-control-indicator::before{
    background-image:radial-gradient(#ffffff, #ffffff 28%, transparent 32%); }
  .bp3-control.bp3-radio input:checked:disabled ~ .bp3-control-indicator::before{
    opacity:0.5; }
  .bp3-control.bp3-radio input:focus ~ .bp3-control-indicator{
    -moz-outline-radius:16px; }
  .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(167, 182, 194, 0.5); }
  .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(115, 134, 148, 0.5); }
  .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(92, 112, 128, 0.5); }
  .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5); }
    .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5); }
    .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch:not(.bp3-align-right){
    padding-left:38px; }
    .bp3-control.bp3-switch:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-38px; }
  .bp3-control.bp3-switch.bp3-align-right{
    padding-right:38px; }
    .bp3-control.bp3-switch.bp3-align-right .bp3-control-indicator{
      margin-right:-38px; }
  .bp3-control.bp3-switch .bp3-control-indicator{
    border:none;
    border-radius:1.75em;
    -webkit-box-shadow:none !important;
            box-shadow:none !important;
    min-width:1.75em;
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    width:auto; }
    .bp3-control.bp3-switch .bp3-control-indicator::before{
      background:#ffffff;
      border-radius:50%;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
      height:calc(1em - 4px);
      left:0;
      margin:2px;
      position:absolute;
      -webkit-transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      width:calc(1em - 4px); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    left:calc(100% - 1em); }
  .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right){
    padding-left:45px; }
    .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-45px; }
  .bp3-control.bp3-switch.bp3-large.bp3-align-right{
    padding-right:45px; }
    .bp3-control.bp3-switch.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-right:-45px; }
  .bp3-dark .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.7); }
  .bp3-dark .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.9); }
  .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(57, 75, 89, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-dark .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-dark .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch .bp3-control-indicator::before{
    background:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-control.bp3-switch .bp3-switch-inner-text{
    font-size:0.7em;
    text-align:center; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:first-child{
    line-height:0;
    margin-left:0.5em;
    margin-right:1.2em;
    visibility:hidden; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:last-child{
    line-height:1em;
    margin-left:1.2em;
    margin-right:0.5em;
    visibility:visible; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:first-child{
    line-height:1em;
    visibility:visible; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:last-child{
    line-height:0;
    visibility:hidden; }
  .bp3-dark .bp3-control{
    color:#f5f8fa; }
    .bp3-dark .bp3-control.bp3-disabled{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-control .bp3-control-indicator{
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-control:hover .bp3-control-indicator{
      background-color:#30404d; }
    .bp3-dark .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
      background:#202b33;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-control input:disabled ~ .bp3-control-indicator{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      cursor:not-allowed; }
    .bp3-dark .bp3-control.bp3-checkbox input:disabled:checked ~ .bp3-control-indicator, .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
      color:rgba(167, 182, 194, 0.6); }
.bp3-file-input{
  cursor:pointer;
  display:inline-block;
  height:30px;
  position:relative; }
  .bp3-file-input input{
    margin:0;
    min-width:200px;
    opacity:0; }
    .bp3-file-input input:disabled + .bp3-file-upload-input,
    .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
      background:rgba(206, 217, 224, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      resize:none; }
      .bp3-file-input input:disabled + .bp3-file-upload-input::after,
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
        background-color:rgba(206, 217, 224, 0.5);
        background-image:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(92, 112, 128, 0.6);
        cursor:not-allowed;
        outline:none; }
        .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active:hover,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active:hover{
          background:rgba(206, 217, 224, 0.7); }
      .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input, .bp3-dark
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
        background:rgba(57, 75, 89, 0.5);
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after, .bp3-dark
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
          background-color:rgba(57, 75, 89, 0.5);
          background-image:none;
          -webkit-box-shadow:none;
                  box-shadow:none;
          color:rgba(167, 182, 194, 0.6); }
          .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-dark
          .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active{
            background:rgba(57, 75, 89, 0.7); }
  .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#182026; }
  .bp3-dark .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#f5f8fa; }
  .bp3-file-input.bp3-fill{
    width:100%; }
  .bp3-file-input.bp3-large,
  .bp3-large .bp3-file-input{
    height:40px; }
  .bp3-file-input .bp3-file-upload-input-custom-text::after{
    content:attr(bp3-button-text); }

.bp3-file-upload-input{
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  background:#ffffff;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#182026;
  font-size:14px;
  font-weight:400;
  height:30px;
  line-height:30px;
  outline:none;
  padding:0 10px;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  vertical-align:middle;
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  color:rgba(92, 112, 128, 0.6);
  left:0;
  padding-right:80px;
  position:absolute;
  right:0;
  top:0;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-file-upload-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input:focus, .bp3-file-upload-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-file-upload-input[type="search"], .bp3-file-upload-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-file-upload-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-file-upload-input:disabled, .bp3-file-upload-input.bp3-disabled{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    resize:none; }
  .bp3-file-upload-input::after{
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    color:#182026;
    min-height:24px;
    min-width:24px;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    border-radius:3px;
    content:"Browse";
    line-height:24px;
    margin:3px;
    position:absolute;
    right:0;
    text-align:center;
    top:0;
    width:70px; }
    .bp3-file-upload-input::after:hover{
      background-clip:padding-box;
      background-color:#ebf1f5;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
    .bp3-file-upload-input::after:active, .bp3-file-upload-input::after.bp3-active{
      background-color:#d8e1e8;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-file-upload-input::after:disabled, .bp3-file-upload-input::after.bp3-disabled{
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      outline:none; }
      .bp3-file-upload-input::after:disabled.bp3-active, .bp3-file-upload-input::after:disabled.bp3-active:hover, .bp3-file-upload-input::after.bp3-disabled.bp3-active, .bp3-file-upload-input::after.bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-file-upload-input:hover::after{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-file-upload-input:active::after{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-large .bp3-file-upload-input{
    font-size:16px;
    height:40px;
    line-height:40px;
    padding-right:95px; }
    .bp3-large .bp3-file-upload-input[type="search"], .bp3-large .bp3-file-upload-input.bp3-round{
      padding:0 15px; }
    .bp3-large .bp3-file-upload-input::after{
      min-height:30px;
      min-width:30px;
      line-height:30px;
      margin:5px;
      width:85px; }
  .bp3-dark .bp3-file-upload-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:disabled, .bp3-dark .bp3-file-upload-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::after{
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover, .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover{
        background-color:#30404d;
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        background-color:#202b33;
        background-image:none;
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
      .bp3-dark .bp3-file-upload-input::after:disabled, .bp3-dark .bp3-file-upload-input::after.bp3-disabled{
        background-color:rgba(57, 75, 89, 0.5);
        background-image:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-upload-input::after:disabled.bp3-active, .bp3-dark .bp3-file-upload-input::after.bp3-disabled.bp3-active{
          background:rgba(57, 75, 89, 0.7); }
      .bp3-dark .bp3-file-upload-input::after .bp3-button-spinner .bp3-spinner-head{
        background:rgba(16, 22, 26, 0.5);
        stroke:#8a9ba8; }
    .bp3-dark .bp3-file-upload-input:hover::after{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:active::after{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
.bp3-file-upload-input::after{
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
.bp3-form-group{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0 0 15px; }
  .bp3-form-group label.bp3-label{
    margin-bottom:5px; }
  .bp3-form-group .bp3-control{
    margin-top:7px; }
  .bp3-form-group .bp3-form-helper-text{
    color:#5c7080;
    font-size:12px;
    margin-top:5px; }
  .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#106ba3; }
  .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#0d8050; }
  .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#bf7326; }
  .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#c23030; }
  .bp3-form-group.bp3-inline{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row; }
    .bp3-form-group.bp3-inline.bp3-large label.bp3-label{
      line-height:40px;
      margin:0 10px 0 0; }
    .bp3-form-group.bp3-inline label.bp3-label{
      line-height:30px;
      margin:0 10px 0 0; }
  .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-dark .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#48aff0; }
  .bp3-dark .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#3dcc91; }
  .bp3-dark .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#ffb366; }
  .bp3-dark .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#ff7373; }
  .bp3-dark .bp3-form-group .bp3-form-helper-text{
    color:#a7b6c2; }
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(167, 182, 194, 0.6) !important; }
.bp3-input-group{
  display:block;
  position:relative; }
  .bp3-input-group .bp3-input{
    position:relative;
    width:100%; }
    .bp3-input-group .bp3-input:not(:first-child){
      padding-left:30px; }
    .bp3-input-group .bp3-input:not(:last-child){
      padding-right:30px; }
  .bp3-input-group .bp3-input-action,
  .bp3-input-group > .bp3-input-left-container,
  .bp3-input-group > .bp3-button,
  .bp3-input-group > .bp3-icon{
    position:absolute;
    top:0; }
    .bp3-input-group .bp3-input-action:first-child,
    .bp3-input-group > .bp3-input-left-container:first-child,
    .bp3-input-group > .bp3-button:first-child,
    .bp3-input-group > .bp3-icon:first-child{
      left:0; }
    .bp3-input-group .bp3-input-action:last-child,
    .bp3-input-group > .bp3-input-left-container:last-child,
    .bp3-input-group > .bp3-button:last-child,
    .bp3-input-group > .bp3-icon:last-child{
      right:0; }
  .bp3-input-group .bp3-button{
    min-height:24px;
    min-width:24px;
    margin:3px;
    padding:0 7px; }
    .bp3-input-group .bp3-button:empty{
      padding:0; }
  .bp3-input-group > .bp3-input-left-container,
  .bp3-input-group > .bp3-icon{
    z-index:1; }
  .bp3-input-group > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group > .bp3-icon{
    color:#5c7080; }
    .bp3-input-group > .bp3-input-left-container > .bp3-icon:empty,
    .bp3-input-group > .bp3-icon:empty{
      font-family:"Icons16", sans-serif;
      font-size:16px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased; }
  .bp3-input-group > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group > .bp3-icon,
  .bp3-input-group .bp3-input-action > .bp3-spinner{
    margin:7px; }
  .bp3-input-group .bp3-tag{
    margin:5px; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus),
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
    color:#5c7080; }
    .bp3-dark .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus), .bp3-dark
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
      color:#a7b6c2; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large{
      color:#5c7080; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled,
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled{
    color:rgba(92, 112, 128, 0.6) !important; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-large{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-input-group.bp3-disabled{
    cursor:not-allowed; }
    .bp3-input-group.bp3-disabled .bp3-icon{
      color:rgba(92, 112, 128, 0.6); }
  .bp3-input-group.bp3-large .bp3-button{
    min-height:30px;
    min-width:30px;
    margin:5px; }
  .bp3-input-group.bp3-large > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group.bp3-large > .bp3-icon,
  .bp3-input-group.bp3-large .bp3-input-action > .bp3-spinner{
    margin:12px; }
  .bp3-input-group.bp3-large .bp3-input{
    font-size:16px;
    height:40px;
    line-height:40px; }
    .bp3-input-group.bp3-large .bp3-input[type="search"], .bp3-input-group.bp3-large .bp3-input.bp3-round{
      padding:0 15px; }
    .bp3-input-group.bp3-large .bp3-input:not(:first-child){
      padding-left:40px; }
    .bp3-input-group.bp3-large .bp3-input:not(:last-child){
      padding-right:40px; }
  .bp3-input-group.bp3-small .bp3-button{
    min-height:20px;
    min-width:20px;
    margin:2px; }
  .bp3-input-group.bp3-small .bp3-tag{
    min-height:20px;
    min-width:20px;
    margin:2px; }
  .bp3-input-group.bp3-small > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group.bp3-small > .bp3-icon,
  .bp3-input-group.bp3-small .bp3-input-action > .bp3-spinner{
    margin:4px; }
  .bp3-input-group.bp3-small .bp3-input{
    font-size:12px;
    height:24px;
    line-height:24px;
    padding-left:8px;
    padding-right:8px; }
    .bp3-input-group.bp3-small .bp3-input[type="search"], .bp3-input-group.bp3-small .bp3-input.bp3-round{
      padding:0 12px; }
    .bp3-input-group.bp3-small .bp3-input:not(:first-child){
      padding-left:24px; }
    .bp3-input-group.bp3-small .bp3-input:not(:last-child){
      padding-right:24px; }
  .bp3-input-group.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-input-group.bp3-round .bp3-button,
  .bp3-input-group.bp3-round .bp3-input,
  .bp3-input-group.bp3-round .bp3-tag{
    border-radius:30px; }
  .bp3-dark .bp3-input-group .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-input-group.bp3-disabled .bp3-icon{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-input-group.bp3-intent-primary .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input-group.bp3-intent-primary .bp3-input:disabled, .bp3-input-group.bp3-intent-primary .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-primary > .bp3-icon{
    color:#106ba3; }
    .bp3-dark .bp3-input-group.bp3-intent-primary > .bp3-icon{
      color:#48aff0; }
  .bp3-input-group.bp3-intent-success .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input-group.bp3-intent-success .bp3-input:disabled, .bp3-input-group.bp3-intent-success .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-success > .bp3-icon{
    color:#0d8050; }
    .bp3-dark .bp3-input-group.bp3-intent-success > .bp3-icon{
      color:#3dcc91; }
  .bp3-input-group.bp3-intent-warning .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input-group.bp3-intent-warning .bp3-input:disabled, .bp3-input-group.bp3-intent-warning .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-warning > .bp3-icon{
    color:#bf7326; }
    .bp3-dark .bp3-input-group.bp3-intent-warning > .bp3-icon{
      color:#ffb366; }
  .bp3-input-group.bp3-intent-danger .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input-group.bp3-intent-danger .bp3-input:disabled, .bp3-input-group.bp3-intent-danger .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-danger > .bp3-icon{
    color:#c23030; }
    .bp3-dark .bp3-input-group.bp3-intent-danger > .bp3-icon{
      color:#ff7373; }
.bp3-input{
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  background:#ffffff;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#182026;
  font-size:14px;
  font-weight:400;
  height:30px;
  line-height:30px;
  outline:none;
  padding:0 10px;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  vertical-align:middle; }
  .bp3-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input:focus, .bp3-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-input[type="search"], .bp3-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-input:disabled, .bp3-input.bp3-disabled{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    resize:none; }
  .bp3-input.bp3-large{
    font-size:16px;
    height:40px;
    line-height:40px; }
    .bp3-input.bp3-large[type="search"], .bp3-input.bp3-large.bp3-round{
      padding:0 15px; }
  .bp3-input.bp3-small{
    font-size:12px;
    height:24px;
    line-height:24px;
    padding-left:8px;
    padding-right:8px; }
    .bp3-input.bp3-small[type="search"], .bp3-input.bp3-small.bp3-round{
      padding:0 12px; }
  .bp3-input.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-dark .bp3-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input:disabled, .bp3-dark .bp3-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-input.bp3-intent-primary{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input.bp3-intent-primary:disabled, .bp3-input.bp3-intent-primary.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary:focus{
        -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #137cbd;
                box-shadow:inset 0 0 0 1px #137cbd; }
      .bp3-dark .bp3-input.bp3-intent-primary:disabled, .bp3-dark .bp3-input.bp3-intent-primary.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-success{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input.bp3-intent-success:disabled, .bp3-input.bp3-intent-success.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-success{
      -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success:focus{
        -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #0f9960;
                box-shadow:inset 0 0 0 1px #0f9960; }
      .bp3-dark .bp3-input.bp3-intent-success:disabled, .bp3-dark .bp3-input.bp3-intent-success.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-warning{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input.bp3-intent-warning:disabled, .bp3-input.bp3-intent-warning.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning:focus{
        -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #d9822b;
                box-shadow:inset 0 0 0 1px #d9822b; }
      .bp3-dark .bp3-input.bp3-intent-warning:disabled, .bp3-dark .bp3-input.bp3-intent-warning.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-danger{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input.bp3-intent-danger:disabled, .bp3-input.bp3-intent-danger.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger:focus{
        -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #db3737;
                box-shadow:inset 0 0 0 1px #db3737; }
      .bp3-dark .bp3-input.bp3-intent-danger:disabled, .bp3-dark .bp3-input.bp3-intent-danger.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input::-ms-clear{
    display:none; }
textarea.bp3-input{
  max-width:100%;
  padding:10px; }
  textarea.bp3-input, textarea.bp3-input.bp3-large, textarea.bp3-input.bp3-small{
    height:auto;
    line-height:inherit; }
  textarea.bp3-input.bp3-small{
    padding:8px; }
  .bp3-dark textarea.bp3-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark textarea.bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input:disabled, .bp3-dark textarea.bp3-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
label.bp3-label{
  display:block;
  margin-bottom:15px;
  margin-top:0; }
  label.bp3-label .bp3-html-select,
  label.bp3-label .bp3-input,
  label.bp3-label .bp3-select,
  label.bp3-label .bp3-slider,
  label.bp3-label .bp3-popover-wrapper{
    display:block;
    margin-top:5px;
    text-transform:none; }
  label.bp3-label .bp3-button-group{
    margin-top:5px; }
  label.bp3-label .bp3-select select,
  label.bp3-label .bp3-html-select select{
    font-weight:400;
    vertical-align:top;
    width:100%; }
  label.bp3-label.bp3-disabled,
  label.bp3-label.bp3-disabled .bp3-text-muted{
    color:rgba(92, 112, 128, 0.6); }
  label.bp3-label.bp3-inline{
    line-height:30px; }
    label.bp3-label.bp3-inline .bp3-html-select,
    label.bp3-label.bp3-inline .bp3-input,
    label.bp3-label.bp3-inline .bp3-input-group,
    label.bp3-label.bp3-inline .bp3-select,
    label.bp3-label.bp3-inline .bp3-popover-wrapper{
      display:inline-block;
      margin:0 0 0 5px;
      vertical-align:top; }
    label.bp3-label.bp3-inline .bp3-button-group{
      margin:0 0 0 5px; }
    label.bp3-label.bp3-inline .bp3-input-group .bp3-input{
      margin-left:0; }
    label.bp3-label.bp3-inline.bp3-large{
      line-height:40px; }
  label.bp3-label:not(.bp3-inline) .bp3-popover-target{
    display:block; }
  .bp3-dark label.bp3-label{
    color:#f5f8fa; }
    .bp3-dark label.bp3-label.bp3-disabled,
    .bp3-dark label.bp3-label.bp3-disabled .bp3-text-muted{
      color:rgba(167, 182, 194, 0.6); }
.bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button{
  -webkit-box-flex:1;
      -ms-flex:1 1 14px;
          flex:1 1 14px;
  min-height:0;
  padding:0;
  width:30px; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:first-child{
    border-radius:0 3px 0 0; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:last-child{
    border-radius:0 0 3px 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:first-child{
  border-radius:3px 0 0 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:last-child{
  border-radius:0 0 0 3px; }

.bp3-numeric-input.bp3-large .bp3-button-group.bp3-vertical > .bp3-button{
  width:40px; }

form{
  display:block; }
.bp3-html-select select,
.bp3-select select{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  font-size:14px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  padding:5px 10px;
  text-align:left;
  vertical-align:middle;
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  color:#182026;
  -moz-appearance:none;
  -webkit-appearance:none;
  border-radius:3px;
  height:30px;
  padding:0 25px 0 10px;
  width:100%; }
  .bp3-html-select select > *, .bp3-select select > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-html-select select > .bp3-fill, .bp3-select select > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-html-select select::before,
  .bp3-select select::before, .bp3-html-select select > *, .bp3-select select > *{
    margin-right:7px; }
  .bp3-html-select select:empty::before,
  .bp3-select select:empty::before,
  .bp3-html-select select > :last-child,
  .bp3-select select > :last-child{
    margin-right:0; }
  .bp3-html-select select:hover,
  .bp3-select select:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-html-select select:active,
  .bp3-select select:active, .bp3-html-select select.bp3-active,
  .bp3-select select.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-html-select select:disabled,
  .bp3-select select:disabled, .bp3-html-select select.bp3-disabled,
  .bp3-select select.bp3-disabled{
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    outline:none; }
    .bp3-html-select select:disabled.bp3-active,
    .bp3-select select:disabled.bp3-active, .bp3-html-select select:disabled.bp3-active:hover,
    .bp3-select select:disabled.bp3-active:hover, .bp3-html-select select.bp3-disabled.bp3-active,
    .bp3-select select.bp3-disabled.bp3-active, .bp3-html-select select.bp3-disabled.bp3-active:hover,
    .bp3-select select.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }

.bp3-html-select.bp3-minimal select,
.bp3-select.bp3-minimal select{
  background:none;
  -webkit-box-shadow:none;
          box-shadow:none; }
  .bp3-html-select.bp3-minimal select:hover,
  .bp3-select.bp3-minimal select:hover{
    background:rgba(167, 182, 194, 0.3);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:#182026;
    text-decoration:none; }
  .bp3-html-select.bp3-minimal select:active,
  .bp3-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal select.bp3-active,
  .bp3-select.bp3-minimal select.bp3-active{
    background:rgba(115, 134, 148, 0.3);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:#182026; }
  .bp3-html-select.bp3-minimal select:disabled,
  .bp3-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal select:disabled:hover,
  .bp3-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal select.bp3-disabled,
  .bp3-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal select.bp3-disabled:hover,
  .bp3-select.bp3-minimal select.bp3-disabled:hover{
    background:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
    .bp3-html-select.bp3-minimal select:disabled.bp3-active,
    .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active{
      background:rgba(115, 134, 148, 0.3); }
  .bp3-dark .bp3-html-select.bp3-minimal select, .bp3-html-select.bp3-minimal .bp3-dark select,
  .bp3-dark .bp3-select.bp3-minimal select, .bp3-select.bp3-minimal .bp3-dark select{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:inherit; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover, .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover{
      background:rgba(138, 155, 168, 0.15); }
    .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:rgba(138, 155, 168, 0.3);
      color:#f5f8fa; }
    .bp3-dark .bp3-html-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal .bp3-dark select:disabled,
    .bp3-dark .bp3-select.bp3-minimal select:disabled, .bp3-select.bp3-minimal .bp3-dark select:disabled, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select:disabled:hover, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover{
      background:none;
      color:rgba(167, 182, 194, 0.6);
      cursor:not-allowed; }
      .bp3-dark .bp3-html-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active{
        background:rgba(138, 155, 168, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-primary,
  .bp3-select.bp3-minimal select.bp3-intent-primary{
    color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover{
      background:rgba(19, 124, 189, 0.15);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:rgba(19, 124, 189, 0.3);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled{
      background:none;
      color:rgba(16, 107, 163, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active{
        background:rgba(19, 124, 189, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
      stroke:#106ba3; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary{
      color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.2);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(72, 175, 240, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-success,
  .bp3-select.bp3-minimal select.bp3-intent-success{
    color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover{
      background:rgba(15, 153, 96, 0.15);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:rgba(15, 153, 96, 0.3);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled{
      background:none;
      color:rgba(13, 128, 80, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active{
        background:rgba(15, 153, 96, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
      stroke:#0d8050; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success{
      color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.2);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(61, 204, 145, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-warning,
  .bp3-select.bp3-minimal select.bp3-intent-warning{
    color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover{
      background:rgba(217, 130, 43, 0.15);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:rgba(217, 130, 43, 0.3);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled{
      background:none;
      color:rgba(191, 115, 38, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active{
        background:rgba(217, 130, 43, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
      stroke:#bf7326; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning{
      color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.2);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(255, 179, 102, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-danger,
  .bp3-select.bp3-minimal select.bp3-intent-danger{
    color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover{
      background:rgba(219, 55, 55, 0.15);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:rgba(219, 55, 55, 0.3);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled{
      background:none;
      color:rgba(194, 48, 48, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active{
        background:rgba(219, 55, 55, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
      stroke:#c23030; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger{
      color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.2);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(255, 115, 115, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }

.bp3-html-select.bp3-large select,
.bp3-select.bp3-large select{
  font-size:16px;
  height:40px;
  padding-right:35px; }

.bp3-dark .bp3-html-select select, .bp3-dark .bp3-select select{
  background-color:#394b59;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
  color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover, .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    background-color:#202b33;
    background-image:none;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-html-select select:disabled, .bp3-dark .bp3-select select:disabled, .bp3-dark .bp3-html-select select.bp3-disabled, .bp3-dark .bp3-select select.bp3-disabled{
    background-color:rgba(57, 75, 89, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-html-select select:disabled.bp3-active, .bp3-dark .bp3-select select:disabled.bp3-active, .bp3-dark .bp3-html-select select.bp3-disabled.bp3-active, .bp3-dark .bp3-select select.bp3-disabled.bp3-active{
      background:rgba(57, 75, 89, 0.7); }
  .bp3-dark .bp3-html-select select .bp3-button-spinner .bp3-spinner-head, .bp3-dark .bp3-select select .bp3-button-spinner .bp3-spinner-head{
    background:rgba(16, 22, 26, 0.5);
    stroke:#8a9ba8; }

.bp3-html-select select:disabled,
.bp3-select select:disabled{
  background-color:rgba(206, 217, 224, 0.5);
  -webkit-box-shadow:none;
          box-shadow:none;
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-html-select .bp3-icon,
.bp3-select .bp3-icon, .bp3-select::after{
  color:#5c7080;
  pointer-events:none;
  position:absolute;
  right:7px;
  top:7px; }
  .bp3-html-select .bp3-disabled.bp3-icon,
  .bp3-select .bp3-disabled.bp3-icon, .bp3-disabled.bp3-select::after{
    color:rgba(92, 112, 128, 0.6); }
.bp3-html-select,
.bp3-select{
  display:inline-block;
  letter-spacing:normal;
  position:relative;
  vertical-align:middle; }
  .bp3-html-select select::-ms-expand,
  .bp3-select select::-ms-expand{
    display:none; }
  .bp3-html-select .bp3-icon,
  .bp3-select .bp3-icon{
    color:#5c7080; }
    .bp3-html-select .bp3-icon:hover,
    .bp3-select .bp3-icon:hover{
      color:#182026; }
    .bp3-dark .bp3-html-select .bp3-icon, .bp3-dark
    .bp3-select .bp3-icon{
      color:#a7b6c2; }
      .bp3-dark .bp3-html-select .bp3-icon:hover, .bp3-dark
      .bp3-select .bp3-icon:hover{
        color:#f5f8fa; }
  .bp3-html-select.bp3-large::after,
  .bp3-html-select.bp3-large .bp3-icon,
  .bp3-select.bp3-large::after,
  .bp3-select.bp3-large .bp3-icon{
    right:12px;
    top:12px; }
  .bp3-html-select.bp3-fill,
  .bp3-html-select.bp3-fill select,
  .bp3-select.bp3-fill,
  .bp3-select.bp3-fill select{
    width:100%; }
  .bp3-dark .bp3-html-select option, .bp3-dark
  .bp3-select option{
    background-color:#30404d;
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select option:disabled, .bp3-dark
  .bp3-select option:disabled{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-html-select::after, .bp3-dark
  .bp3-select::after{
    color:#a7b6c2; }

.bp3-select::after{
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  content:""; }
.bp3-running-text table, table.bp3-html-table{
  border-spacing:0;
  font-size:14px; }
  .bp3-running-text table th, table.bp3-html-table th,
  .bp3-running-text table td,
  table.bp3-html-table td{
    padding:11px;
    text-align:left;
    vertical-align:top; }
  .bp3-running-text table th, table.bp3-html-table th{
    color:#182026;
    font-weight:600; }
  
  .bp3-running-text table td,
  table.bp3-html-table td{
    color:#182026; }
  .bp3-running-text table tbody tr:first-child th, table.bp3-html-table tbody tr:first-child th,
  .bp3-running-text table tbody tr:first-child td,
  table.bp3-html-table tbody tr:first-child td,
  .bp3-running-text table tfoot tr:first-child th,
  table.bp3-html-table tfoot tr:first-child th,
  .bp3-running-text table tfoot tr:first-child td,
  table.bp3-html-table tfoot tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-running-text table th, .bp3-running-text .bp3-dark table th, .bp3-dark table.bp3-html-table th{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table td, .bp3-running-text .bp3-dark table td, .bp3-dark table.bp3-html-table td{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table tbody tr:first-child th, .bp3-running-text .bp3-dark table tbody tr:first-child th, .bp3-dark table.bp3-html-table tbody tr:first-child th,
  .bp3-dark .bp3-running-text table tbody tr:first-child td,
  .bp3-running-text .bp3-dark table tbody tr:first-child td,
  .bp3-dark table.bp3-html-table tbody tr:first-child td,
  .bp3-dark .bp3-running-text table tfoot tr:first-child th,
  .bp3-running-text .bp3-dark table tfoot tr:first-child th,
  .bp3-dark table.bp3-html-table tfoot tr:first-child th,
  .bp3-dark .bp3-running-text table tfoot tr:first-child td,
  .bp3-running-text .bp3-dark table tfoot tr:first-child td,
  .bp3-dark table.bp3-html-table tfoot tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }

table.bp3-html-table.bp3-html-table-condensed th,
table.bp3-html-table.bp3-html-table-condensed td, table.bp3-html-table.bp3-small th,
table.bp3-html-table.bp3-small td{
  padding-bottom:6px;
  padding-top:6px; }

table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(191, 204, 214, 0.15); }

table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered tbody tr td,
table.bp3-html-table.bp3-html-table-bordered tfoot tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child),
  table.bp3-html-table.bp3-html-table-bordered tfoot tr td:not(:first-child){
    -webkit-box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
  -webkit-box-shadow:none;
          box-shadow:none; }
  table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-interactive tbody tr:hover td{
  background-color:rgba(191, 204, 214, 0.3);
  cursor:pointer; }

table.bp3-html-table.bp3-interactive tbody tr:active td{
  background-color:rgba(191, 204, 214, 0.4); }

.bp3-dark table.bp3-html-table{ }
  .bp3-dark table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
    background:rgba(92, 112, 128, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td,
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tfoot tr td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child),
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered tfoot tr td:not(:first-child){
      -webkit-box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15);
              box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
    -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:first-child{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-dark table.bp3-html-table.bp3-interactive tbody tr:hover td{
    background-color:rgba(92, 112, 128, 0.3);
    cursor:pointer; }
  .bp3-dark table.bp3-html-table.bp3-interactive tbody tr:active td{
    background-color:rgba(92, 112, 128, 0.4); }

.bp3-key-combo{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center; }
  .bp3-key-combo > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-key-combo > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-key-combo::before,
  .bp3-key-combo > *{
    margin-right:5px; }
  .bp3-key-combo:empty::before,
  .bp3-key-combo > :last-child{
    margin-right:0; }

.bp3-hotkey-dialog{
  padding-bottom:0;
  top:40px; }
  .bp3-hotkey-dialog .bp3-dialog-body{
    margin:0;
    padding:0; }
  .bp3-hotkey-dialog .bp3-hotkey-label{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1; }

.bp3-hotkey-column{
  margin:auto;
  max-height:80vh;
  overflow-y:auto;
  padding:30px; }
  .bp3-hotkey-column .bp3-heading{
    margin-bottom:20px; }
    .bp3-hotkey-column .bp3-heading:not(:first-child){
      margin-top:40px; }

.bp3-hotkey{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:justify;
      -ms-flex-pack:justify;
          justify-content:space-between;
  margin-left:0;
  margin-right:0; }
  .bp3-hotkey:not(:last-child){
    margin-bottom:10px; }
.bp3-icon{
  display:inline-block;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  vertical-align:text-bottom; }
  .bp3-icon:not(:empty)::before{
    content:"" !important;
    content:unset !important; }
  .bp3-icon > svg{
    display:block; }
    .bp3-icon > svg:not([fill]){
      fill:currentColor; }

.bp3-icon.bp3-intent-primary, .bp3-icon-standard.bp3-intent-primary, .bp3-icon-large.bp3-intent-primary{
  color:#106ba3; }
  .bp3-dark .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-icon-large.bp3-intent-primary{
    color:#48aff0; }

.bp3-icon.bp3-intent-success, .bp3-icon-standard.bp3-intent-success, .bp3-icon-large.bp3-intent-success{
  color:#0d8050; }
  .bp3-dark .bp3-icon.bp3-intent-success, .bp3-dark .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-icon-large.bp3-intent-success{
    color:#3dcc91; }

.bp3-icon.bp3-intent-warning, .bp3-icon-standard.bp3-intent-warning, .bp3-icon-large.bp3-intent-warning{
  color:#bf7326; }
  .bp3-dark .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-icon-large.bp3-intent-warning{
    color:#ffb366; }

.bp3-icon.bp3-intent-danger, .bp3-icon-standard.bp3-intent-danger, .bp3-icon-large.bp3-intent-danger{
  color:#c23030; }
  .bp3-dark .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-icon-large.bp3-intent-danger{
    color:#ff7373; }

span.bp3-icon-standard{
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon-large{
  font-family:"Icons20", sans-serif;
  font-size:20px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon:empty{
  font-family:"Icons20";
  font-size:inherit;
  font-style:normal;
  font-weight:400;
  line-height:1; }
  span.bp3-icon:empty::before{
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased; }

.bp3-icon-add::before{
  content:""; }

.bp3-icon-add-column-left::before{
  content:""; }

.bp3-icon-add-column-right::before{
  content:""; }

.bp3-icon-add-row-bottom::before{
  content:""; }

.bp3-icon-add-row-top::before{
  content:""; }

.bp3-icon-add-to-artifact::before{
  content:""; }

.bp3-icon-add-to-folder::before{
  content:""; }

.bp3-icon-airplane::before{
  content:""; }

.bp3-icon-align-center::before{
  content:""; }

.bp3-icon-align-justify::before{
  content:""; }

.bp3-icon-align-left::before{
  content:""; }

.bp3-icon-align-right::before{
  content:""; }

.bp3-icon-alignment-bottom::before{
  content:""; }

.bp3-icon-alignment-horizontal-center::before{
  content:""; }

.bp3-icon-alignment-left::before{
  content:""; }

.bp3-icon-alignment-right::before{
  content:""; }

.bp3-icon-alignment-top::before{
  content:""; }

.bp3-icon-alignment-vertical-center::before{
  content:""; }

.bp3-icon-annotation::before{
  content:""; }

.bp3-icon-application::before{
  content:""; }

.bp3-icon-applications::before{
  content:""; }

.bp3-icon-archive::before{
  content:""; }

.bp3-icon-arrow-bottom-left::before{
  content:"↙"; }

.bp3-icon-arrow-bottom-right::before{
  content:"↘"; }

.bp3-icon-arrow-down::before{
  content:"↓"; }

.bp3-icon-arrow-left::before{
  content:"←"; }

.bp3-icon-arrow-right::before{
  content:"→"; }

.bp3-icon-arrow-top-left::before{
  content:"↖"; }

.bp3-icon-arrow-top-right::before{
  content:"↗"; }

.bp3-icon-arrow-up::before{
  content:"↑"; }

.bp3-icon-arrows-horizontal::before{
  content:"↔"; }

.bp3-icon-arrows-vertical::before{
  content:"↕"; }

.bp3-icon-asterisk::before{
  content:"*"; }

.bp3-icon-automatic-updates::before{
  content:""; }

.bp3-icon-badge::before{
  content:""; }

.bp3-icon-ban-circle::before{
  content:""; }

.bp3-icon-bank-account::before{
  content:""; }

.bp3-icon-barcode::before{
  content:""; }

.bp3-icon-blank::before{
  content:""; }

.bp3-icon-blocked-person::before{
  content:""; }

.bp3-icon-bold::before{
  content:""; }

.bp3-icon-book::before{
  content:""; }

.bp3-icon-bookmark::before{
  content:""; }

.bp3-icon-box::before{
  content:""; }

.bp3-icon-briefcase::before{
  content:""; }

.bp3-icon-bring-data::before{
  content:""; }

.bp3-icon-build::before{
  content:""; }

.bp3-icon-calculator::before{
  content:""; }

.bp3-icon-calendar::before{
  content:""; }

.bp3-icon-camera::before{
  content:""; }

.bp3-icon-caret-down::before{
  content:"⌄"; }

.bp3-icon-caret-left::before{
  content:"〈"; }

.bp3-icon-caret-right::before{
  content:"〉"; }

.bp3-icon-caret-up::before{
  content:"⌃"; }

.bp3-icon-cell-tower::before{
  content:""; }

.bp3-icon-changes::before{
  content:""; }

.bp3-icon-chart::before{
  content:""; }

.bp3-icon-chat::before{
  content:""; }

.bp3-icon-chevron-backward::before{
  content:""; }

.bp3-icon-chevron-down::before{
  content:""; }

.bp3-icon-chevron-forward::before{
  content:""; }

.bp3-icon-chevron-left::before{
  content:""; }

.bp3-icon-chevron-right::before{
  content:""; }

.bp3-icon-chevron-up::before{
  content:""; }

.bp3-icon-circle::before{
  content:""; }

.bp3-icon-circle-arrow-down::before{
  content:""; }

.bp3-icon-circle-arrow-left::before{
  content:""; }

.bp3-icon-circle-arrow-right::before{
  content:""; }

.bp3-icon-circle-arrow-up::before{
  content:""; }

.bp3-icon-citation::before{
  content:""; }

.bp3-icon-clean::before{
  content:""; }

.bp3-icon-clipboard::before{
  content:""; }

.bp3-icon-cloud::before{
  content:"☁"; }

.bp3-icon-cloud-download::before{
  content:""; }

.bp3-icon-cloud-upload::before{
  content:""; }

.bp3-icon-code::before{
  content:""; }

.bp3-icon-code-block::before{
  content:""; }

.bp3-icon-cog::before{
  content:""; }

.bp3-icon-collapse-all::before{
  content:""; }

.bp3-icon-column-layout::before{
  content:""; }

.bp3-icon-comment::before{
  content:""; }

.bp3-icon-comparison::before{
  content:""; }

.bp3-icon-compass::before{
  content:""; }

.bp3-icon-compressed::before{
  content:""; }

.bp3-icon-confirm::before{
  content:""; }

.bp3-icon-console::before{
  content:""; }

.bp3-icon-contrast::before{
  content:""; }

.bp3-icon-control::before{
  content:""; }

.bp3-icon-credit-card::before{
  content:""; }

.bp3-icon-cross::before{
  content:"✗"; }

.bp3-icon-crown::before{
  content:""; }

.bp3-icon-cube::before{
  content:""; }

.bp3-icon-cube-add::before{
  content:""; }

.bp3-icon-cube-remove::before{
  content:""; }

.bp3-icon-curved-range-chart::before{
  content:""; }

.bp3-icon-cut::before{
  content:""; }

.bp3-icon-dashboard::before{
  content:""; }

.bp3-icon-data-lineage::before{
  content:""; }

.bp3-icon-database::before{
  content:""; }

.bp3-icon-delete::before{
  content:""; }

.bp3-icon-delta::before{
  content:"Δ"; }

.bp3-icon-derive-column::before{
  content:""; }

.bp3-icon-desktop::before{
  content:""; }

.bp3-icon-diagnosis::before{
  content:""; }

.bp3-icon-diagram-tree::before{
  content:""; }

.bp3-icon-direction-left::before{
  content:""; }

.bp3-icon-direction-right::before{
  content:""; }

.bp3-icon-disable::before{
  content:""; }

.bp3-icon-document::before{
  content:""; }

.bp3-icon-document-open::before{
  content:""; }

.bp3-icon-document-share::before{
  content:""; }

.bp3-icon-dollar::before{
  content:"$"; }

.bp3-icon-dot::before{
  content:"•"; }

.bp3-icon-double-caret-horizontal::before{
  content:""; }

.bp3-icon-double-caret-vertical::before{
  content:""; }

.bp3-icon-double-chevron-down::before{
  content:""; }

.bp3-icon-double-chevron-left::before{
  content:""; }

.bp3-icon-double-chevron-right::before{
  content:""; }

.bp3-icon-double-chevron-up::before{
  content:""; }

.bp3-icon-doughnut-chart::before{
  content:""; }

.bp3-icon-download::before{
  content:""; }

.bp3-icon-drag-handle-horizontal::before{
  content:""; }

.bp3-icon-drag-handle-vertical::before{
  content:""; }

.bp3-icon-draw::before{
  content:""; }

.bp3-icon-drive-time::before{
  content:""; }

.bp3-icon-duplicate::before{
  content:""; }

.bp3-icon-edit::before{
  content:"✎"; }

.bp3-icon-eject::before{
  content:"⏏"; }

.bp3-icon-endorsed::before{
  content:""; }

.bp3-icon-envelope::before{
  content:"✉"; }

.bp3-icon-equals::before{
  content:""; }

.bp3-icon-eraser::before{
  content:""; }

.bp3-icon-error::before{
  content:""; }

.bp3-icon-euro::before{
  content:"€"; }

.bp3-icon-exchange::before{
  content:""; }

.bp3-icon-exclude-row::before{
  content:""; }

.bp3-icon-expand-all::before{
  content:""; }

.bp3-icon-export::before{
  content:""; }

.bp3-icon-eye-off::before{
  content:""; }

.bp3-icon-eye-on::before{
  content:""; }

.bp3-icon-eye-open::before{
  content:""; }

.bp3-icon-fast-backward::before{
  content:""; }

.bp3-icon-fast-forward::before{
  content:""; }

.bp3-icon-feed::before{
  content:""; }

.bp3-icon-feed-subscribed::before{
  content:""; }

.bp3-icon-film::before{
  content:""; }

.bp3-icon-filter::before{
  content:""; }

.bp3-icon-filter-keep::before{
  content:""; }

.bp3-icon-filter-list::before{
  content:""; }

.bp3-icon-filter-open::before{
  content:""; }

.bp3-icon-filter-remove::before{
  content:""; }

.bp3-icon-flag::before{
  content:"⚑"; }

.bp3-icon-flame::before{
  content:""; }

.bp3-icon-flash::before{
  content:""; }

.bp3-icon-floppy-disk::before{
  content:""; }

.bp3-icon-flow-branch::before{
  content:""; }

.bp3-icon-flow-end::before{
  content:""; }

.bp3-icon-flow-linear::before{
  content:""; }

.bp3-icon-flow-review::before{
  content:""; }

.bp3-icon-flow-review-branch::before{
  content:""; }

.bp3-icon-flows::before{
  content:""; }

.bp3-icon-folder-close::before{
  content:""; }

.bp3-icon-folder-new::before{
  content:""; }

.bp3-icon-folder-open::before{
  content:""; }

.bp3-icon-folder-shared::before{
  content:""; }

.bp3-icon-folder-shared-open::before{
  content:""; }

.bp3-icon-follower::before{
  content:""; }

.bp3-icon-following::before{
  content:""; }

.bp3-icon-font::before{
  content:""; }

.bp3-icon-fork::before{
  content:""; }

.bp3-icon-form::before{
  content:""; }

.bp3-icon-full-circle::before{
  content:""; }

.bp3-icon-full-stacked-chart::before{
  content:""; }

.bp3-icon-fullscreen::before{
  content:""; }

.bp3-icon-function::before{
  content:""; }

.bp3-icon-gantt-chart::before{
  content:""; }

.bp3-icon-geolocation::before{
  content:""; }

.bp3-icon-geosearch::before{
  content:""; }

.bp3-icon-git-branch::before{
  content:""; }

.bp3-icon-git-commit::before{
  content:""; }

.bp3-icon-git-merge::before{
  content:""; }

.bp3-icon-git-new-branch::before{
  content:""; }

.bp3-icon-git-pull::before{
  content:""; }

.bp3-icon-git-push::before{
  content:""; }

.bp3-icon-git-repo::before{
  content:""; }

.bp3-icon-glass::before{
  content:""; }

.bp3-icon-globe::before{
  content:""; }

.bp3-icon-globe-network::before{
  content:""; }

.bp3-icon-graph::before{
  content:""; }

.bp3-icon-graph-remove::before{
  content:""; }

.bp3-icon-greater-than::before{
  content:""; }

.bp3-icon-greater-than-or-equal-to::before{
  content:""; }

.bp3-icon-grid::before{
  content:""; }

.bp3-icon-grid-view::before{
  content:""; }

.bp3-icon-group-objects::before{
  content:""; }

.bp3-icon-grouped-bar-chart::before{
  content:""; }

.bp3-icon-hand::before{
  content:""; }

.bp3-icon-hand-down::before{
  content:""; }

.bp3-icon-hand-left::before{
  content:""; }

.bp3-icon-hand-right::before{
  content:""; }

.bp3-icon-hand-up::before{
  content:""; }

.bp3-icon-header::before{
  content:""; }

.bp3-icon-header-one::before{
  content:""; }

.bp3-icon-header-two::before{
  content:""; }

.bp3-icon-headset::before{
  content:""; }

.bp3-icon-heart::before{
  content:"♥"; }

.bp3-icon-heart-broken::before{
  content:""; }

.bp3-icon-heat-grid::before{
  content:""; }

.bp3-icon-heatmap::before{
  content:""; }

.bp3-icon-help::before{
  content:"?"; }

.bp3-icon-helper-management::before{
  content:""; }

.bp3-icon-highlight::before{
  content:""; }

.bp3-icon-history::before{
  content:""; }

.bp3-icon-home::before{
  content:"⌂"; }

.bp3-icon-horizontal-bar-chart::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-asc::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-desc::before{
  content:""; }

.bp3-icon-horizontal-distribution::before{
  content:""; }

.bp3-icon-id-number::before{
  content:""; }

.bp3-icon-image-rotate-left::before{
  content:""; }

.bp3-icon-image-rotate-right::before{
  content:""; }

.bp3-icon-import::before{
  content:""; }

.bp3-icon-inbox::before{
  content:""; }

.bp3-icon-inbox-filtered::before{
  content:""; }

.bp3-icon-inbox-geo::before{
  content:""; }

.bp3-icon-inbox-search::before{
  content:""; }

.bp3-icon-inbox-update::before{
  content:""; }

.bp3-icon-info-sign::before{
  content:"ℹ"; }

.bp3-icon-inheritance::before{
  content:""; }

.bp3-icon-inner-join::before{
  content:""; }

.bp3-icon-insert::before{
  content:""; }

.bp3-icon-intersection::before{
  content:""; }

.bp3-icon-ip-address::before{
  content:""; }

.bp3-icon-issue::before{
  content:""; }

.bp3-icon-issue-closed::before{
  content:""; }

.bp3-icon-issue-new::before{
  content:""; }

.bp3-icon-italic::before{
  content:""; }

.bp3-icon-join-table::before{
  content:""; }

.bp3-icon-key::before{
  content:""; }

.bp3-icon-key-backspace::before{
  content:""; }

.bp3-icon-key-command::before{
  content:""; }

.bp3-icon-key-control::before{
  content:""; }

.bp3-icon-key-delete::before{
  content:""; }

.bp3-icon-key-enter::before{
  content:""; }

.bp3-icon-key-escape::before{
  content:""; }

.bp3-icon-key-option::before{
  content:""; }

.bp3-icon-key-shift::before{
  content:""; }

.bp3-icon-key-tab::before{
  content:""; }

.bp3-icon-known-vehicle::before{
  content:""; }

.bp3-icon-lab-test::before{
  content:""; }

.bp3-icon-label::before{
  content:""; }

.bp3-icon-layer::before{
  content:""; }

.bp3-icon-layers::before{
  content:""; }

.bp3-icon-layout::before{
  content:""; }

.bp3-icon-layout-auto::before{
  content:""; }

.bp3-icon-layout-balloon::before{
  content:""; }

.bp3-icon-layout-circle::before{
  content:""; }

.bp3-icon-layout-grid::before{
  content:""; }

.bp3-icon-layout-group-by::before{
  content:""; }

.bp3-icon-layout-hierarchy::before{
  content:""; }

.bp3-icon-layout-linear::before{
  content:""; }

.bp3-icon-layout-skew-grid::before{
  content:""; }

.bp3-icon-layout-sorted-clusters::before{
  content:""; }

.bp3-icon-learning::before{
  content:""; }

.bp3-icon-left-join::before{
  content:""; }

.bp3-icon-less-than::before{
  content:""; }

.bp3-icon-less-than-or-equal-to::before{
  content:""; }

.bp3-icon-lifesaver::before{
  content:""; }

.bp3-icon-lightbulb::before{
  content:""; }

.bp3-icon-link::before{
  content:""; }

.bp3-icon-list::before{
  content:"☰"; }

.bp3-icon-list-columns::before{
  content:""; }

.bp3-icon-list-detail-view::before{
  content:""; }

.bp3-icon-locate::before{
  content:""; }

.bp3-icon-lock::before{
  content:""; }

.bp3-icon-log-in::before{
  content:""; }

.bp3-icon-log-out::before{
  content:""; }

.bp3-icon-manual::before{
  content:""; }

.bp3-icon-manually-entered-data::before{
  content:""; }

.bp3-icon-map::before{
  content:""; }

.bp3-icon-map-create::before{
  content:""; }

.bp3-icon-map-marker::before{
  content:""; }

.bp3-icon-maximize::before{
  content:""; }

.bp3-icon-media::before{
  content:""; }

.bp3-icon-menu::before{
  content:""; }

.bp3-icon-menu-closed::before{
  content:""; }

.bp3-icon-menu-open::before{
  content:""; }

.bp3-icon-merge-columns::before{
  content:""; }

.bp3-icon-merge-links::before{
  content:""; }

.bp3-icon-minimize::before{
  content:""; }

.bp3-icon-minus::before{
  content:"−"; }

.bp3-icon-mobile-phone::before{
  content:""; }

.bp3-icon-mobile-video::before{
  content:""; }

.bp3-icon-moon::before{
  content:""; }

.bp3-icon-more::before{
  content:""; }

.bp3-icon-mountain::before{
  content:""; }

.bp3-icon-move::before{
  content:""; }

.bp3-icon-mugshot::before{
  content:""; }

.bp3-icon-multi-select::before{
  content:""; }

.bp3-icon-music::before{
  content:""; }

.bp3-icon-new-drawing::before{
  content:""; }

.bp3-icon-new-grid-item::before{
  content:""; }

.bp3-icon-new-layer::before{
  content:""; }

.bp3-icon-new-layers::before{
  content:""; }

.bp3-icon-new-link::before{
  content:""; }

.bp3-icon-new-object::before{
  content:""; }

.bp3-icon-new-person::before{
  content:""; }

.bp3-icon-new-prescription::before{
  content:""; }

.bp3-icon-new-text-box::before{
  content:""; }

.bp3-icon-ninja::before{
  content:""; }

.bp3-icon-not-equal-to::before{
  content:""; }

.bp3-icon-notifications::before{
  content:""; }

.bp3-icon-notifications-updated::before{
  content:""; }

.bp3-icon-numbered-list::before{
  content:""; }

.bp3-icon-numerical::before{
  content:""; }

.bp3-icon-office::before{
  content:""; }

.bp3-icon-offline::before{
  content:""; }

.bp3-icon-oil-field::before{
  content:""; }

.bp3-icon-one-column::before{
  content:""; }

.bp3-icon-outdated::before{
  content:""; }

.bp3-icon-page-layout::before{
  content:""; }

.bp3-icon-panel-stats::before{
  content:""; }

.bp3-icon-panel-table::before{
  content:""; }

.bp3-icon-paperclip::before{
  content:""; }

.bp3-icon-paragraph::before{
  content:""; }

.bp3-icon-path::before{
  content:""; }

.bp3-icon-path-search::before{
  content:""; }

.bp3-icon-pause::before{
  content:""; }

.bp3-icon-people::before{
  content:""; }

.bp3-icon-percentage::before{
  content:""; }

.bp3-icon-person::before{
  content:""; }

.bp3-icon-phone::before{
  content:"☎"; }

.bp3-icon-pie-chart::before{
  content:""; }

.bp3-icon-pin::before{
  content:""; }

.bp3-icon-pivot::before{
  content:""; }

.bp3-icon-pivot-table::before{
  content:""; }

.bp3-icon-play::before{
  content:""; }

.bp3-icon-plus::before{
  content:"+"; }

.bp3-icon-polygon-filter::before{
  content:""; }

.bp3-icon-power::before{
  content:""; }

.bp3-icon-predictive-analysis::before{
  content:""; }

.bp3-icon-prescription::before{
  content:""; }

.bp3-icon-presentation::before{
  content:""; }

.bp3-icon-print::before{
  content:"⎙"; }

.bp3-icon-projects::before{
  content:""; }

.bp3-icon-properties::before{
  content:""; }

.bp3-icon-property::before{
  content:""; }

.bp3-icon-publish-function::before{
  content:""; }

.bp3-icon-pulse::before{
  content:""; }

.bp3-icon-random::before{
  content:""; }

.bp3-icon-record::before{
  content:""; }

.bp3-icon-redo::before{
  content:""; }

.bp3-icon-refresh::before{
  content:""; }

.bp3-icon-regression-chart::before{
  content:""; }

.bp3-icon-remove::before{
  content:""; }

.bp3-icon-remove-column::before{
  content:""; }

.bp3-icon-remove-column-left::before{
  content:""; }

.bp3-icon-remove-column-right::before{
  content:""; }

.bp3-icon-remove-row-bottom::before{
  content:""; }

.bp3-icon-remove-row-top::before{
  content:""; }

.bp3-icon-repeat::before{
  content:""; }

.bp3-icon-reset::before{
  content:""; }

.bp3-icon-resolve::before{
  content:""; }

.bp3-icon-rig::before{
  content:""; }

.bp3-icon-right-join::before{
  content:""; }

.bp3-icon-ring::before{
  content:""; }

.bp3-icon-rotate-document::before{
  content:""; }

.bp3-icon-rotate-page::before{
  content:""; }

.bp3-icon-satellite::before{
  content:""; }

.bp3-icon-saved::before{
  content:""; }

.bp3-icon-scatter-plot::before{
  content:""; }

.bp3-icon-search::before{
  content:""; }

.bp3-icon-search-around::before{
  content:""; }

.bp3-icon-search-template::before{
  content:""; }

.bp3-icon-search-text::before{
  content:""; }

.bp3-icon-segmented-control::before{
  content:""; }

.bp3-icon-select::before{
  content:""; }

.bp3-icon-selection::before{
  content:"⦿"; }

.bp3-icon-send-to::before{
  content:""; }

.bp3-icon-send-to-graph::before{
  content:""; }

.bp3-icon-send-to-map::before{
  content:""; }

.bp3-icon-series-add::before{
  content:""; }

.bp3-icon-series-configuration::before{
  content:""; }

.bp3-icon-series-derived::before{
  content:""; }

.bp3-icon-series-filtered::before{
  content:""; }

.bp3-icon-series-search::before{
  content:""; }

.bp3-icon-settings::before{
  content:""; }

.bp3-icon-share::before{
  content:""; }

.bp3-icon-shield::before{
  content:""; }

.bp3-icon-shop::before{
  content:""; }

.bp3-icon-shopping-cart::before{
  content:""; }

.bp3-icon-signal-search::before{
  content:""; }

.bp3-icon-sim-card::before{
  content:""; }

.bp3-icon-slash::before{
  content:""; }

.bp3-icon-small-cross::before{
  content:""; }

.bp3-icon-small-minus::before{
  content:""; }

.bp3-icon-small-plus::before{
  content:""; }

.bp3-icon-small-tick::before{
  content:""; }

.bp3-icon-snowflake::before{
  content:""; }

.bp3-icon-social-media::before{
  content:""; }

.bp3-icon-sort::before{
  content:""; }

.bp3-icon-sort-alphabetical::before{
  content:""; }

.bp3-icon-sort-alphabetical-desc::before{
  content:""; }

.bp3-icon-sort-asc::before{
  content:""; }

.bp3-icon-sort-desc::before{
  content:""; }

.bp3-icon-sort-numerical::before{
  content:""; }

.bp3-icon-sort-numerical-desc::before{
  content:""; }

.bp3-icon-split-columns::before{
  content:""; }

.bp3-icon-square::before{
  content:""; }

.bp3-icon-stacked-chart::before{
  content:""; }

.bp3-icon-star::before{
  content:"★"; }

.bp3-icon-star-empty::before{
  content:"☆"; }

.bp3-icon-step-backward::before{
  content:""; }

.bp3-icon-step-chart::before{
  content:""; }

.bp3-icon-step-forward::before{
  content:""; }

.bp3-icon-stop::before{
  content:""; }

.bp3-icon-stopwatch::before{
  content:""; }

.bp3-icon-strikethrough::before{
  content:""; }

.bp3-icon-style::before{
  content:""; }

.bp3-icon-swap-horizontal::before{
  content:""; }

.bp3-icon-swap-vertical::before{
  content:""; }

.bp3-icon-symbol-circle::before{
  content:""; }

.bp3-icon-symbol-cross::before{
  content:""; }

.bp3-icon-symbol-diamond::before{
  content:""; }

.bp3-icon-symbol-square::before{
  content:""; }

.bp3-icon-symbol-triangle-down::before{
  content:""; }

.bp3-icon-symbol-triangle-up::before{
  content:""; }

.bp3-icon-tag::before{
  content:""; }

.bp3-icon-take-action::before{
  content:""; }

.bp3-icon-taxi::before{
  content:""; }

.bp3-icon-text-highlight::before{
  content:""; }

.bp3-icon-th::before{
  content:""; }

.bp3-icon-th-derived::before{
  content:""; }

.bp3-icon-th-disconnect::before{
  content:""; }

.bp3-icon-th-filtered::before{
  content:""; }

.bp3-icon-th-list::before{
  content:""; }

.bp3-icon-thumbs-down::before{
  content:""; }

.bp3-icon-thumbs-up::before{
  content:""; }

.bp3-icon-tick::before{
  content:"✓"; }

.bp3-icon-tick-circle::before{
  content:""; }

.bp3-icon-time::before{
  content:"⏲"; }

.bp3-icon-timeline-area-chart::before{
  content:""; }

.bp3-icon-timeline-bar-chart::before{
  content:""; }

.bp3-icon-timeline-events::before{
  content:""; }

.bp3-icon-timeline-line-chart::before{
  content:""; }

.bp3-icon-tint::before{
  content:""; }

.bp3-icon-torch::before{
  content:""; }

.bp3-icon-tractor::before{
  content:""; }

.bp3-icon-train::before{
  content:""; }

.bp3-icon-translate::before{
  content:""; }

.bp3-icon-trash::before{
  content:""; }

.bp3-icon-tree::before{
  content:""; }

.bp3-icon-trending-down::before{
  content:""; }

.bp3-icon-trending-up::before{
  content:""; }

.bp3-icon-truck::before{
  content:""; }

.bp3-icon-two-columns::before{
  content:""; }

.bp3-icon-unarchive::before{
  content:""; }

.bp3-icon-underline::before{
  content:"⎁"; }

.bp3-icon-undo::before{
  content:"⎌"; }

.bp3-icon-ungroup-objects::before{
  content:""; }

.bp3-icon-unknown-vehicle::before{
  content:""; }

.bp3-icon-unlock::before{
  content:""; }

.bp3-icon-unpin::before{
  content:""; }

.bp3-icon-unresolve::before{
  content:""; }

.bp3-icon-updated::before{
  content:""; }

.bp3-icon-upload::before{
  content:""; }

.bp3-icon-user::before{
  content:""; }

.bp3-icon-variable::before{
  content:""; }

.bp3-icon-vertical-bar-chart-asc::before{
  content:""; }

.bp3-icon-vertical-bar-chart-desc::before{
  content:""; }

.bp3-icon-vertical-distribution::before{
  content:""; }

.bp3-icon-video::before{
  content:""; }

.bp3-icon-volume-down::before{
  content:""; }

.bp3-icon-volume-off::before{
  content:""; }

.bp3-icon-volume-up::before{
  content:""; }

.bp3-icon-walk::before{
  content:""; }

.bp3-icon-warning-sign::before{
  content:""; }

.bp3-icon-waterfall-chart::before{
  content:""; }

.bp3-icon-widget::before{
  content:""; }

.bp3-icon-widget-button::before{
  content:""; }

.bp3-icon-widget-footer::before{
  content:""; }

.bp3-icon-widget-header::before{
  content:""; }

.bp3-icon-wrench::before{
  content:""; }

.bp3-icon-zoom-in::before{
  content:""; }

.bp3-icon-zoom-out::before{
  content:""; }

.bp3-icon-zoom-to-fit::before{
  content:""; }
.bp3-submenu > .bp3-popover-wrapper{
  display:block; }

.bp3-submenu .bp3-popover-target{
  display:block; }
  .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{ }

.bp3-submenu.bp3-popover{
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0 5px; }
  .bp3-submenu.bp3-popover > .bp3-popover-content{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-submenu.bp3-popover, .bp3-submenu.bp3-popover.bp3-dark{
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-dark .bp3-submenu.bp3-popover > .bp3-popover-content, .bp3-submenu.bp3-popover.bp3-dark > .bp3-popover-content{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
.bp3-menu{
  background:#ffffff;
  border-radius:3px;
  color:#182026;
  list-style:none;
  margin:0;
  min-width:180px;
  padding:5px;
  text-align:left; }

.bp3-menu-divider{
  border-top:1px solid rgba(16, 22, 26, 0.15);
  display:block;
  margin:5px; }
  .bp3-dark .bp3-menu-divider{
    border-top-color:rgba(255, 255, 255, 0.15); }

.bp3-menu-item{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  border-radius:2px;
  color:inherit;
  line-height:20px;
  padding:5px 7px;
  text-decoration:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-menu-item > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-menu-item > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-menu-item::before,
  .bp3-menu-item > *{
    margin-right:7px; }
  .bp3-menu-item:empty::before,
  .bp3-menu-item > :last-child{
    margin-right:0; }
  .bp3-menu-item > .bp3-fill{
    word-break:break-word; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    background-color:rgba(167, 182, 194, 0.3);
    cursor:pointer;
    text-decoration:none; }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-dark .bp3-menu-item{
    color:inherit; }
    .bp3-dark .bp3-menu-item:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
      background-color:rgba(138, 155, 168, 0.15);
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-disabled{
      background-color:inherit;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-menu-item.bp3-intent-primary{
    color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-primary::before, .bp3-menu-item.bp3-intent-primary::after,
    .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary:active, .bp3-menu-item.bp3-intent-primary:active::before, .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-success{
    color:#0d8050; }
    .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-success::before, .bp3-menu-item.bp3-intent-success::after,
    .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-menu-item.bp3-intent-success:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success:active, .bp3-menu-item.bp3-intent-success:active::before, .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-warning{
    color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-warning::before, .bp3-menu-item.bp3-intent-warning::after,
    .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning:active, .bp3-menu-item.bp3-intent-warning:active::before, .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-danger{
    color:#c23030; }
    .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-danger::before, .bp3-menu-item.bp3-intent-danger::after,
    .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger:active, .bp3-menu-item.bp3-intent-danger:active::before, .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    margin-right:7px; }
  .bp3-menu-item::before,
  .bp3-menu-item > .bp3-icon{
    color:#5c7080;
    margin-top:2px; }
  .bp3-menu-item .bp3-menu-item-label{
    color:#5c7080; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    color:inherit; }
  .bp3-menu-item.bp3-active, .bp3-menu-item:active{
    background-color:rgba(115, 134, 148, 0.3); }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit !important;
    color:rgba(92, 112, 128, 0.6) !important;
    cursor:not-allowed !important;
    outline:none !important; }
    .bp3-menu-item.bp3-disabled::before,
    .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-large .bp3-menu-item{
    font-size:16px;
    line-height:22px;
    padding:9px 7px; }
    .bp3-large .bp3-menu-item .bp3-icon{
      margin-top:3px; }
    .bp3-large .bp3-menu-item::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      margin-right:10px;
      margin-top:1px; }

button.bp3-menu-item{
  background:none;
  border:none;
  text-align:left;
  width:100%; }
.bp3-menu-header{
  border-top:1px solid rgba(16, 22, 26, 0.15);
  display:block;
  margin:5px;
  cursor:default;
  padding-left:2px; }
  .bp3-dark .bp3-menu-header{
    border-top-color:rgba(255, 255, 255, 0.15); }
  .bp3-menu-header:first-of-type{
    border-top:none; }
  .bp3-menu-header > h6{
    color:#182026;
    font-weight:600;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    line-height:17px;
    margin:0;
    padding:10px 7px 0 1px; }
    .bp3-dark .bp3-menu-header > h6{
      color:#f5f8fa; }
  .bp3-menu-header:first-of-type > h6{
    padding-top:0; }
  .bp3-large .bp3-menu-header > h6{
    font-size:18px;
    padding-bottom:5px;
    padding-top:15px; }
  .bp3-large .bp3-menu-header:first-of-type > h6{
    padding-top:0; }

.bp3-dark .bp3-menu{
  background:#30404d;
  color:#f5f8fa; }

.bp3-dark .bp3-menu-item{ }
  .bp3-dark .bp3-menu-item.bp3-intent-primary{
    color:#48aff0; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary::before, .bp3-dark .bp3-menu-item.bp3-intent-primary::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#48aff0; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary:active, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-success{
    color:#3dcc91; }
    .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-success::before, .bp3-dark .bp3-menu-item.bp3-intent-success::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#3dcc91; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success:active, .bp3-dark .bp3-menu-item.bp3-intent-success:active::before, .bp3-dark .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning{
    color:#ffb366; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning::before, .bp3-dark .bp3-menu-item.bp3-intent-warning::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#ffb366; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning:active, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger{
    color:#ff7373; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger::before, .bp3-dark .bp3-menu-item.bp3-intent-danger::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#ff7373; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger:active, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item::before,
  .bp3-dark .bp3-menu-item > .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-menu-item .bp3-menu-item-label{
    color:#a7b6c2; }
  .bp3-dark .bp3-menu-item.bp3-active, .bp3-dark .bp3-menu-item:active{
    background-color:rgba(138, 155, 168, 0.3); }
  .bp3-dark .bp3-menu-item.bp3-disabled{
    color:rgba(167, 182, 194, 0.6) !important; }
    .bp3-dark .bp3-menu-item.bp3-disabled::before,
    .bp3-dark .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-dark .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(167, 182, 194, 0.6) !important; }

.bp3-dark .bp3-menu-divider,
.bp3-dark .bp3-menu-header{
  border-color:rgba(255, 255, 255, 0.15); }

.bp3-dark .bp3-menu-header > h6{
  color:#f5f8fa; }

.bp3-label .bp3-menu{
  margin-top:5px; }
.bp3-navbar{
  background-color:#ffffff;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  height:50px;
  padding:0 15px;
  position:relative;
  width:100%;
  z-index:10; }
  .bp3-navbar.bp3-dark,
  .bp3-dark .bp3-navbar{
    background-color:#394b59; }
  .bp3-navbar.bp3-dark{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-navbar{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-navbar.bp3-fixed-top{
    left:0;
    position:fixed;
    right:0;
    top:0; }

.bp3-navbar-heading{
  font-size:16px;
  margin-right:15px; }

.bp3-navbar-group{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:50px; }
  .bp3-navbar-group.bp3-align-left{
    float:left; }
  .bp3-navbar-group.bp3-align-right{
    float:right; }

.bp3-navbar-divider{
  border-left:1px solid rgba(16, 22, 26, 0.15);
  height:20px;
  margin:0 10px; }
  .bp3-dark .bp3-navbar-divider{
    border-left-color:rgba(255, 255, 255, 0.15); }
.bp3-non-ideal-state{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  height:100%;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  text-align:center;
  width:100%; }
  .bp3-non-ideal-state > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-non-ideal-state > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-non-ideal-state::before,
  .bp3-non-ideal-state > *{
    margin-bottom:20px; }
  .bp3-non-ideal-state:empty::before,
  .bp3-non-ideal-state > :last-child{
    margin-bottom:0; }
  .bp3-non-ideal-state > *{
    max-width:400px; }

.bp3-non-ideal-state-visual{
  color:rgba(92, 112, 128, 0.6);
  font-size:60px; }
  .bp3-dark .bp3-non-ideal-state-visual{
    color:rgba(167, 182, 194, 0.6); }

.bp3-overflow-list{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:nowrap;
      flex-wrap:nowrap;
  min-width:0; }

.bp3-overflow-list-spacer{
  -ms-flex-negative:1;
      flex-shrink:1;
  width:1px; }

body.bp3-overlay-open{
  overflow:hidden; }

.bp3-overlay{
  bottom:0;
  left:0;
  position:static;
  right:0;
  top:0;
  z-index:20; }
  .bp3-overlay:not(.bp3-overlay-open){
    pointer-events:none; }
  .bp3-overlay.bp3-overlay-container{
    overflow:hidden;
    position:fixed; }
    .bp3-overlay.bp3-overlay-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-scroll-container{
    overflow:auto;
    position:fixed; }
    .bp3-overlay.bp3-overlay-scroll-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-inline{
    display:inline;
    overflow:visible; }

.bp3-overlay-content{
  position:fixed;
  z-index:20; }
  .bp3-overlay-inline .bp3-overlay-content,
  .bp3-overlay-scroll-container .bp3-overlay-content{
    position:absolute; }

.bp3-overlay-backdrop{
  bottom:0;
  left:0;
  position:fixed;
  right:0;
  top:0;
  opacity:1;
  background-color:rgba(16, 22, 26, 0.7);
  overflow:auto;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none;
  z-index:20; }
  .bp3-overlay-backdrop.bp3-overlay-enter, .bp3-overlay-backdrop.bp3-overlay-appear{
    opacity:0; }
  .bp3-overlay-backdrop.bp3-overlay-enter-active, .bp3-overlay-backdrop.bp3-overlay-appear-active{
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-overlay-backdrop.bp3-overlay-exit{
    opacity:1; }
  .bp3-overlay-backdrop.bp3-overlay-exit-active{
    opacity:0;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-overlay-backdrop:focus{
    outline:none; }
  .bp3-overlay-inline .bp3-overlay-backdrop{
    position:absolute; }
.bp3-panel-stack{
  overflow:hidden;
  position:relative; }

.bp3-panel-stack-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  height:30px;
  z-index:1; }
  .bp3-dark .bp3-panel-stack-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack-header > span{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1; }
  .bp3-panel-stack-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack-view{
  bottom:0;
  left:0;
  position:absolute;
  right:0;
  top:0;
  background-color:#ffffff;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  overflow-y:auto;
  z-index:1; }
  .bp3-dark .bp3-panel-stack-view{
    background-color:#30404d; }
  .bp3-panel-stack-view:nth-last-child(n + 4){
    display:none; }

.bp3-panel-stack-push .bp3-panel-stack-enter, .bp3-panel-stack-push .bp3-panel-stack-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack-push .bp3-panel-stack-enter-active, .bp3-panel-stack-push .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-push .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-push .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-pop .bp3-panel-stack-enter, .bp3-panel-stack-pop .bp3-panel-stack-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter-active, .bp3-panel-stack-pop .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-pop .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-pop .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }
.bp3-panel-stack2{
  overflow:hidden;
  position:relative; }

.bp3-panel-stack2-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  height:30px;
  z-index:1; }
  .bp3-dark .bp3-panel-stack2-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack2-header > span{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1; }
  .bp3-panel-stack2-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack2-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack2-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack2-view{
  bottom:0;
  left:0;
  position:absolute;
  right:0;
  top:0;
  background-color:#ffffff;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  overflow-y:auto;
  z-index:1; }
  .bp3-dark .bp3-panel-stack2-view{
    background-color:#30404d; }
  .bp3-panel-stack2-view:nth-last-child(n + 4){
    display:none; }

.bp3-panel-stack2-push .bp3-panel-stack2-enter, .bp3-panel-stack2-push .bp3-panel-stack2-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack2-push .bp3-panel-stack2-enter-active, .bp3-panel-stack2-push .bp3-panel-stack2-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-push .bp3-panel-stack2-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack2-push .bp3-panel-stack2-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-pop .bp3-panel-stack2-enter, .bp3-panel-stack2-pop .bp3-panel-stack2-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack2-pop .bp3-panel-stack2-enter-active, .bp3-panel-stack2-pop .bp3-panel-stack2-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-pop .bp3-panel-stack2-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack2-pop .bp3-panel-stack2-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }
.bp3-popover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1);
  border-radius:3px;
  display:inline-block;
  z-index:20; }
  .bp3-popover .bp3-popover-arrow{
    height:30px;
    position:absolute;
    width:30px; }
    .bp3-popover .bp3-popover-arrow::before{
      height:20px;
      margin:5px;
      width:20px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover{
    margin-bottom:17px;
    margin-top:-17px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
      bottom:-11px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover{
    margin-left:17px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
      left:-11px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover{
    margin-top:17px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
      top:-11px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover{
    margin-left:-17px;
    margin-right:17px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
      right:-11px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-popover > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-popover > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
    top:-0.3934px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
    right:-0.3934px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
    left:-0.3934px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
    bottom:-0.3934px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-popover .bp3-popover-content{
    background:#ffffff;
    color:inherit; }
  .bp3-popover .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-popover .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-popover .bp3-popover-arrow-fill{
    fill:#ffffff; }
  .bp3-popover-enter > .bp3-popover, .bp3-popover-appear > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3); }
  .bp3-popover-enter-active > .bp3-popover, .bp3-popover-appear-active > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-popover-exit > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-popover .bp3-popover-content{
    border-radius:3px;
    position:relative; }
  .bp3-popover.bp3-popover-content-sizing .bp3-popover-content{
    max-width:350px;
    padding:20px; }
  .bp3-popover-target + .bp3-overlay .bp3-popover.bp3-popover-content-sizing{
    width:350px; }
  .bp3-popover.bp3-minimal{
    margin:0 !important; }
    .bp3-popover.bp3-minimal .bp3-popover-arrow{
      display:none; }
    .bp3-popover.bp3-minimal.bp3-popover{
      -webkit-transform:scale(1);
              transform:scale(1); }
      .bp3-popover-enter > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-enter-active > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-delay:0;
                transition-delay:0;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
      .bp3-popover-exit > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-exit-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-delay:0;
                transition-delay:0;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-popover.bp3-dark,
  .bp3-dark .bp3-popover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-popover .bp3-popover-content{
      background:#30404d;
      color:inherit; }
    .bp3-popover.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-popover .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-popover .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-popover.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-popover .bp3-popover-arrow-fill{
      fill:#30404d; }

.bp3-popover-arrow::before{
  border-radius:2px;
  content:"";
  display:block;
  position:absolute;
  -webkit-transform:rotate(45deg);
          transform:rotate(45deg); }

.bp3-tether-pinned .bp3-popover-arrow{
  display:none; }

.bp3-popover-backdrop{
  background:rgba(255, 255, 255, 0); }

.bp3-transition-container{
  opacity:1;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  z-index:20; }
  .bp3-transition-container.bp3-popover-enter, .bp3-transition-container.bp3-popover-appear{
    opacity:0; }
  .bp3-transition-container.bp3-popover-enter-active, .bp3-transition-container.bp3-popover-appear-active{
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-transition-container.bp3-popover-exit{
    opacity:1; }
  .bp3-transition-container.bp3-popover-exit-active{
    opacity:0;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-transition-container:focus{
    outline:none; }
  .bp3-transition-container.bp3-popover-leave .bp3-popover-content{
    pointer-events:none; }
  .bp3-transition-container[data-x-out-of-boundaries]{
    display:none; }

span.bp3-popover-target{
  display:inline-block; }

.bp3-popover-wrapper.bp3-fill{
  width:100%; }

.bp3-portal{
  left:0;
  position:absolute;
  right:0;
  top:0; }
@-webkit-keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }
@keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }

.bp3-progress-bar{
  background:rgba(92, 112, 128, 0.2);
  border-radius:40px;
  display:block;
  height:8px;
  overflow:hidden;
  position:relative;
  width:100%; }
  .bp3-progress-bar .bp3-progress-meter{
    background:linear-gradient(-45deg, rgba(255, 255, 255, 0.2) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.2) 50%, rgba(255, 255, 255, 0.2) 75%, transparent 75%);
    background-color:rgba(92, 112, 128, 0.8);
    background-size:30px 30px;
    border-radius:40px;
    height:100%;
    position:absolute;
    -webkit-transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    width:100%; }
  .bp3-progress-bar:not(.bp3-no-animation):not(.bp3-no-stripes) .bp3-progress-meter{
    animation:linear-progress-bar-stripes 300ms linear infinite reverse; }
  .bp3-progress-bar.bp3-no-stripes .bp3-progress-meter{
    background-image:none; }

.bp3-dark .bp3-progress-bar{
  background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-progress-bar .bp3-progress-meter{
    background-color:#8a9ba8; }

.bp3-progress-bar.bp3-intent-primary .bp3-progress-meter{
  background-color:#137cbd; }

.bp3-progress-bar.bp3-intent-success .bp3-progress-meter{
  background-color:#0f9960; }

.bp3-progress-bar.bp3-intent-warning .bp3-progress-meter{
  background-color:#d9822b; }

.bp3-progress-bar.bp3-intent-danger .bp3-progress-meter{
  background-color:#db3737; }
@-webkit-keyframes skeleton-glow{
  from{
    background:rgba(206, 217, 224, 0.2);
    border-color:rgba(206, 217, 224, 0.2); }
  to{
    background:rgba(92, 112, 128, 0.2);
    border-color:rgba(92, 112, 128, 0.2); } }
@keyframes skeleton-glow{
  from{
    background:rgba(206, 217, 224, 0.2);
    border-color:rgba(206, 217, 224, 0.2); }
  to{
    background:rgba(92, 112, 128, 0.2);
    border-color:rgba(92, 112, 128, 0.2); } }
.bp3-skeleton{
  -webkit-animation:1000ms linear infinite alternate skeleton-glow;
          animation:1000ms linear infinite alternate skeleton-glow;
  background:rgba(206, 217, 224, 0.2);
  background-clip:padding-box !important;
  border-color:rgba(206, 217, 224, 0.2) !important;
  border-radius:2px;
  -webkit-box-shadow:none !important;
          box-shadow:none !important;
  color:transparent !important;
  cursor:default;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-skeleton::before, .bp3-skeleton::after,
  .bp3-skeleton *{
    visibility:hidden !important; }
.bp3-slider{
  height:40px;
  min-width:150px;
  width:100%;
  cursor:default;
  outline:none;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-slider:hover{
    cursor:pointer; }
  .bp3-slider:active{
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-slider.bp3-disabled{
    cursor:not-allowed;
    opacity:0.5; }
  .bp3-slider.bp3-slider-unlabeled{
    height:16px; }

.bp3-slider-track,
.bp3-slider-progress{
  height:6px;
  left:0;
  right:0;
  top:5px;
  position:absolute; }

.bp3-slider-track{
  border-radius:3px;
  overflow:hidden; }

.bp3-slider-progress{
  background:rgba(92, 112, 128, 0.2); }
  .bp3-dark .bp3-slider-progress{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-slider-progress.bp3-intent-primary{
    background-color:#137cbd; }
  .bp3-slider-progress.bp3-intent-success{
    background-color:#0f9960; }
  .bp3-slider-progress.bp3-intent-warning{
    background-color:#d9822b; }
  .bp3-slider-progress.bp3-intent-danger{
    background-color:#db3737; }

.bp3-slider-handle{
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  color:#182026;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
  cursor:pointer;
  height:16px;
  left:0;
  position:absolute;
  top:0;
  width:16px; }
  .bp3-slider-handle:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-slider-handle:active, .bp3-slider-handle.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-slider-handle:disabled, .bp3-slider-handle.bp3-disabled{
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    outline:none; }
    .bp3-slider-handle:disabled.bp3-active, .bp3-slider-handle:disabled.bp3-active:hover, .bp3-slider-handle.bp3-disabled.bp3-active, .bp3-slider-handle.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }
  .bp3-slider-handle:focus{
    z-index:1; }
  .bp3-slider-handle:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
    cursor:-webkit-grab;
    cursor:grab;
    z-index:2; }
  .bp3-slider-handle.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-disabled .bp3-slider-handle{
    background:#bfccd6;
    -webkit-box-shadow:none;
            box-shadow:none;
    pointer-events:none; }
  .bp3-dark .bp3-slider-handle{
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover, .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-slider-handle:disabled, .bp3-dark .bp3-slider-handle.bp3-disabled{
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-slider-handle:disabled.bp3-active, .bp3-dark .bp3-slider-handle.bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-slider-handle .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-slider-handle, .bp3-dark .bp3-slider-handle:hover{
      background-color:#394b59; }
    .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#293742; }
  .bp3-dark .bp3-disabled .bp3-slider-handle{
    background:#5c7080;
    border-color:#5c7080;
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-slider-handle .bp3-slider-label{
    background:#394b59;
    border-radius:3px;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
    color:#f5f8fa;
    margin-left:8px; }
    .bp3-dark .bp3-slider-handle .bp3-slider-label{
      background:#e1e8ed;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
      color:#394b59; }
    .bp3-disabled .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-slider-handle.bp3-start, .bp3-slider-handle.bp3-end{
    width:8px; }
  .bp3-slider-handle.bp3-start{
    border-bottom-right-radius:0;
    border-top-right-radius:0; }
  .bp3-slider-handle.bp3-end{
    border-bottom-left-radius:0;
    border-top-left-radius:0;
    margin-left:8px; }
    .bp3-slider-handle.bp3-end .bp3-slider-label{
      margin-left:0; }

.bp3-slider-label{
  -webkit-transform:translate(-50%, 20px);
          transform:translate(-50%, 20px);
  display:inline-block;
  font-size:12px;
  line-height:1;
  padding:2px 5px;
  position:absolute;
  vertical-align:top; }

.bp3-slider.bp3-vertical{
  height:150px;
  min-width:40px;
  width:40px; }
  .bp3-slider.bp3-vertical .bp3-slider-track,
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    bottom:0;
    height:auto;
    left:5px;
    top:0;
    width:6px; }
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-label{
    -webkit-transform:translate(20px, 50%);
            transform:translate(20px, 50%); }
  .bp3-slider.bp3-vertical .bp3-slider-handle{
    top:auto; }
    .bp3-slider.bp3-vertical .bp3-slider-handle .bp3-slider-label{
      margin-left:0;
      margin-top:-8px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end, .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      height:8px;
      margin-left:0;
      width:16px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      border-bottom-right-radius:3px;
      border-top-left-radius:0; }
      .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start .bp3-slider-label{
        -webkit-transform:translate(20px);
                transform:translate(20px); }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end{
      border-bottom-left-radius:0;
      border-bottom-right-radius:0;
      border-top-left-radius:3px;
      margin-bottom:8px; }

@-webkit-keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

@keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

.bp3-spinner{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  overflow:visible;
  vertical-align:middle; }
  .bp3-spinner svg{
    display:block; }
  .bp3-spinner path{
    fill-opacity:0; }
  .bp3-spinner .bp3-spinner-head{
    stroke:rgba(92, 112, 128, 0.8);
    stroke-linecap:round;
    -webkit-transform-origin:center;
            transform-origin:center;
    -webkit-transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-spinner .bp3-spinner-track{
    stroke:rgba(92, 112, 128, 0.2); }

.bp3-spinner-animation{
  -webkit-animation:pt-spinner-animation 500ms linear infinite;
          animation:pt-spinner-animation 500ms linear infinite; }
  .bp3-no-spin > .bp3-spinner-animation{
    -webkit-animation:none;
            animation:none; }

.bp3-dark .bp3-spinner .bp3-spinner-head{
  stroke:#8a9ba8; }

.bp3-dark .bp3-spinner .bp3-spinner-track{
  stroke:rgba(16, 22, 26, 0.5); }

.bp3-spinner.bp3-intent-primary .bp3-spinner-head{
  stroke:#137cbd; }

.bp3-spinner.bp3-intent-success .bp3-spinner-head{
  stroke:#0f9960; }

.bp3-spinner.bp3-intent-warning .bp3-spinner-head{
  stroke:#d9822b; }

.bp3-spinner.bp3-intent-danger .bp3-spinner-head{
  stroke:#db3737; }
.bp3-tabs.bp3-vertical{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-tabs.bp3-vertical > .bp3-tab-list{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start;
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab{
      border-radius:3px;
      padding:0 10px;
      width:100%; }
      .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab[aria-selected="true"]{
        background-color:rgba(19, 124, 189, 0.2);
        -webkit-box-shadow:none;
                box-shadow:none; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab-indicator-wrapper .bp3-tab-indicator{
      background-color:rgba(19, 124, 189, 0.2);
      border-radius:3px;
      bottom:0;
      height:auto;
      left:0;
      right:0;
      top:0; }
  .bp3-tabs.bp3-vertical > .bp3-tab-panel{
    margin-top:0;
    padding-left:20px; }

.bp3-tab-list{
  -webkit-box-align:end;
      -ms-flex-align:end;
          align-items:flex-end;
  border:none;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  list-style:none;
  margin:0;
  padding:0;
  position:relative; }
  .bp3-tab-list > *:not(:last-child){
    margin-right:20px; }

.bp3-tab{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  color:#182026;
  cursor:pointer;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  font-size:14px;
  line-height:30px;
  max-width:100%;
  position:relative;
  vertical-align:top; }
  .bp3-tab a{
    color:inherit;
    display:block;
    text-decoration:none; }
  .bp3-tab-indicator-wrapper ~ .bp3-tab{
    background-color:transparent !important;
    -webkit-box-shadow:none !important;
            box-shadow:none !important; }
  .bp3-tab[aria-disabled="true"]{
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-tab[aria-selected="true"]{
    border-radius:0;
    -webkit-box-shadow:inset 0 -3px 0 #106ba3;
            box-shadow:inset 0 -3px 0 #106ba3; }
  .bp3-tab[aria-selected="true"], .bp3-tab:not([aria-disabled="true"]):hover{
    color:#106ba3; }
  .bp3-tab:focus{
    -moz-outline-radius:0; }
  .bp3-large > .bp3-tab{
    font-size:16px;
    line-height:40px; }

.bp3-tab-panel{
  margin-top:20px; }
  .bp3-tab-panel[aria-hidden="true"]{
    display:none; }

.bp3-tab-indicator-wrapper{
  left:0;
  pointer-events:none;
  position:absolute;
  top:0;
  -webkit-transform:translateX(0), translateY(0);
          transform:translateX(0), translateY(0);
  -webkit-transition:height, width, -webkit-transform;
  transition:height, width, -webkit-transform;
  transition:height, transform, width;
  transition:height, transform, width, -webkit-transform;
  -webkit-transition-duration:200ms;
          transition-duration:200ms;
  -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
          transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tab-indicator-wrapper .bp3-tab-indicator{
    background-color:#106ba3;
    bottom:0;
    height:3px;
    left:0;
    position:absolute;
    right:0; }
  .bp3-tab-indicator-wrapper.bp3-no-animation{
    -webkit-transition:none;
    transition:none; }

.bp3-dark .bp3-tab{
  color:#f5f8fa; }
  .bp3-dark .bp3-tab[aria-disabled="true"]{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tab[aria-selected="true"]{
    -webkit-box-shadow:inset 0 -3px 0 #48aff0;
            box-shadow:inset 0 -3px 0 #48aff0; }
  .bp3-dark .bp3-tab[aria-selected="true"], .bp3-dark .bp3-tab:not([aria-disabled="true"]):hover{
    color:#48aff0; }

.bp3-dark .bp3-tab-indicator{
  background-color:#48aff0; }

.bp3-flex-expander{
  -webkit-box-flex:1;
      -ms-flex:1 1;
          flex:1 1; }
.bp3-tag{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:#5c7080;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:none;
          box-shadow:none;
  color:#f5f8fa;
  font-size:12px;
  line-height:16px;
  max-width:100%;
  min-height:20px;
  min-width:20px;
  padding:2px 6px;
  position:relative; }
  .bp3-tag.bp3-interactive{
    cursor:pointer; }
    .bp3-tag.bp3-interactive:hover{
      background-color:rgba(92, 112, 128, 0.85); }
    .bp3-tag.bp3-interactive.bp3-active, .bp3-tag.bp3-interactive:active{
      background-color:rgba(92, 112, 128, 0.7); }
  .bp3-tag > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag::before,
  .bp3-tag > *{
    margin-right:4px; }
  .bp3-tag:empty::before,
  .bp3-tag > :last-child{
    margin-right:0; }
  .bp3-tag:focus{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:0;
    -moz-outline-radius:6px; }
  .bp3-tag.bp3-round{
    border-radius:30px;
    padding-left:8px;
    padding-right:8px; }
  .bp3-dark .bp3-tag{
    background-color:#bfccd6;
    color:#182026; }
    .bp3-dark .bp3-tag.bp3-interactive{
      cursor:pointer; }
      .bp3-dark .bp3-tag.bp3-interactive:hover{
        background-color:rgba(191, 204, 214, 0.85); }
      .bp3-dark .bp3-tag.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-interactive:active{
        background-color:rgba(191, 204, 214, 0.7); }
    .bp3-dark .bp3-tag > .bp3-icon, .bp3-dark .bp3-tag .bp3-icon-standard, .bp3-dark .bp3-tag .bp3-icon-large{
      fill:currentColor; }
  .bp3-tag > .bp3-icon, .bp3-tag .bp3-icon-standard, .bp3-tag .bp3-icon-large{
    fill:#ffffff; }
  .bp3-tag.bp3-large,
  .bp3-large .bp3-tag{
    font-size:14px;
    line-height:20px;
    min-height:30px;
    min-width:30px;
    padding:5px 10px; }
    .bp3-tag.bp3-large::before,
    .bp3-tag.bp3-large > *,
    .bp3-large .bp3-tag::before,
    .bp3-large .bp3-tag > *{
      margin-right:7px; }
    .bp3-tag.bp3-large:empty::before,
    .bp3-tag.bp3-large > :last-child,
    .bp3-large .bp3-tag:empty::before,
    .bp3-large .bp3-tag > :last-child{
      margin-right:0; }
    .bp3-tag.bp3-large.bp3-round,
    .bp3-large .bp3-tag.bp3-round{
      padding-left:12px;
      padding-right:12px; }
  .bp3-tag.bp3-intent-primary{
    background:#137cbd;
    color:#ffffff; }
    .bp3-tag.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.85); }
      .bp3-tag.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.7); }
  .bp3-tag.bp3-intent-success{
    background:#0f9960;
    color:#ffffff; }
    .bp3-tag.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.85); }
      .bp3-tag.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.7); }
  .bp3-tag.bp3-intent-warning{
    background:#d9822b;
    color:#ffffff; }
    .bp3-tag.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.85); }
      .bp3-tag.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.7); }
  .bp3-tag.bp3-intent-danger{
    background:#db3737;
    color:#ffffff; }
    .bp3-tag.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.85); }
      .bp3-tag.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.7); }
  .bp3-tag.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-tag.bp3-minimal > .bp3-icon, .bp3-tag.bp3-minimal .bp3-icon-standard, .bp3-tag.bp3-minimal .bp3-icon-large{
    fill:#5c7080; }
  .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
    background-color:rgba(138, 155, 168, 0.2);
    color:#182026; }
    .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
        background-color:rgba(92, 112, 128, 0.3); }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
        background-color:rgba(92, 112, 128, 0.4); }
    .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
      color:#f5f8fa; }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
          background-color:rgba(191, 204, 214, 0.3); }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
          background-color:rgba(191, 204, 214, 0.4); }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) > .bp3-icon, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-large{
        fill:#a7b6c2; }
  .bp3-tag.bp3-minimal.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15);
    color:#106ba3; }
    .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-primary > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-large{
      fill:#137cbd; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25);
      color:#48aff0; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
          background-color:rgba(19, 124, 189, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
          background-color:rgba(19, 124, 189, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15);
    color:#0d8050; }
    .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-success > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-large{
      fill:#0f9960; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25);
      color:#3dcc91; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
          background-color:rgba(15, 153, 96, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
          background-color:rgba(15, 153, 96, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15);
    color:#bf7326; }
    .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-warning > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-large{
      fill:#d9822b; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25);
      color:#ffb366; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
          background-color:rgba(217, 130, 43, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
          background-color:rgba(217, 130, 43, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15);
    color:#c23030; }
    .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-danger > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-large{
      fill:#db3737; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25);
      color:#ff7373; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
          background-color:rgba(219, 55, 55, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
          background-color:rgba(219, 55, 55, 0.45); }

.bp3-tag-remove{
  background:none;
  border:none;
  color:inherit;
  cursor:pointer;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin-bottom:-2px;
  margin-right:-6px !important;
  margin-top:-2px;
  opacity:0.5;
  padding:2px;
  padding-left:0; }
  .bp3-tag-remove:hover{
    background:none;
    opacity:0.8;
    text-decoration:none; }
  .bp3-tag-remove:active{
    opacity:1; }
  .bp3-tag-remove:empty::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    content:""; }
  .bp3-large .bp3-tag-remove{
    margin-right:-10px !important;
    padding:0 5px 0 0; }
    .bp3-large .bp3-tag-remove:empty::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1; }
.bp3-tag-input{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  cursor:text;
  height:auto;
  line-height:inherit;
  min-height:30px;
  padding-left:5px;
  padding-right:0; }
  .bp3-tag-input > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag-input > .bp3-tag-input-values{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag-input .bp3-tag-input-icon{
    color:#5c7080;
    margin-left:2px;
    margin-right:7px;
    margin-top:7px; }
  .bp3-tag-input .bp3-tag-input-values{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    -ms-flex-item-align:stretch;
        align-self:stretch;
    -ms-flex-wrap:wrap;
        flex-wrap:wrap;
    margin-right:7px;
    margin-top:5px;
    min-width:0; }
    .bp3-tag-input .bp3-tag-input-values > *{
      -webkit-box-flex:0;
          -ms-flex-positive:0;
              flex-grow:0;
      -ms-flex-negative:0;
          flex-shrink:0; }
    .bp3-tag-input .bp3-tag-input-values > .bp3-fill{
      -webkit-box-flex:1;
          -ms-flex-positive:1;
              flex-grow:1;
      -ms-flex-negative:1;
          flex-shrink:1; }
    .bp3-tag-input .bp3-tag-input-values::before,
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-right:5px; }
    .bp3-tag-input .bp3-tag-input-values:empty::before,
    .bp3-tag-input .bp3-tag-input-values > :last-child{
      margin-right:0; }
    .bp3-tag-input .bp3-tag-input-values:first-child .bp3-input-ghost:first-child{
      padding-left:5px; }
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-bottom:5px; }
  .bp3-tag-input .bp3-tag{
    overflow-wrap:break-word; }
    .bp3-tag-input .bp3-tag.bp3-active{
      outline:rgba(19, 124, 189, 0.6) auto 2px;
      outline-offset:0;
      -moz-outline-radius:6px; }
  .bp3-tag-input .bp3-input-ghost{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:20px;
    width:80px; }
    .bp3-tag-input .bp3-input-ghost:disabled, .bp3-tag-input .bp3-input-ghost.bp3-disabled{
      cursor:not-allowed; }
  .bp3-tag-input .bp3-button,
  .bp3-tag-input .bp3-spinner{
    margin:3px;
    margin-left:0; }
  .bp3-tag-input .bp3-button{
    min-height:24px;
    min-width:24px;
    padding:0 7px; }
  .bp3-tag-input.bp3-large{
    height:auto;
    min-height:40px; }
    .bp3-tag-input.bp3-large::before,
    .bp3-tag-input.bp3-large > *{
      margin-right:10px; }
    .bp3-tag-input.bp3-large:empty::before,
    .bp3-tag-input.bp3-large > :last-child{
      margin-right:0; }
    .bp3-tag-input.bp3-large .bp3-tag-input-icon{
      margin-left:5px;
      margin-top:10px; }
    .bp3-tag-input.bp3-large .bp3-input-ghost{
      line-height:30px; }
    .bp3-tag-input.bp3-large .bp3-button{
      min-height:30px;
      min-width:30px;
      padding:5px 10px;
      margin:5px;
      margin-left:0; }
    .bp3-tag-input.bp3-large .bp3-spinner{
      margin:8px;
      margin-left:0; }
  .bp3-tag-input.bp3-active{
    background-color:#ffffff;
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-tag-input .bp3-tag-input-icon, .bp3-tag-input.bp3-dark .bp3-tag-input-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-tag-input .bp3-input-ghost, .bp3-tag-input.bp3-dark .bp3-input-ghost{
    color:#f5f8fa; }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-webkit-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-moz-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost:-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::placeholder{
      color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tag-input.bp3-active, .bp3-tag-input.bp3-dark.bp3-active{
    background-color:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-primary, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-success, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-warning, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-danger, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-input-ghost{
  background:none;
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0; }
  .bp3-input-ghost::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost:focus{
    outline:none !important; }
.bp3-toast{
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin:20px 0 0;
  max-width:500px;
  min-width:300px;
  pointer-events:all;
  position:relative !important; }
  .bp3-toast.bp3-toast-enter, .bp3-toast.bp3-toast-appear{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active, .bp3-toast.bp3-toast-appear-active{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-toast.bp3-toast-enter ~ .bp3-toast, .bp3-toast.bp3-toast-appear ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active ~ .bp3-toast, .bp3-toast.bp3-toast-appear-active ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-toast.bp3-toast-exit{
    opacity:1;
    -webkit-filter:blur(0);
            filter:blur(0); }
  .bp3-toast.bp3-toast-exit-active{
    opacity:0;
    -webkit-filter:blur(10px);
            filter:blur(10px);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:opacity, filter;
    transition-property:opacity, filter, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-toast.bp3-toast-exit ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0); }
  .bp3-toast.bp3-toast-exit-active ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px);
    -webkit-transition-delay:50ms;
            transition-delay:50ms;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-toast .bp3-button-group{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    padding:5px;
    padding-left:0; }
  .bp3-toast > .bp3-icon{
    color:#5c7080;
    margin:12px;
    margin-right:0; }
  .bp3-toast.bp3-dark,
  .bp3-dark .bp3-toast{
    background-color:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-toast.bp3-dark > .bp3-icon,
    .bp3-dark .bp3-toast > .bp3-icon{
      color:#a7b6c2; }
  .bp3-toast[class*="bp3-intent-"] a{
    color:rgba(255, 255, 255, 0.7); }
    .bp3-toast[class*="bp3-intent-"] a:hover{
      color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] > .bp3-icon{
    color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button, .bp3-toast[class*="bp3-intent-"] .bp3-button::before,
  .bp3-toast[class*="bp3-intent-"] .bp3-button .bp3-icon, .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    color:rgba(255, 255, 255, 0.7) !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:focus{
    outline-color:rgba(255, 255, 255, 0.5); }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:hover{
    background-color:rgba(255, 255, 255, 0.15) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    background-color:rgba(255, 255, 255, 0.3) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button::after{
    background:rgba(255, 255, 255, 0.3) !important; }
  .bp3-toast.bp3-intent-primary{
    background-color:#137cbd;
    color:#ffffff; }
  .bp3-toast.bp3-intent-success{
    background-color:#0f9960;
    color:#ffffff; }
  .bp3-toast.bp3-intent-warning{
    background-color:#d9822b;
    color:#ffffff; }
  .bp3-toast.bp3-intent-danger{
    background-color:#db3737;
    color:#ffffff; }

.bp3-toast-message{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  padding:11px;
  word-break:break-word; }

.bp3-toast-container{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box !important;
  display:-ms-flexbox !important;
  display:flex !important;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  left:0;
  overflow:hidden;
  padding:0 20px 20px;
  pointer-events:none;
  right:0;
  z-index:40; }
  .bp3-toast-container.bp3-toast-container-in-portal{
    position:fixed; }
  .bp3-toast-container.bp3-toast-container-inline{
    position:absolute; }
  .bp3-toast-container.bp3-toast-container-top{
    top:0; }
  .bp3-toast-container.bp3-toast-container-bottom{
    bottom:0;
    -webkit-box-orient:vertical;
    -webkit-box-direction:reverse;
        -ms-flex-direction:column-reverse;
            flex-direction:column-reverse;
    top:auto; }
  .bp3-toast-container.bp3-toast-container-left{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
  .bp3-toast-container.bp3-toast-container-right{
    -webkit-box-align:end;
        -ms-flex-align:end;
            align-items:flex-end; }

.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active) ~ .bp3-toast, .bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active) ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-exit-active ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-leave-active ~ .bp3-toast{
  -webkit-transform:translateY(60px);
          transform:translateY(60px); }
.bp3-tooltip{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1); }
  .bp3-tooltip .bp3-popover-arrow{
    height:22px;
    position:absolute;
    width:22px; }
    .bp3-tooltip .bp3-popover-arrow::before{
      height:14px;
      margin:4px;
      width:14px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip{
    margin-bottom:11px;
    margin-top:-11px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
      bottom:-8px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip{
    margin-left:11px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
      left:-8px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip{
    margin-top:11px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
      top:-8px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip{
    margin-left:-11px;
    margin-right:11px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
      right:-8px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-tooltip > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-tooltip > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
    top:-0.22183px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
    right:-0.22183px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
    left:-0.22183px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
    bottom:-0.22183px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-tooltip .bp3-popover-content{
    background:#394b59;
    color:#f5f8fa; }
  .bp3-tooltip .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-tooltip .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-tooltip .bp3-popover-arrow-fill{
    fill:#394b59; }
  .bp3-popover-enter > .bp3-tooltip, .bp3-popover-appear > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8); }
  .bp3-popover-enter-active > .bp3-tooltip, .bp3-popover-appear-active > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-popover-exit > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tooltip .bp3-popover-content{
    padding:10px 12px; }
  .bp3-tooltip.bp3-dark,
  .bp3-dark .bp3-tooltip{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-tooltip .bp3-popover-content{
      background:#e1e8ed;
      color:#394b59; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-fill{
      fill:#e1e8ed; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-content{
    background:#137cbd;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-arrow-fill{
    fill:#137cbd; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-content{
    background:#0f9960;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-arrow-fill{
    fill:#0f9960; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-content{
    background:#d9822b;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-arrow-fill{
    fill:#d9822b; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-content{
    background:#db3737;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-arrow-fill{
    fill:#db3737; }

.bp3-tooltip-indicator{
  border-bottom:dotted 1px;
  cursor:help; }
.bp3-tree .bp3-icon, .bp3-tree .bp3-icon-standard, .bp3-tree .bp3-icon-large{
  color:#5c7080; }
  .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-tree .bp3-icon.bp3-intent-success, .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-tree-node-list{
  list-style:none;
  margin:0;
  padding-left:0; }

.bp3-tree-root{
  background-color:transparent;
  cursor:default;
  padding-left:0;
  position:relative; }

.bp3-tree-node-content-0{
  padding-left:0px; }

.bp3-tree-node-content-1{
  padding-left:23px; }

.bp3-tree-node-content-2{
  padding-left:46px; }

.bp3-tree-node-content-3{
  padding-left:69px; }

.bp3-tree-node-content-4{
  padding-left:92px; }

.bp3-tree-node-content-5{
  padding-left:115px; }

.bp3-tree-node-content-6{
  padding-left:138px; }

.bp3-tree-node-content-7{
  padding-left:161px; }

.bp3-tree-node-content-8{
  padding-left:184px; }

.bp3-tree-node-content-9{
  padding-left:207px; }

.bp3-tree-node-content-10{
  padding-left:230px; }

.bp3-tree-node-content-11{
  padding-left:253px; }

.bp3-tree-node-content-12{
  padding-left:276px; }

.bp3-tree-node-content-13{
  padding-left:299px; }

.bp3-tree-node-content-14{
  padding-left:322px; }

.bp3-tree-node-content-15{
  padding-left:345px; }

.bp3-tree-node-content-16{
  padding-left:368px; }

.bp3-tree-node-content-17{
  padding-left:391px; }

.bp3-tree-node-content-18{
  padding-left:414px; }

.bp3-tree-node-content-19{
  padding-left:437px; }

.bp3-tree-node-content-20{
  padding-left:460px; }

.bp3-tree-node-content{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:30px;
  padding-right:5px;
  width:100%; }
  .bp3-tree-node-content:hover{
    background-color:rgba(191, 204, 214, 0.4); }

.bp3-tree-node-caret,
.bp3-tree-node-caret-none{
  min-width:30px; }

.bp3-tree-node-caret{
  color:#5c7080;
  cursor:pointer;
  padding:7px;
  -webkit-transform:rotate(0deg);
          transform:rotate(0deg);
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tree-node-caret:hover{
    color:#182026; }
  .bp3-dark .bp3-tree-node-caret{
    color:#a7b6c2; }
    .bp3-dark .bp3-tree-node-caret:hover{
      color:#f5f8fa; }
  .bp3-tree-node-caret.bp3-tree-node-caret-open{
    -webkit-transform:rotate(90deg);
            transform:rotate(90deg); }
  .bp3-tree-node-caret.bp3-icon-standard::before{
    content:""; }

.bp3-tree-node-icon{
  margin-right:7px;
  position:relative; }

.bp3-tree-node-label{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-label span{
    display:inline; }

.bp3-tree-node-secondary-label{
  padding:0 5px;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-secondary-label .bp3-popover-wrapper,
  .bp3-tree-node-secondary-label .bp3-popover-target{
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-content{
  background-color:inherit;
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-caret,
.bp3-tree-node.bp3-disabled .bp3-tree-node-icon{
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content,
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-standard, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-large{
    color:#ffffff; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret::before{
    color:rgba(255, 255, 255, 0.7); }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret:hover::before{
    color:#ffffff; }

.bp3-dark .bp3-tree-node-content:hover{
  background-color:rgba(92, 112, 128, 0.3); }

.bp3-dark .bp3-tree .bp3-icon, .bp3-dark .bp3-tree .bp3-icon-standard, .bp3-dark .bp3-tree .bp3-icon-large{
  color:#a7b6c2; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-dark .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
.bp3-omnibar{
  -webkit-filter:blur(0);
          filter:blur(0);
  opacity:1;
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  left:calc(50% - 250px);
  top:20vh;
  width:500px;
  z-index:21; }
  .bp3-omnibar.bp3-overlay-enter, .bp3-omnibar.bp3-overlay-appear{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2; }
  .bp3-omnibar.bp3-overlay-enter-active, .bp3-omnibar.bp3-overlay-appear-active{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-omnibar.bp3-overlay-exit{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1; }
  .bp3-omnibar.bp3-overlay-exit-active{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-omnibar .bp3-input{
    background-color:transparent;
    border-radius:0; }
    .bp3-omnibar .bp3-input, .bp3-omnibar .bp3-input:focus{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-omnibar .bp3-menu{
    background-color:transparent;
    border-radius:0;
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
    max-height:calc(60vh - 40px);
    overflow:auto; }
    .bp3-omnibar .bp3-menu:empty{
      display:none; }
  .bp3-dark .bp3-omnibar, .bp3-omnibar.bp3-dark{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-omnibar-overlay .bp3-overlay-backdrop{
  background-color:rgba(16, 22, 26, 0.2); }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }

.bp3-multi-select{
  min-width:150px; }

.bp3-multi-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto; }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yMCA4aC0yLjgxYy0uNDUtLjc4LTEuMDctMS40NS0xLjgyLTEuOTZMMTcgNC40MSAxNS41OSAzbC0yLjE3IDIuMTdDMTIuOTYgNS4wNiAxMi40OSA1IDEyIDVjLS40OSAwLS45Ni4wNi0xLjQxLjE3TDguNDEgMyA3IDQuNDFsMS42MiAxLjYzQzcuODggNi41NSA3LjI2IDcuMjIgNi44MSA4SDR2MmgyLjA5Yy0uMDUuMzMtLjA5LjY2LS4wOSAxdjFINHYyaDJ2MWMwIC4zNC4wNC42Ny4wOSAxSDR2MmgyLjgxYzEuMDQgMS43OSAyLjk3IDMgNS4xOSAzczQuMTUtMS4yMSA1LjE5LTNIMjB2LTJoLTIuMDljLjA1LS4zMy4wOS0uNjYuMDktMXYtMWgydi0yaC0ydi0xYzAtLjM0LS4wNC0uNjctLjA5LTFIMjBWOHptLTYgOGgtNHYtMmg0djJ6bTAtNGgtNHYtMmg0djJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTExLjQgMTguNkw2LjggMTRMMTEuNCA5LjRMMTAgOEw0IDE0TDEwIDIwTDExLjQgMTguNlpNMTYuNiAxOC42TDIxLjIgMTRMMTYuNiA5LjRMMTggOEwyNCAxNEwxOCAyMEwxNi42IDE4LjZWMTguNloiLz4KCTwvZz4KPC9zdmc+Cg==);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1pY29uLWJyYW5kMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNmZmYiPgogICAgPHBhdGggZD0iTTEwNSAxMjcuM2g0MHYxMi44aC00MHpNNTEuMSA3N0w3NCA5OS45bC0yMy4zIDIzLjMgMTAuNSAxMC41IDIzLjMtMjMuM0w5NSA5OS45IDg0LjUgODkuNCA2MS42IDY2LjV6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copyright: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCI+CiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0xMS44OCw5LjE0YzEuMjgsMC4wNiwxLjYxLDEuMTUsMS42MywxLjY2aDEuNzljLTAuMDgtMS45OC0xLjQ5LTMuMTktMy40NS0zLjE5QzkuNjQsNy42MSw4LDksOCwxMi4xNCBjMCwxLjk0LDAuOTMsNC4yNCwzLjg0LDQuMjRjMi4yMiwwLDMuNDEtMS42NSwzLjQ0LTIuOTVoLTEuNzljLTAuMDMsMC41OS0wLjQ1LDEuMzgtMS42MywxLjQ0QzEwLjU1LDE0LjgzLDEwLDEzLjgxLDEwLDEyLjE0IEMxMCw5LjI1LDExLjI4LDkuMTYsMTEuODgsOS4xNHogTTEyLDJDNi40OCwyLDIsNi40OCwyLDEyczQuNDgsMTAsMTAsMTBzMTAtNC40OCwxMC0xMFMxNy41MiwyLDEyLDJ6IE0xMiwyMGMtNC40MSwwLTgtMy41OS04LTggczMuNTktOCw4LThzOCwzLjU5LDgsOFMxNi40MSwyMCwxMiwyMHoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNGOUE4MjUiPgogICAgPHBhdGggZD0iTTIwLjIgMTEuOGMtMS42IDAtMS43LjUtMS43IDEgMCAuNC4xLjkuMSAxLjMuMS41LjEuOS4xIDEuMyAwIDEuNy0xLjQgMi4zLTMuNSAyLjNoLS45di0xLjloLjVjMS4xIDAgMS40IDAgMS40LS44IDAtLjMgMC0uNi0uMS0xIDAtLjQtLjEtLjgtLjEtMS4yIDAtMS4zIDAtMS44IDEuMy0yLTEuMy0uMi0xLjMtLjctMS4zLTIgMC0uNC4xLS44LjEtMS4yLjEtLjQuMS0uNy4xLTEgMC0uOC0uNC0uNy0xLjQtLjhoLS41VjQuMWguOWMyLjIgMCAzLjUuNyAzLjUgMi4zIDAgLjQtLjEuOS0uMSAxLjMtLjEuNS0uMS45LS4xIDEuMyAwIC41LjIgMSAxLjcgMXYxLjh6TTEuOCAxMC4xYzEuNiAwIDEuNy0uNSAxLjctMSAwLS40LS4xLS45LS4xLTEuMy0uMS0uNS0uMS0uOS0uMS0xLjMgMC0xLjYgMS40LTIuMyAzLjUtMi4zaC45djEuOWgtLjVjLTEgMC0xLjQgMC0xLjQuOCAwIC4zIDAgLjYuMSAxIDAgLjIuMS42LjEgMSAwIDEuMyAwIDEuOC0xLjMgMkM2IDExLjIgNiAxMS43IDYgMTNjMCAuNC0uMS44LS4xIDEuMi0uMS4zLS4xLjctLjEgMSAwIC44LjMuOCAxLjQuOGguNXYxLjloLS45Yy0yLjEgMC0zLjUtLjYtMy41LTIuMyAwLS40LjEtLjkuMS0xLjMuMS0uNS4xLS45LjEtMS4zIDAtLjUtLjItMS0xLjctMXYtMS45eiIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSIxMy44IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY3g9IjExIiBjeT0iOC4yIiByPSIyLjEiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-julia: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDMyNSAzMDAiPgogIDxnIGNsYXNzPSJqcC1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjY2IzYzMzIj4KICAgIDxwYXRoIGQ9Ik0gMTUwLjg5ODQzOCAyMjUgQyAxNTAuODk4NDM4IDI2Ni40MjE4NzUgMTE3LjMyMDMxMiAzMDAgNzUuODk4NDM4IDMwMCBDIDM0LjQ3NjU2MiAzMDAgMC44OTg0MzggMjY2LjQyMTg3NSAwLjg5ODQzOCAyMjUgQyAwLjg5ODQzOCAxODMuNTc4MTI1IDM0LjQ3NjU2MiAxNTAgNzUuODk4NDM4IDE1MCBDIDExNy4zMjAzMTIgMTUwIDE1MC44OTg0MzggMTgzLjU3ODEyNSAxNTAuODk4NDM4IDIyNSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzM4OTgyNiI+CiAgICA8cGF0aCBkPSJNIDIzNy41IDc1IEMgMjM3LjUgMTE2LjQyMTg3NSAyMDMuOTIxODc1IDE1MCAxNjIuNSAxNTAgQyAxMjEuMDc4MTI1IDE1MCA4Ny41IDExNi40MjE4NzUgODcuNSA3NSBDIDg3LjUgMzMuNTc4MTI1IDEyMS4wNzgxMjUgMCAxNjIuNSAwIEMgMjAzLjkyMTg3NSAwIDIzNy41IDMzLjU3ODEyNSAyMzcuNSA3NSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzk1NThiMiI+CiAgICA8cGF0aCBkPSJNIDMyNC4xMDE1NjIgMjI1IEMgMzI0LjEwMTU2MiAyNjYuNDIxODc1IDI5MC41MjM0MzggMzAwIDI0OS4xMDE1NjIgMzAwIEMgMjA3LjY3OTY4OCAzMDAgMTc0LjEwMTU2MiAyNjYuNDIxODc1IDE3NC4xMDE1NjIgMjI1IEMgMTc0LjEwMTU2MiAxODMuNTc4MTI1IDIwNy42Nzk2ODggMTUwIDI0OS4xMDE1NjIgMTUwIEMgMjkwLjUyMzQzOCAxNTAgMzI0LjEwMTU2MiAxODMuNTc4MTI1IDMyNC4xMDE1NjIgMjI1Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgPGcgY2xhc3M9ImpwLWljb24td2FybjAiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4=);
  --jp-icon-listings-info: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MC45NzggNTAuOTc4IiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MC45NzggNTAuOTc4OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+Cgk8Zz4KCQk8cGF0aCBzdHlsZT0iZmlsbDojMDEwMDAyOyIgZD0iTTQzLjUyLDcuNDU4QzM4LjcxMSwyLjY0OCwzMi4zMDcsMCwyNS40ODksMEMxOC42NywwLDEyLjI2NiwyLjY0OCw3LjQ1OCw3LjQ1OAoJCQljLTkuOTQzLDkuOTQxLTkuOTQzLDI2LjExOSwwLDM2LjA2MmM0LjgwOSw0LjgwOSwxMS4yMTIsNy40NTYsMTguMDMxLDcuNDU4YzAsMCwwLjAwMSwwLDAuMDAyLDAKCQkJYzYuODE2LDAsMTMuMjIxLTIuNjQ4LDE4LjAyOS03LjQ1OGM0LjgwOS00LjgwOSw3LjQ1Ny0xMS4yMTIsNy40NTctMTguMDNDNTAuOTc3LDE4LjY3LDQ4LjMyOCwxMi4yNjYsNDMuNTIsNy40NTh6CgkJCSBNNDIuMTA2LDQyLjEwNWMtNC40MzIsNC40MzEtMTAuMzMyLDYuODcyLTE2LjYxNSw2Ljg3MmgtMC4wMDJjLTYuMjg1LTAuMDAxLTEyLjE4Ny0yLjQ0MS0xNi42MTctNi44NzIKCQkJYy05LjE2Mi05LjE2My05LjE2Mi0yNC4wNzEsMC0zMy4yMzNDMTMuMzAzLDQuNDQsMTkuMjA0LDIsMjUuNDg5LDJjNi4yODQsMCwxMi4xODYsMi40NCwxNi42MTcsNi44NzIKCQkJYzQuNDMxLDQuNDMxLDYuODcxLDEwLjMzMiw2Ljg3MSwxNi42MTdDNDguOTc3LDMxLjc3Miw0Ni41MzYsMzcuNjc1LDQyLjEwNiw0Mi4xMDV6Ii8+CgkJPHBhdGggc3R5bGU9ImZpbGw6IzAxMDAwMjsiIGQ9Ik0yMy41NzgsMzIuMjE4Yy0wLjAyMy0xLjczNCwwLjE0My0zLjA1OSwwLjQ5Ni0zLjk3MmMwLjM1My0wLjkxMywxLjExLTEuOTk3LDIuMjcyLTMuMjUzCgkJCWMwLjQ2OC0wLjUzNiwwLjkyMy0xLjA2MiwxLjM2Ny0xLjU3NWMwLjYyNi0wLjc1MywxLjEwNC0xLjQ3OCwxLjQzNi0yLjE3NWMwLjMzMS0wLjcwNywwLjQ5NS0xLjU0MSwwLjQ5NS0yLjUKCQkJYzAtMS4wOTYtMC4yNi0yLjA4OC0wLjc3OS0yLjk3OWMtMC41NjUtMC44NzktMS41MDEtMS4zMzYtMi44MDYtMS4zNjljLTEuODAyLDAuMDU3LTIuOTg1LDAuNjY3LTMuNTUsMS44MzIKCQkJYy0wLjMwMSwwLjUzNS0wLjUwMywxLjE0MS0wLjYwNywxLjgxNGMtMC4xMzksMC43MDctMC4yMDcsMS40MzItMC4yMDcsMi4xNzRoLTIuOTM3Yy0wLjA5MS0yLjIwOCwwLjQwNy00LjExNCwxLjQ5My01LjcxOQoJCQljMS4wNjItMS42NCwyLjg1NS0yLjQ4MSw1LjM3OC0yLjUyN2MyLjE2LDAuMDIzLDMuODc0LDAuNjA4LDUuMTQxLDEuNzU4YzEuMjc4LDEuMTYsMS45MjksMi43NjQsMS45NSw0LjgxMQoJCQljMCwxLjE0Mi0wLjEzNywyLjExMS0wLjQxLDIuOTExYy0wLjMwOSwwLjg0NS0wLjczMSwxLjU5My0xLjI2OCwyLjI0M2MtMC40OTIsMC42NS0xLjA2OCwxLjMxOC0xLjczLDIuMDAyCgkJCWMtMC42NSwwLjY5Ny0xLjMxMywxLjQ3OS0xLjk4NywyLjM0NmMtMC4yMzksMC4zNzctMC40MjksMC43NzctMC41NjUsMS4xOTljLTAuMTYsMC45NTktMC4yMTcsMS45NTEtMC4xNzEsMi45NzkKCQkJQzI2LjU4OSwzMi4yMTgsMjMuNTc4LDMyLjIxOCwyMy41NzgsMzIuMjE4eiBNMjMuNTc4LDM4LjIydi0zLjQ4NGgzLjA3NnYzLjQ4NEgyMy41Nzh6Ii8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-numbering: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTQgMTlINlYxOS41SDVWMjAuNUg2VjIxSDRWMjJIN1YxOEg0VjE5Wk01IDEwSDZWNkg0VjdINVYxMFpNNCAxM0g1LjhMNCAxNS4xVjE2SDdWMTVINS4yTDcgMTIuOVYxMkg0VjEzWk05IDdWOUgyM1Y3SDlaTTkgMjFIMjNWMTlIOVYyMVpNOSAxNUgyM1YxM0g5VjE1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-offline-bolt: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDIuMDJjLTUuNTEgMC05Ljk4IDQuNDctOS45OCA5Ljk4czQuNDcgOS45OCA5Ljk4IDkuOTggOS45OC00LjQ3IDkuOTgtOS45OFMxNy41MSAyLjAyIDEyIDIuMDJ6TTExLjQ4IDIwdi02LjI2SDhMMTMgNHY2LjI2aDMuMzVMMTEuNDggMjB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-pdf: url(data:image/svg+xml;base64,PHN2ZwogICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyMiAyMiIgd2lkdGg9IjE2Ij4KICAgIDxwYXRoIHRyYW5zZm9ybT0icm90YXRlKDQ1KSIgY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0ZGMkEyQSIKICAgICAgIGQ9Im0gMjIuMzQ0MzY5LC0zLjAxNjM2NDIgaCA1LjYzODYwNCB2IDEuNTc5MjQzMyBoIC0zLjU0OTIyNyB2IDEuNTA4NjkyOTkgaCAzLjMzNzU3NiBWIDEuNjUwODE1NCBoIC0zLjMzNzU3NiB2IDMuNDM1MjYxMyBoIC0yLjA4OTM3NyB6IG0gLTcuMTM2NDQ0LDEuNTc5MjQzMyB2IDQuOTQzOTU0MyBoIDAuNzQ4OTIgcSAxLjI4MDc2MSwwIDEuOTUzNzAzLC0wLjYzNDk1MzUgMC42NzgzNjksLTAuNjM0OTUzNSAwLjY3ODM2OSwtMS44NDUxNjQxIDAsLTEuMjA0NzgzNTUgLTAuNjcyOTQyLC0xLjgzNDMxMDExIC0wLjY3Mjk0MiwtMC42Mjk1MjY1OSAtMS45NTkxMywtMC42Mjk1MjY1OSB6IG0gLTIuMDg5Mzc3LC0xLjU3OTI0MzMgaCAyLjIwMzM0MyBxIDEuODQ1MTY0LDAgMi43NDYwMzksMC4yNjU5MjA3IDAuOTA2MzAxLDAuMjYwNDkzNyAxLjU1MjEwOCwwLjg5MDAyMDMgMC41Njk4MywwLjU0ODEyMjMgMC44NDY2MDUsMS4yNjQ0ODAwNiAwLjI3Njc3NCwwLjcxNjM1NzgxIDAuMjc2Nzc0LDEuNjIyNjU4OTQgMCwwLjkxNzE1NTEgLTAuMjc2Nzc0LDEuNjM4OTM5OSAtMC4yNzY3NzUsMC43MTYzNTc4IC0wLjg0NjYwNSwxLjI2NDQ4IC0wLjY1MTIzNCwwLjYyOTUyNjYgLTEuNTYyOTYyLDAuODk1NDQ3MyAtMC45MTE3MjgsMC4yNjA0OTM3IC0yLjczNTE4NSwwLjI2MDQ5MzcgaCAtMi4yMDMzNDMgeiBtIC04LjE0NTg1NjUsMCBoIDMuNDY3ODIzIHEgMS41NDY2ODE2LDAgMi4zNzE1Nzg1LDAuNjg5MjIzIDAuODMwMzI0LDAuNjgzNzk2MSAwLjgzMDMyNCwxLjk1MzcwMzE0IDAsMS4yNzUzMzM5NyAtMC44MzAzMjQsMS45NjQ1NTcwNiBRIDkuOTg3MTk2MSwyLjI3NDkxNSA4LjQ0MDUxNDUsMi4yNzQ5MTUgSCA3LjA2MjA2ODQgViA1LjA4NjA3NjcgSCA0Ljk3MjY5MTUgWiBtIDIuMDg5Mzc2OSwxLjUxNDExOTkgdiAyLjI2MzAzOTQzIGggMS4xNTU5NDEgcSAwLjYwNzgxODgsMCAwLjkzODg2MjksLTAuMjkzMDU1NDcgMC4zMzEwNDQxLC0wLjI5ODQ4MjQxIDAuMzMxMDQ0MSwtMC44NDExNzc3MiAwLC0wLjU0MjY5NTMxIC0wLjMzMTA0NDEsLTAuODM1NzUwNzQgLTAuMzMxMDQ0MSwtMC4yOTMwNTU1IC0wLjkzODg2MjksLTAuMjkzMDU1NSB6IgovPgo8L3N2Zz4K);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMEQ0N0ExIj4KICAgIDxwYXRoIGQ9Ik0xMS4xIDYuOVY1LjhINi45YzAtLjUgMC0xLjMuMi0xLjYuNC0uNy44LTEuMSAxLjctMS40IDEuNy0uMyAyLjUtLjMgMy45LS4xIDEgLjEgMS45LjkgMS45IDEuOXY0LjJjMCAuNS0uOSAxLjYtMiAxLjZIOC44Yy0xLjUgMC0yLjQgMS40LTIuNCAyLjh2Mi4ySDQuN0MzLjUgMTUuMSAzIDE0IDMgMTMuMVY5Yy0uMS0xIC42LTIgMS44LTIgMS41LS4xIDYuMy0uMSA2LjMtLjF6Ii8+CiAgICA8cGF0aCBkPSJNMTAuOSAxNS4xdjEuMWg0LjJjMCAuNSAwIDEuMy0uMiAxLjYtLjQuNy0uOCAxLjEtMS43IDEuNC0xLjcuMy0yLjUuMy0zLjkuMS0xLS4xLTEuOS0uOS0xLjktMS45di00LjJjMC0uNS45LTEuNiAyLTEuNmgzLjhjMS41IDAgMi40LTEuNCAyLjQtMi44VjYuNmgxLjdDMTguNSA2LjkgMTkgOCAxOSA4LjlWMTNjMCAxLS43IDIuMS0xLjkgMi4xaC02LjJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-redo: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE4LjQgMTAuNkMxNi41NSA4Ljk5IDE0LjE1IDggMTEuNSA4Yy00LjY1IDAtOC41OCAzLjAzLTkuOTYgNy4yMkwzLjkgMTZjMS4wNS0zLjE5IDQuMDUtNS41IDcuNi01LjUgMS45NSAwIDMuNzMuNzIgNS4xMiAxLjg4TDEzIDE2aDlWN2wtMy42IDMuNnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-table-rows: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMSw4SDNWNGgxOFY4eiBNMjEsMTBIM3Y0aDE4VjEweiBNMjEsMTZIM3Y0aDE4VjE2eiIvPgogICAgPC9nPgo8L3N2Zz4=);
  --jp-icon-tag: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjgiIGhlaWdodD0iMjgiIHZpZXdCb3g9IjAgMCA0MyAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTI4LjgzMzIgMTIuMzM0TDMyLjk5OTggMTYuNTAwN0wzNy4xNjY1IDEyLjMzNEgyOC44MzMyWiIvPgoJCTxwYXRoIGQ9Ik0xNi4yMDk1IDIxLjYxMDRDMTUuNjg3MyAyMi4xMjk5IDE0Ljg0NDMgMjIuMTI5OSAxNC4zMjQ4IDIxLjYxMDRMNi45ODI5IDE0LjcyNDVDNi41NzI0IDE0LjMzOTQgNi4wODMxMyAxMy42MDk4IDYuMDQ3ODYgMTMuMDQ4MkM1Ljk1MzQ3IDExLjUyODggNi4wMjAwMiA4LjYxOTQ0IDYuMDY2MjEgNy4wNzY5NUM2LjA4MjgxIDYuNTE0NzcgNi41NTU0OCA2LjA0MzQ3IDcuMTE4MDQgNi4wMzA1NUM5LjA4ODYzIDUuOTg0NzMgMTMuMjYzOCA1LjkzNTc5IDEzLjY1MTggNi4zMjQyNUwyMS43MzY5IDEzLjYzOUMyMi4yNTYgMTQuMTU4NSAyMS43ODUxIDE1LjQ3MjQgMjEuMjYyIDE1Ljk5NDZMMTYuMjA5NSAyMS42MTA0Wk05Ljc3NTg1IDguMjY1QzkuMzM1NTEgNy44MjU2NiA4LjYyMzUxIDcuODI1NjYgOC4xODI4IDguMjY1QzcuNzQzNDYgOC43MDU3MSA3Ljc0MzQ2IDkuNDE3MzMgOC4xODI4IDkuODU2NjdDOC42MjM4MiAxMC4yOTY0IDkuMzM1ODIgMTAuMjk2NCA5Ljc3NTg1IDkuODU2NjdDMTAuMjE1NiA5LjQxNzMzIDEwLjIxNTYgOC43MDUzMyA5Ljc3NTg1IDguMjY1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMikiIGZpbGw9IiMzMzMzMzMiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uLWFjY2VudDIganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGQ9Ik01LjA1NjY0IDguNzYxNzJDNS4wNTY2NCA4LjU5NzY2IDUuMDMxMjUgOC40NTMxMiA0Ljk4MDQ3IDguMzI4MTJDNC45MzM1OSA4LjE5OTIyIDQuODU1NDcgOC4wODIwMyA0Ljc0NjA5IDcuOTc2NTZDNC42NDA2MiA3Ljg3MTA5IDQuNSA3Ljc3NTM5IDQuMzI0MjIgNy42ODk0NUM0LjE1MjM0IDcuNTk5NjEgMy45NDMzNiA3LjUxMTcyIDMuNjk3MjcgNy40MjU3OEMzLjMwMjczIDcuMjg1MTYgMi45NDMzNiA3LjEzNjcyIDIuNjE5MTQgNi45ODA0N0MyLjI5NDkyIDYuODI0MjIgMi4wMTc1OCA2LjY0MjU4IDEuNzg3MTEgNi40MzU1NUMxLjU2MDU1IDYuMjI4NTIgMS4zODQ3NyA1Ljk4ODI4IDEuMjU5NzcgNS43MTQ4NEMxLjEzNDc3IDUuNDM3NSAxLjA3MjI3IDUuMTA5MzggMS4wNzIyNyA0LjczMDQ3QzEuMDcyMjcgNC4zOTg0NCAxLjEyODkxIDQuMDk1NyAxLjI0MjE5IDMuODIyMjdDMS4zNTU0NyAzLjU0NDkyIDEuNTE1NjIgMy4zMDQ2OSAxLjcyMjY2IDMuMTAxNTZDMS45Mjk2OSAyLjg5ODQ0IDIuMTc5NjkgMi43MzQzNyAyLjQ3MjY2IDIuNjA5MzhDMi43NjU2MiAyLjQ4NDM4IDMuMDkxOCAyLjQwNDMgMy40NTExNyAyLjM2OTE0VjEuMTA5MzhINC4zODg2N1YyLjM4MDg2QzQuNzQwMjMgMi40Mjc3MyA1LjA1NjY0IDIuNTIzNDQgNS4zMzc4OSAyLjY2Nzk3QzUuNjE5MTQgMi44MTI1IDUuODU3NDIgMy4wMDE5NSA2LjA1MjczIDMuMjM2MzNDNi4yNTE5NSAzLjQ2NjggNi40MDQzIDMuNzQwMjMgNi41MDk3NyA0LjA1NjY0QzYuNjE5MTQgNC4zNjkxNCA2LjY3MzgzIDQuNzIwNyA2LjY3MzgzIDUuMTExMzNINS4wNDQ5MkM1LjA0NDkyIDQuNjM4NjcgNC45Mzc1IDQuMjgxMjUgNC43MjI2NiA0LjAzOTA2QzQuNTA3ODEgMy43OTI5NyA0LjIxNjggMy42Njk5MiAzLjg0OTYxIDMuNjY5OTJDMy42NTAzOSAzLjY2OTkyIDMuNDc2NTYgMy42OTcyNyAzLjMyODEyIDMuNzUxOTVDMy4xODM1OSAzLjgwMjczIDMuMDY0NDUgMy44NzY5NSAyLjk3MDcgMy45NzQ2MUMyLjg3Njk1IDQuMDY4MzYgMi44MDY2NCA0LjE3OTY5IDIuNzU5NzcgNC4zMDg1OUMyLjcxNjggNC40Mzc1IDIuNjk1MzEgNC41NzgxMiAyLjY5NTMxIDQuNzMwNDdDMi42OTUzMSA0Ljg4MjgxIDIuNzE2OCA1LjAxOTUzIDIuNzU5NzcgNS4xNDA2MkMyLjgwNjY0IDUuMjU3ODEgMi44ODI4MSA1LjM2NzE5IDIuOTg4MjggNS40Njg3NUMzLjA5NzY2IDUuNTcwMzEgMy4yNDAyMyA1LjY2Nzk3IDMuNDE2MDIgNS43NjE3MkMzLjU5MTggNS44NTE1NiAzLjgxMDU1IDUuOTQzMzYgNC4wNzIyNyA2LjAzNzExQzQuNDY2OCA2LjE4NTU1IDQuODI0MjIgNi4zMzk4NCA1LjE0NDUzIDYuNUM1LjQ2NDg0IDYuNjU2MjUgNS43MzgyOCA2LjgzOTg0IDUuOTY0ODQgNy4wNTA3OEM2LjE5NTMxIDcuMjU3ODEgNi4zNzEwOSA3LjUgNi40OTIxOSA3Ljc3NzM0QzYuNjE3MTkgOC4wNTA3OCA2LjY3OTY5IDguMzc1IDYuNjc5NjkgOC43NUM2LjY3OTY5IDkuMDkzNzUgNi42MjMwNSA5LjQwNDMgNi41MDk3NyA5LjY4MTY0QzYuMzk2NDggOS45NTUwOCA2LjIzNDM4IDEwLjE5MTQgNi4wMjM0NCAxMC4zOTA2QzUuODEyNSAxMC41ODk4IDUuNTU4NTkgMTAuNzUgNS4yNjE3MiAxMC44NzExQzQuOTY0ODQgMTAuOTg4MyA0LjYzMjgxIDExLjA2NDUgNC4yNjU2MiAxMS4wOTk2VjEyLjI0OEgzLjMzMzk4VjExLjA5OTZDMy4wMDE5NSAxMS4wNjg0IDIuNjc5NjkgMTAuOTk2MSAyLjM2NzE5IDEwLjg4MjhDMi4wNTQ2OSAxMC43NjU2IDEuNzc3MzQgMTAuNTk3NyAxLjUzNTE2IDEwLjM3ODlDMS4yOTY4OCAxMC4xNjAyIDEuMTA1NDcgOS44ODQ3NyAwLjk2MDkzOCA5LjU1MjczQzAuODE2NDA2IDkuMjE2OCAwLjc0NDE0MSA4LjgxNDQ1IDAuNzQ0MTQxIDguMzQ1N0gyLjM3ODkxQzIuMzc4OTEgOC42MjY5NSAyLjQxOTkyIDguODYzMjggMi41MDE5NSA5LjA1NDY5QzIuNTgzOTggOS4yNDIxOSAyLjY4OTQ1IDkuMzkyNTggMi44MTgzNiA5LjUwNTg2QzIuOTUxMTcgOS42MTUyMyAzLjEwMTU2IDkuNjkzMzYgMy4yNjk1MyA5Ljc0MDIzQzMuNDM3NSA5Ljc4NzExIDMuNjA5MzggOS44MTA1NSAzLjc4NTE2IDkuODEwNTVDNC4yMDMxMiA5LjgxMDU1IDQuNTE5NTMgOS43MTI4OSA0LjczNDM4IDkuNTE3NThDNC45NDkyMiA5LjMyMjI3IDUuMDU2NjQgOS4wNzAzMSA1LjA1NjY0IDguNzYxNzJaTTEzLjQxOCAxMi4yNzE1SDguMDc0MjJWMTFIMTMuNDE4VjEyLjI3MTVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzLjk1MjY0IDYpIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTUgMTVIM3YyaDEydi0yem0wLThIM3YyaDEyVjd6TTMgMTNoMTh2LTJIM3Yyem0wIDhoMTh2LTJIM3Yyek0zIDN2MmgxOFYzSDN6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-toc: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik03LDVIMjFWN0g3VjVNNywxM1YxMUgyMVYxM0g3TTQsNC41QTEuNSwxLjUgMCAwLDEgNS41LDZBMS41LDEuNSAwIDAsMSA0LDcuNUExLjUsMS41IDAgMCwxIDIuNSw2QTEuNSwxLjUgMCAwLDEgNCw0LjVNNCwxMC41QTEuNSwxLjUgMCAwLDEgNS41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMy41QTEuNSwxLjUgMCAwLDEgMi41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMC41TTcsMTlWMTdIMjFWMTlIN000LDE2LjVBMS41LDEuNSAwIDAsMSA1LjUsMThBMS41LDEuNSAwIDAsMSA0LDE5LjVBMS41LDEuNSAwIDAsMSAyLjUsMThBMS41LDEuNSAwIDAsMSA0LDE2LjVaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tree-view: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMiAxMVYzaC03djNIOVYzSDJ2OGg3VjhoMnYxMGg0djNoN3YtOGgtN3YzaC0yVjhoMnYzeiIvPgogICAgPC9nPgo8L3N2Zz4=);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}
.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}
.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}
.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}
.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}
.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}
.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}
.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}
.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}
.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}
.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}
.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}
.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}
.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}
.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}
.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}
.jp-CodeIcon {
  background-image: var(--jp-icon-code);
}
.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}
.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}
.jp-CopyrightIcon {
  background-image: var(--jp-icon-copyright);
}
.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}
.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}
.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}
.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}
.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}
.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}
.jp-FileIcon {
  background-image: var(--jp-icon-file);
}
.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}
.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}
.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}
.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}
.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}
.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}
.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}
.jp-JuliaIcon {
  background-image: var(--jp-icon-julia);
}
.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}
.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}
.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}
.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}
.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}
.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}
.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}
.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}
.jp-ListIcon {
  background-image: var(--jp-icon-list);
}
.jp-ListingsInfoIcon {
  background-image: var(--jp-icon-listings-info);
}
.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}
.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}
.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}
.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}
.jp-NumberingIcon {
  background-image: var(--jp-icon-numbering);
}
.jp-OfflineBoltIcon {
  background-image: var(--jp-icon-offline-bolt);
}
.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}
.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}
.jp-PdfIcon {
  background-image: var(--jp-icon-pdf);
}
.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}
.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}
.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}
.jp-RedoIcon {
  background-image: var(--jp-icon-redo);
}
.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}
.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}
.jp-RunIcon {
  background-image: var(--jp-icon-run);
}
.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}
.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}
.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}
.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}
.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}
.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}
.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}
.jp-TableRowsIcon {
  background-image: var(--jp-icon-table-rows);
}
.jp-TagIcon {
  background-image: var(--jp-icon-tag);
}
.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}
.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}
.jp-TocIcon {
  background-image: var(--jp-icon-toc);
}
.jp-TreeViewIcon {
  background-image: var(--jp-icon-tree-view);
}
.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}
.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}
.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}
.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}
/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}
/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}
/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}
.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}
.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}
.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}
.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}
.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}
.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}
.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}
.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}
/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}
.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}
.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}
.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}
.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}
.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}
.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}
/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

/* CSS for icons in selected items in the settings editor */
#setting-editor .jp-PluginList .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
#setting-editor
  .jp-PluginList
  .jp-mod-selected
  .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected tabs in the sidebar tab manager */
#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable[fill] {
  fill: #fff;
}

#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable[fill] {
  fill: var(--jp-brand-color1);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable-inverse[fill] {
  fill: #fff;
}

/**
 * TODO: come up with non css-hack solution for showing the busy icon on top
 *  of the close icon
 * CSS for complex behavior of close icon of tabs in the sidebar tab manager
 */
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-dirty.jp-mod-active
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: #fff;
}

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) svg {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-switch {
  display: flex;
  align-items: center;
  padding-left: 4px;
  padding-right: 4px;
  font-size: var(--jp-ui-font-size1);
  background-color: transparent;
  color: var(--jp-ui-font-color1);
  border: none;
  height: 20px;
}

.jp-switch:hover {
  background-color: var(--jp-layout-color2);
}

.jp-switch-label {
  margin-right: 5px;
}

.jp-switch-track {
  cursor: pointer;
  background-color: var(--jp-border-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 34px;
  height: 16px;
  width: 35px;
  position: relative;
}

.jp-switch-track::before {
  content: '';
  position: absolute;
  height: 10px;
  width: 10px;
  margin: 3px;
  left: 0px;
  background-color: var(--jp-ui-inverse-font-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 50%;
}

.jp-switch[aria-checked='true'] .jp-switch-track {
  background-color: var(--jp-warn-color0);
}

.jp-switch[aria-checked='true'] .jp-switch-track::before {
  /* track width (35) - margins (3 + 3) - thumb width (10) */
  left: 19px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

/* Override Blueprint's _reset.scss styles */
html {
  box-sizing: unset;
}

*,
*::before,
*::after {
  box-sizing: unset;
}

body {
  color: unset;
  font-family: var(--jp-ui-font-family);
}

p {
  margin-top: unset;
  margin-bottom: unset;
}

small {
  font-size: unset;
}

strong {
  font-weight: unset;
}

/* Override Blueprint's _typography.scss styles */
a {
  text-decoration: unset;
  color: unset;
}
a:hover {
  text-decoration: unset;
  color: unset;
}

/* Override Blueprint's _accessibility.scss styles */
:focus {
  outline: unset;
  outline-offset: unset;
  -moz-outline-radius: unset;
}

/* Styles for ui-components */
.jp-Button {
  border-radius: var(--jp-border-radius);
  padding: 0px 12px;
  font-size: var(--jp-ui-font-size1);
}

/* Use our own theme for hover styles */
button.jp-Button.bp3-button.bp3-minimal:hover {
  background-color: var(--jp-layout-color2);
}
.jp-Button.minimal {
  color: unset !important;
}

.jp-Button.jp-ToolbarButtonComponent {
  text-transform: none;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color3);
}

.jp-BPIcon {
  display: inline-block;
  vertical-align: middle;
  margin: auto;
}

/* Stop blueprint futzing with our icon fills */
.bp3-icon.jp-BPIcon > svg:not([fill]) {
  fill: var(--jp-inverse-layout-color3);
}

.jp-InputGroupAction {
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

/* Use our own theme for hover and option styles */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}
select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-top: 1px solid var(--jp-border-color2);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-Collapse-header {
  padding: 1px 12px;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size2);
}

.jp-Collapse-header:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Collapse-contents {
  padding: 0px 12px 0px 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0px;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Modal variant
|----------------------------------------------------------------------------*/

.jp-ModalCommandPalette {
  position: absolute;
  z-index: 10000;
  top: 38px;
  left: 30%;
  margin: 0;
  padding: 4px;
  width: 40%;
  box-shadow: var(--jp-elevation-z4);
  border-radius: 4px;
  background: var(--jp-layout-color0);
}

.jp-ModalCommandPalette .lm-CommandPalette {
  max-height: 40vh;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-close-icon::after {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-header {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-item {
  margin-left: 4px;
  margin-right: 4px;
}

.jp-ModalCommandPalette
  .lm-CommandPalette
  .lm-CommandPalette-item.lm-mod-disabled {
  display: none;
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0px 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-SearchIconGroup {
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  padding: 5px 5px 1px 5px;
}

.jp-SearchIconGroup svg {
  height: 20px;
  width: 20px;
}

.jp-SearchIconGroup .jp-icon3[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color2);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0px;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item.lm-mod-active {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active .jp-icon-selectable[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.6;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty:after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0px 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0px;
  left: 0px;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px;
  padding-bottom: 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
  resize: both;
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0px;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

button.jp-Dialog-close-button {
  padding: 0;
  height: 100%;
  min-width: unset;
  min-height: unset;
}

.jp-Dialog-header {
  display: flex;
  justify-content: space-between;
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0px 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

.jp-HoverBox.jp-mod-outofview {
  display: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

.jp-Input-Boolean-Dialog {
  flex-direction: row-reverse;
  align-items: end;
  width: 100%;
}

.jp-Input-Boolean-Dialog > label {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;

  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;

  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #aa00ff;

  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;

  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;

  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;

  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;

  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;

  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;

  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;

  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;

  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;

  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ffff00;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;

  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;

  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;

  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;

  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;

  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eeeeee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;

  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent:before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent:after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0px 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input[type='checkbox'].jp-mod-styled {
  appearance: checkbox;
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  height: auto;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-FileDialog-Checkbox {
  margin-top: 35px;
  display: flex;
  flex-direction: row;
  align-items: end;
  width: 100%;
}

.jp-FileDialog-Checkbox > label {
  flex: 1 1 auto;
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  height: 28px;
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  background-color: var(--jp-layout-color1);
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0px 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  height: 32px;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 1;
  overflow-x: auto;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px;
  margin: 0px;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px 6px;
  margin: 0px;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent span {
  padding: 0px;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar.jp-Toolbar-micro {
  padding: 0;
  min-height: 0;
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar {
  border: none;
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ body.p-mod-override-cursor *, /* </DEPRECATED> */
body.lm-mod-override-cursor * {
  cursor: inherit !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/* BASICS */

.CodeMirror {
  /* Set height, width, borders, and global font properties here */
  font-family: monospace;
  height: 300px;
  color: black;
  direction: ltr;
}

/* PADDING */

.CodeMirror-lines {
  padding: 4px 0; /* Vertical padding around content */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  padding: 0 4px; /* Horizontal padding of content */
}

.CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  background-color: white; /* The little square between H and V scrollbars */
}

/* GUTTER */

.CodeMirror-gutters {
  border-right: 1px solid #ddd;
  background-color: #f7f7f7;
  white-space: nowrap;
}
.CodeMirror-linenumbers {}
.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: #999;
  white-space: nowrap;
}

.CodeMirror-guttermarker { color: black; }
.CodeMirror-guttermarker-subtle { color: #999; }

/* CURSOR */

.CodeMirror-cursor {
  border-left: 1px solid black;
  border-right: none;
  width: 0;
}
/* Shown when moving in bi-directional text */
.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver;
}
.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: #7e7;
}
.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1;
}
.cm-fat-cursor-mark {
  background-color: rgba(20, 255, 20, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
}
.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: #7e7;
}
@-moz-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@-webkit-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}

/* Can style cursor different in overwrite (non-insert) mode */
.CodeMirror-overwrite .CodeMirror-cursor {}

.cm-tab { display: inline-block; text-decoration: inherit; }

.CodeMirror-rulers {
  position: absolute;
  left: 0; right: 0; top: -50px; bottom: 0;
  overflow: hidden;
}
.CodeMirror-ruler {
  border-left: 1px solid #ccc;
  top: 0; bottom: 0;
  position: absolute;
}

/* DEFAULT THEME */

.cm-s-default .cm-header {color: blue;}
.cm-s-default .cm-quote {color: #090;}
.cm-negative {color: #d44;}
.cm-positive {color: #292;}
.cm-header, .cm-strong {font-weight: bold;}
.cm-em {font-style: italic;}
.cm-link {text-decoration: underline;}
.cm-strikethrough {text-decoration: line-through;}

.cm-s-default .cm-keyword {color: #708;}
.cm-s-default .cm-atom {color: #219;}
.cm-s-default .cm-number {color: #164;}
.cm-s-default .cm-def {color: #00f;}
.cm-s-default .cm-variable,
.cm-s-default .cm-punctuation,
.cm-s-default .cm-property,
.cm-s-default .cm-operator {}
.cm-s-default .cm-variable-2 {color: #05a;}
.cm-s-default .cm-variable-3, .cm-s-default .cm-type {color: #085;}
.cm-s-default .cm-comment {color: #a50;}
.cm-s-default .cm-string {color: #a11;}
.cm-s-default .cm-string-2 {color: #f50;}
.cm-s-default .cm-meta {color: #555;}
.cm-s-default .cm-qualifier {color: #555;}
.cm-s-default .cm-builtin {color: #30a;}
.cm-s-default .cm-bracket {color: #997;}
.cm-s-default .cm-tag {color: #170;}
.cm-s-default .cm-attribute {color: #00c;}
.cm-s-default .cm-hr {color: #999;}
.cm-s-default .cm-link {color: #00c;}

.cm-s-default .cm-error {color: #f00;}
.cm-invalidchar {color: #f00;}

.CodeMirror-composing { border-bottom: 2px solid; }

/* Default styles for common addons */

div.CodeMirror span.CodeMirror-matchingbracket {color: #0b0;}
div.CodeMirror span.CodeMirror-nonmatchingbracket {color: #a22;}
.CodeMirror-matchingtag { background: rgba(255, 150, 0, .3); }
.CodeMirror-activeline-background {background: #e8f2ff;}

/* STOP */

/* The rest of this file contains styles related to the mechanics of
   the editor. You probably shouldn't touch them. */

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white;
}

.CodeMirror-scroll {
  overflow: scroll !important; /* Things will break if this is overridden */
  /* 50px is the magic margin used to hide the element's real scrollbars */
  /* See overflow: hidden in .CodeMirror */
  margin-bottom: -50px; margin-right: -50px;
  padding-bottom: 50px;
  height: 100%;
  outline: none; /* Prevent dragging from highlighting the element */
  position: relative;
}
.CodeMirror-sizer {
  position: relative;
  border-right: 50px solid transparent;
}

/* The fake, visible scrollbars. Used to force redraw during scrolling
   before actual scrolling happens, thus preventing shaking and
   flickering artifacts. */
.CodeMirror-vscrollbar, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
  outline: none;
}
.CodeMirror-vscrollbar {
  right: 0; top: 0;
  overflow-x: hidden;
  overflow-y: scroll;
}
.CodeMirror-hscrollbar {
  bottom: 0; left: 0;
  overflow-y: hidden;
  overflow-x: scroll;
}
.CodeMirror-scrollbar-filler {
  right: 0; bottom: 0;
}
.CodeMirror-gutter-filler {
  left: 0; bottom: 0;
}

.CodeMirror-gutters {
  position: absolute; left: 0; top: 0;
  min-height: 100%;
  z-index: 3;
}
.CodeMirror-gutter {
  white-space: normal;
  height: 100%;
  display: inline-block;
  vertical-align: top;
  margin-bottom: -50px;
}
.CodeMirror-gutter-wrapper {
  position: absolute;
  z-index: 4;
  background: none !important;
  border: none !important;
}
.CodeMirror-gutter-background {
  position: absolute;
  top: 0; bottom: 0;
  z-index: 4;
}
.CodeMirror-gutter-elt {
  position: absolute;
  cursor: default;
  z-index: 4;
}
.CodeMirror-gutter-wrapper ::selection { background-color: transparent }
.CodeMirror-gutter-wrapper ::-moz-selection { background-color: transparent }

.CodeMirror-lines {
  cursor: text;
  min-height: 1px; /* prevents collapsing before first draw */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  /* Reset some styles that the rest of the page might have set */
  -moz-border-radius: 0; -webkit-border-radius: 0; border-radius: 0;
  border-width: 0;
  background: transparent;
  font-family: inherit;
  font-size: inherit;
  margin: 0;
  white-space: pre;
  word-wrap: normal;
  line-height: inherit;
  color: inherit;
  z-index: 2;
  position: relative;
  overflow: visible;
  -webkit-tap-highlight-color: transparent;
  -webkit-font-variant-ligatures: contextual;
  font-variant-ligatures: contextual;
}
.CodeMirror-wrap pre.CodeMirror-line,
.CodeMirror-wrap pre.CodeMirror-line-like {
  word-wrap: break-word;
  white-space: pre-wrap;
  word-break: normal;
}

.CodeMirror-linebackground {
  position: absolute;
  left: 0; right: 0; top: 0; bottom: 0;
  z-index: 0;
}

.CodeMirror-linewidget {
  position: relative;
  z-index: 2;
  padding: 0.1px; /* Force widget margins to stay inside of the container */
}

.CodeMirror-widget {}

.CodeMirror-rtl pre { direction: rtl; }

.CodeMirror-code {
  outline: none;
}

/* Force content-box sizing for the elements where we expect it */
.CodeMirror-scroll,
.CodeMirror-sizer,
.CodeMirror-gutter,
.CodeMirror-gutters,
.CodeMirror-linenumber {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.CodeMirror-measure {
  position: absolute;
  width: 100%;
  height: 0;
  overflow: hidden;
  visibility: hidden;
}

.CodeMirror-cursor {
  position: absolute;
  pointer-events: none;
}
.CodeMirror-measure pre { position: static; }

div.CodeMirror-cursors {
  visibility: hidden;
  position: relative;
  z-index: 3;
}
div.CodeMirror-dragcursors {
  visibility: visible;
}

.CodeMirror-focused div.CodeMirror-cursors {
  visibility: visible;
}

.CodeMirror-selected { background: #d9d9d9; }
.CodeMirror-focused .CodeMirror-selected { background: #d7d4f0; }
.CodeMirror-crosshair { cursor: crosshair; }
.CodeMirror-line::selection, .CodeMirror-line > span::selection, .CodeMirror-line > span > span::selection { background: #d7d4f0; }
.CodeMirror-line::-moz-selection, .CodeMirror-line > span::-moz-selection, .CodeMirror-line > span > span::-moz-selection { background: #d7d4f0; }

.cm-searching {
  background-color: #ffa;
  background-color: rgba(255, 255, 0, .4);
}

/* Used to force a border model for a node */
.cm-force-border { padding-right: .1px; }

@media print {
  /* Hide the cursor when printing */
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

/* See issue #2901 */
.cm-tab-wrap-hack:after { content: ''; }

/* Help users use markselection to safely style text background */
span.CodeMirror-selectedtext { background: none; }

.CodeMirror-dialog {
  position: absolute;
  left: 0; right: 0;
  background: inherit;
  z-index: 15;
  padding: .1em .8em;
  overflow: hidden;
  color: inherit;
}

.CodeMirror-dialog-top {
  border-bottom: 1px solid #eee;
  top: 0;
}

.CodeMirror-dialog-bottom {
  border-top: 1px solid #eee;
  bottom: 0;
}

.CodeMirror-dialog input {
  border: none;
  outline: none;
  background: transparent;
  width: 20em;
  color: inherit;
  font-family: monospace;
}

.CodeMirror-dialog button {
  font-size: 70%;
}

.CodeMirror-foldmarker {
  color: blue;
  text-shadow: #b9f 1px 1px 2px, #b9f -1px -1px 2px, #b9f 1px -1px 2px, #b9f -1px 1px 2px;
  font-family: arial;
  line-height: .3;
  cursor: pointer;
}
.CodeMirror-foldgutter {
  width: .7em;
}
.CodeMirror-foldgutter-open,
.CodeMirror-foldgutter-folded {
  cursor: pointer;
}
.CodeMirror-foldgutter-open:after {
  content: "\25BE";
}
.CodeMirror-foldgutter-folded:after {
  content: "\25B8";
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.CodeMirror {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;
  /* Changed to auto to autogrow */
}

.CodeMirror pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* This causes https://github.com/jupyter/jupyterlab/issues/522 */
/* May not cause it not because we changed it! */
.CodeMirror-lines {
  padding: var(--jp-code-padding) 0;
}

.CodeMirror-linenumber {
  padding: 0 8px;
}

.jp-CodeMirrorEditor {
  cursor: text;
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.CodeMirror.jp-mod-readOnly .CodeMirror-cursor {
  display: none;
}

.CodeMirror-gutters {
  border-right: 1px solid var(--jp-border-color2);
  background-color: var(--jp-layout-color0);
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.CodeMirror-selectedtext.cm-searching {
  background-color: var(--jp-search-selected-match-background-color) !important;
  color: var(--jp-search-selected-match-color) !important;
}

.cm-searching {
  background-color: var(
    --jp-search-unselected-match-background-color
  ) !important;
  color: var(--jp-search-unselected-match-color) !important;
}

.CodeMirror-focused .CodeMirror-selected {
  background-color: var(--jp-editor-selected-focused-background);
}

.CodeMirror-selected {
  background-color: var(--jp-editor-selected-background);
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/**
 * Here is our jupyter theme for CodeMirror syntax highlighting
 * This is used in our marked.js syntax highlighting and CodeMirror itself
 * The string "jupyter" is set in ../codemirror/widget.DEFAULT_CODEMIRROR_THEME
 * This came from the classic notebook, which came form highlight.js/GitHub
 */

/**
 * CodeMirror themes are handling the background/color in this way. This works
 * fine for CodeMirror editors outside the notebook, but the notebook styles
 * these things differently.
 */
.CodeMirror.cm-s-jupyter {
  background: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* In the notebook, we want this styling to be handled by its container */
.jp-CodeConsole .CodeMirror.cm-s-jupyter,
.jp-Notebook .CodeMirror.cm-s-jupyter {
  background: transparent;
}

.cm-s-jupyter .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}
.cm-s-jupyter span.cm-keyword {
  color: var(--jp-mirror-editor-keyword-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-atom {
  color: var(--jp-mirror-editor-atom-color);
}
.cm-s-jupyter span.cm-number {
  color: var(--jp-mirror-editor-number-color);
}
.cm-s-jupyter span.cm-def {
  color: var(--jp-mirror-editor-def-color);
}
.cm-s-jupyter span.cm-variable {
  color: var(--jp-mirror-editor-variable-color);
}
.cm-s-jupyter span.cm-variable-2 {
  color: var(--jp-mirror-editor-variable-2-color);
}
.cm-s-jupyter span.cm-variable-3 {
  color: var(--jp-mirror-editor-variable-3-color);
}
.cm-s-jupyter span.cm-punctuation {
  color: var(--jp-mirror-editor-punctuation-color);
}
.cm-s-jupyter span.cm-property {
  color: var(--jp-mirror-editor-property-color);
}
.cm-s-jupyter span.cm-operator {
  color: var(--jp-mirror-editor-operator-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-comment {
  color: var(--jp-mirror-editor-comment-color);
  font-style: italic;
}
.cm-s-jupyter span.cm-string {
  color: var(--jp-mirror-editor-string-color);
}
.cm-s-jupyter span.cm-string-2 {
  color: var(--jp-mirror-editor-string-2-color);
}
.cm-s-jupyter span.cm-meta {
  color: var(--jp-mirror-editor-meta-color);
}
.cm-s-jupyter span.cm-qualifier {
  color: var(--jp-mirror-editor-qualifier-color);
}
.cm-s-jupyter span.cm-builtin {
  color: var(--jp-mirror-editor-builtin-color);
}
.cm-s-jupyter span.cm-bracket {
  color: var(--jp-mirror-editor-bracket-color);
}
.cm-s-jupyter span.cm-tag {
  color: var(--jp-mirror-editor-tag-color);
}
.cm-s-jupyter span.cm-attribute {
  color: var(--jp-mirror-editor-attribute-color);
}
.cm-s-jupyter span.cm-header {
  color: var(--jp-mirror-editor-header-color);
}
.cm-s-jupyter span.cm-quote {
  color: var(--jp-mirror-editor-quote-color);
}
.cm-s-jupyter span.cm-link {
  color: var(--jp-mirror-editor-link-color);
}
.cm-s-jupyter span.cm-error {
  color: var(--jp-mirror-editor-error-color);
}
.cm-s-jupyter span.cm-hr {
  color: #999;
}

.cm-s-jupyter span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}

.cm-s-jupyter .CodeMirror-activeline-background,
.cm-s-jupyter .CodeMirror-gutter {
  background-color: var(--jp-layout-color2);
}

/* Styles for shared cursors (remote cursor locations and selected ranges) */
.jp-CodeMirrorEditor .remote-caret {
  position: relative;
  border-left: 2px solid black;
  margin-left: -1px;
  margin-right: -1px;
  box-sizing: border-box;
}

.jp-CodeMirrorEditor .remote-caret > div {
  white-space: nowrap;
  position: absolute;
  top: -1.15em;
  padding-bottom: 0.05em;
  left: -2px;
  font-size: 0.95em;
  background-color: rgb(250, 129, 0);
  font-family: var(--jp-ui-font-family);
  font-weight: bold;
  line-height: normal;
  user-select: none;
  color: white;
  padding-left: 2px;
  padding-right: 2px;
  z-index: 3;
  transition: opacity 0.3s ease-in-out;
}

.jp-CodeMirrorEditor .remote-caret.hide-name > div {
  transition-delay: 0.7s;
  opacity: 0;
}

.jp-CodeMirrorEditor .remote-caret:hover > div {
  opacity: 1;
  transition-delay: 0s;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

:root {
  /* This is the padding value to fill the gaps between lines containing spans with background color. */
  --jp-private-code-span-padding: calc(
    (var(--jp-code-line-height) - 1) * var(--jp-code-font-size) / 2
  );
}

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0px;
  padding: 0px;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}
.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}
.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}
.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}
.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}
.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}
.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}
.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}
.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}
.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}
.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}
.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}
.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}
.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}
.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}
.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}
.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0em;
}

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: 12px;
  table-layout: fixed;
  margin-left: auto;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon table {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0px;
}

.jp-RenderedHTMLCommon p {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}
/* ...or leave it untouched if they don't */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-dark-background {
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-light-background {
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}
.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}
.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}
.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}
.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}
.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}
.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}
.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}
.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: 0.8em;
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser {
  display: flex;
  flex-direction: column;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  border-bottom: none;
  height: auto;
  margin: var(--jp-toolbar-header-margin);
  box-shadow: none;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 8px 12px 8px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0px 2px;
  padding: 0px 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0px;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar.jp-Toolbar {
  padding: 0px;
  margin: 8px 12px 0px 12px;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  justify-content: flex-start;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-Toolbar-item {
  flex: 0 0 auto;
  padding-left: 0px;
  padding-right: 2px;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-ToolbarButtonComponent {
  width: 40px;
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent {
  width: 72px;
  background: var(--jp-brand-color1);
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent:focus-visible {
  background-color: var(--jp-brand-color0);
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent
  .jp-icon3 {
  fill: white;
}

/*-----------------------------------------------------------------------------
| Other styles
|----------------------------------------------------------------------------*/

.jp-FileDialog.jp-mod-conflict input {
  color: var(--jp-error-color1);
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

.jp-LastModified-hidden {
  display: none;
}

.jp-FileBrowser-filterBox {
  padding: 0px;
  flex: 0 0 auto;
  margin: 8px 12px 0px 12px;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing:focus-visible {
  border: 1px solid var(--jp-brand-color1);
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px 12px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-id-narrow {
  display: none;
  flex: 0 0 5px;
  padding: 4px 4px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
  color: var(--jp-border-color2);
}

.jp-DirListing-narrow .jp-id-narrow {
  display: block;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-content mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.jp-DirListing-content .jp-DirListing-item.jp-mod-selected mark {
  color: var(--jp-ui-inverse-font-color0);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-item[data-is-dot] {
  opacity: 75%;
}

.jp-DirListing-item.jp-mod-selected {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon:before {
  color: var(--jp-success-color1);
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.jp-mod-running.jp-mod-selected
  .jp-DirListing-itemIcon:before {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0px;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-DirListing-deadSpace {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
}

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: flex;
  flex-direction: row;
}

body[data-format='mobile'] .jp-OutputArea-child {
  flex-direction: column;
}

.jp-OutputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

body[data-format='mobile'] .jp-OutputPrompt {
  flex: 0 0 auto;
  text-align: left;
}

.jp-OutputArea-output {
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea-child .jp-OutputArea-output {
  flex-grow: 1;
  flex-shrink: 1;
}

body[data-format='mobile'] .jp-OutputArea-child .jp-OutputArea-output {
  margin-left: var(--jp-notebook-padding);
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0px;
  padding: 0px;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0px;
  flex: 1 1 auto;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
  border-top: var(--jp-border-width) solid transparent;
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-OutputArea-stdin {
  line-height: var(--jp-code-line-height);
  padding-top: var(--jp-code-padding);
  display: flex;
}

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;
  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0px;
  bottom: 0px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0px;
  width: 100%;
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: flex;
  flex-direction: row;
  overflow: hidden;
}

body[data-format='mobile'] .jp-InputArea {
  flex-direction: column;
}

.jp-InputArea-editor {
  flex: 1 1 auto;
  overflow: hidden;
}

.jp-InputArea-editor {
  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0px;
  background: var(--jp-cell-editor-background);
}

body[data-format='mobile'] .jp-InputArea-editor {
  margin-left: var(--jp-notebook-padding);
}

.jp-InputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

body[data-format='mobile'] .jp-InputPrompt {
  flex: 0 0 auto;
  text-align: left;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: flex;
  flex-direction: row;
  flex: 1 1 auto;
}

.jp-Placeholder-prompt {
  box-sizing: border-box;
}

.jp-Placeholder-content {
  flex: 1 1 auto;
  border: none;
  background: transparent;
  height: 20px;
  box-sizing: border-box;
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0px;
  margin: 0px;
  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 200px;
  box-shadow: inset 0 0 6px 2px rgba(0, 0, 0, 0.3);
  margin-left: var(--jp-private-cell-scrolling-output-offset);
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  flex: 0 0
    calc(
      var(--jp-cell-prompt-width) -
        var(--jp-private-cell-scrolling-output-offset)
    );
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  flex: 1 1 auto;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

.jp-showHiddenCellsButton {
  margin-left: calc(var(--jp-cell-prompt-width) + 2 * var(--jp-code-padding));
  margin-top: var(--jp-code-padding);
  border: 1px solid var(--jp-border-color2);
  background-color: var(--jp-border-color3) !important;
  color: var(--jp-content-font-color0) !important;
}

.jp-showHiddenCellsButton:hover {
  background-color: var(--jp-border-color2) !important;
}

.jp-collapseHeadingButton {
  display: none;
}

.jp-MarkdownCell:hover .jp-collapseHeadingButton {
  display: flex;
  min-height: var(--jp-cell-collapser-min-height);
  position: absolute;
  right: 0;
  top: 0;
  bottom: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: 2px;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-MainAreaWidget-ContainStrict .jp-Notebook * {
  contain: strict;
}

.jp-Notebook-render * {
  contain: none !important;
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
  float: left;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* cell is dirty */
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt {
  color: var(--jp-warn-color1);
}
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt:before {
  color: var(--jp-warn-color1);
  content: '•';
}

.jp-Notebook .jp-Cell.jp-mod-active.jp-mod-dirty .jp-Collapser {
  background: var(--jp-warn-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: block;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0px;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-NotebookTools-tool {
  padding: 0px 12px 0 12px;
}

.jp-ActiveCellTool {
  padding: 12px;
  background-color: var(--jp-layout-color1);
  border-top: none !important;
}

.jp-ActiveCellTool .jp-InputArea-prompt {
  flex: 0 0 auto;
  padding-left: 0px;
}

.jp-ActiveCellTool .jp-InputArea-editor {
  flex: 1 1 auto;
  background: var(--jp-cell-editor-background);
  border-color: var(--jp-cell-editor-border-color);
}

.jp-ActiveCellTool .jp-InputArea-editor .CodeMirror {
  background: transparent;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0px 12px 0px;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label {
  line-height: 1.4;
}

.jp-NotebookTools .jp-select-wrapper {
  margin-top: 4px;
  margin-bottom: 0px;
}

.jp-NotebookTools .jp-Collapse {
  margin-top: 16px;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Cell-Placeholder {
  padding-left: 55px;
}

.jp-Cell-Placeholder-wrapper {
  background: #fff;
  border: 1px solid;
  border-color: #e5e6e9 #dfe0e4 #d0d1d5;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  margin: 10px 15px;
}

.jp-Cell-Placeholder-wrapper-inner {
  padding: 15px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body {
  background-repeat: repeat;
  background-size: 50% auto;
}

.jp-Cell-Placeholder-wrapper-body div {
  background: #f6f7f8;
  background-image: -webkit-linear-gradient(
    left,
    #f6f7f8 0%,
    #edeef1 20%,
    #f6f7f8 40%,
    #f6f7f8 100%
  );
  background-repeat: no-repeat;
  background-size: 800px 104px;
  height: 104px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body div {
  position: absolute;
  right: 15px;
  left: 15px;
  top: 15px;
}

div.jp-Cell-Placeholder-h1 {
  top: 20px;
  height: 20px;
  left: 15px;
  width: 150px;
}

div.jp-Cell-Placeholder-h2 {
  left: 15px;
  top: 50px;
  height: 10px;
  width: 100px;
}

div.jp-Cell-Placeholder-content-1,
div.jp-Cell-Placeholder-content-2,
div.jp-Cell-Placeholder-content-3 {
  left: 15px;
  right: 15px;
  height: 10px;
}

div.jp-Cell-Placeholder-content-1 {
  top: 100px;
}

div.jp-Cell-Placeholder-content-2 {
  top: 120px;
}

div.jp-Cell-Placeholder-content-3 {
  top: 140px;
}

</style>

    <style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0px 2px 1px -1px var(--jp-shadow-umbra-color),
    0px 1px 1px 0px var(--jp-shadow-penumbra-color),
    0px 1px 3px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0px 3px 1px -2px var(--jp-shadow-umbra-color),
    0px 2px 2px 0px var(--jp-shadow-penumbra-color),
    0px 1px 5px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0px 2px 4px -1px var(--jp-shadow-umbra-color),
    0px 4px 5px 0px var(--jp-shadow-penumbra-color),
    0px 1px 10px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0px 3px 5px -1px var(--jp-shadow-umbra-color),
    0px 6px 10px 0px var(--jp-shadow-penumbra-color),
    0px 1px 18px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0px 5px 5px -3px var(--jp-shadow-umbra-color),
    0px 8px 10px 1px var(--jp-shadow-penumbra-color),
    0px 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0px 7px 8px -4px var(--jp-shadow-umbra-color),
    0px 12px 17px 2px var(--jp-shadow-penumbra-color),
    0px 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0px 8px 10px -5px var(--jp-shadow-umbra-color),
    0px 16px 24px 2px var(--jp-shadow-penumbra-color),
    0px 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0px 10px 13px -6px var(--jp-shadow-umbra-color),
    0px 20px 31px 3px var(--jp-shadow-penumbra-color),
    0px 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0px 11px 15px -7px var(--jp-shadow-umbra-color),
    0px 24px 38px 3px var(--jp-shadow-penumbra-color),
    0px 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;

  --jp-ui-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica,
    Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;

  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);

  --jp-content-link-color: var(--md-blue-700);

  --jp-content-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: Menlo, Consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-900);
  --jp-brand-color1: var(--md-blue-700);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);

  --jp-accent-color0: var(--md-green-900);
  --jp-accent-color1: var(--md-green-700);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-900);
  --jp-warn-color1: var(--md-orange-700);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);

  --jp-error-color0: var(--md-red-900);
  --jp-error-color1: var(--md-red-700);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);

  --jp-success-color0: var(--md-green-900);
  --jp-success-color1: var(--md-green-700);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);

  --jp-info-color0: var(--md-cyan-900);
  --jp-info-color1: var(--md-cyan-700);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;

  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;

  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);

  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: var(--jp-code-font-family-default);
  --jp-cell-prompt-letter-spacing: 0px;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);
  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;
  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0px 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Statusbar specific styles */

  --jp-statusbar-height: 24px;

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-border-color1);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: #05a;
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #aa22ff;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #aa22ff;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 250px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);
}
</style>

<style type="text/css">
/* Force rendering true colors when outputing to pdf */
* {
  -webkit-print-color-adjust: exact;
}

/* Misc */
a.anchor-link {
  display: none;
}

.highlight  {
  margin: 0.4em;
}

/* Input area styling */
.jp-InputArea {
  overflow: hidden;
}

.jp-InputArea-editor {
  overflow: hidden;
}

.CodeMirror pre {
  margin: 0;
  padding: 0;
}

/* Using table instead of flexbox so that we can use break-inside property */
/* CSS rules under this comment should not be required anymore after we move to the JupyterLab 4.0 CSS */


.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  min-width: calc(
    var(--jp-cell-prompt-width) - var(--jp-private-cell-scrolling-output-offset)
  );
}

.jp-OutputArea-child {
  display: table;
  width: 100%;
}

.jp-OutputPrompt {
  display: table-cell;
  vertical-align: top;
  min-width: var(--jp-cell-prompt-width);
}

body[data-format='mobile'] .jp-OutputPrompt {
  display: table-row;
}

.jp-OutputArea-output {
  display: table-cell;
  width: 100%;
}

body[data-format='mobile'] .jp-OutputArea-child .jp-OutputArea-output {
  display: table-row;
}

.jp-OutputArea-output.jp-OutputArea-executeResult {
  width: 100%;
}

/* Hiding the collapser by default */
.jp-Collapser {
  display: none;
}

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }

  .jp-OutputArea-child {
    break-inside: avoid-page;
  }
}
</style>

<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-AMS_CHTML-full,Safe"> </script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                CommonHTML: {
                    linebreaks: { 
                    automatic: true 
                    }
                }
            });
        
            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
    <!-- End of mathjax configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">

<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Data Science task project:</p>
<p>Task:</p>
<ol>
<li>Using the attached dataset (credit_risk_dataset_training.csv) analyse the data and 
visualize the most important aspects using your preferred method. Furthermore, 
share three ideas on how to increase the % of successful loan applicants. 
Document your steps where needed.</li>
</ol>
<ol>
<li>Predict the outcome of a loan: is a customer likely to satisfy or default on the loan 
obligations? Use credit_risk_dataset_training.csv to train your model and 
credit_risk_dataset_test.csv to predict the missing value (‘loan_status’). Please 
document your steps and method used. Include the accuracy or evaluation metric used for 
calibrating your model
Key success factors:
● Be precise and structure your answers in a clear manner. Don’t beat around the bush.
● Presentation of the answers is key. Show us what you did.
● Showcase your creativity and have fun doing it</li>
</ol>

<pre><code>    Undertaken by:
        Timothy Mutumwa Kiriinya.</code></pre>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h3>Importing the necessary libraries <br></h3>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Pandas for data analysis and manipulation <br>
Numpy  for mathematical and logical operations <br>
seaborn and matplotlib.pyplot for data visualization <br>
sklearn for machine learning <br></p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[69]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span> 
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="kn">import</span> <span class="n">svm</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">accuracy_score</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="kn">import</span> <span class="n">train_test_split</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="kn">import</span> <span class="n">cross_val_score</span>
<span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="kn">import</span> <span class="n">LogisticRegression</span>
<span class="kn">from</span> <span class="nn">sklearn.neighbors</span> <span class="kn">import</span> <span class="n">KNeighborsClassifier</span>
<span class="kn">from</span> <span class="nn">sklearn.preprocessing</span> <span class="kn">import</span> <span class="n">LabelEncoder</span>
<span class="kn">from</span> <span class="nn">sklearn.ensemble</span> <span class="kn">import</span> <span class="n">RandomForestClassifier</span>
<span class="kn">from</span> <span class="nn">sklearn.tree</span> <span class="kn">import</span> <span class="n">DecisionTreeClassifier</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="o">%</span><span class="k">matplotlib</span> inline
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>I extracted the data into the project after I uploaded it to jupyter IDE <br>
I decided to name my training dataset as "loan_data" and  <br>
test dataset as "test_data"</p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[70]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">loan_data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;credit_risk_dataset_training.csv&#39;</span><span class="p">)</span>
<span class="n">test_data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;credit_risk_dataset_test.csv&#39;</span><span class="p">)</span>
<span class="c1">#displaying the first 5 rows of the dataset</span>
<span class="n">loan_data</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[70]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>person_age</th>
      <th>person_income</th>
      <th>person_home_ownership</th>
      <th>person_emp_length</th>
      <th>loan_intent</th>
      <th>loan_grade</th>
      <th>loan_amnt</th>
      <th>loan_int_rate</th>
      <th>loan_status</th>
      <th>loan_percent_income</th>
      <th>cb_person_default_on_file</th>
      <th>cb_person_cred_hist_length</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>22</td>
      <td>59000</td>
      <td>RENT</td>
      <td>123.0</td>
      <td>PERSONAL</td>
      <td>D</td>
      <td>35000</td>
      <td>16.02</td>
      <td>1</td>
      <td>0.59</td>
      <td>Y</td>
      <td>3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>21</td>
      <td>9600</td>
      <td>OWN</td>
      <td>5.0</td>
      <td>EDUCATION</td>
      <td>B</td>
      <td>1000</td>
      <td>11.14</td>
      <td>0</td>
      <td>0.10</td>
      <td>N</td>
      <td>2</td>
    </tr>
    <tr>
      <th>2</th>
      <td>23</td>
      <td>65500</td>
      <td>RENT</td>
      <td>4.0</td>
      <td>MEDICAL</td>
      <td>C</td>
      <td>35000</td>
      <td>15.23</td>
      <td>1</td>
      <td>0.53</td>
      <td>N</td>
      <td>2</td>
    </tr>
    <tr>
      <th>3</th>
      <td>21</td>
      <td>9900</td>
      <td>OWN</td>
      <td>2.0</td>
      <td>VENTURE</td>
      <td>A</td>
      <td>2500</td>
      <td>7.14</td>
      <td>1</td>
      <td>0.25</td>
      <td>N</td>
      <td>2</td>
    </tr>
    <tr>
      <th>4</th>
      <td>26</td>
      <td>77100</td>
      <td>RENT</td>
      <td>8.0</td>
      <td>EDUCATION</td>
      <td>B</td>
      <td>35000</td>
      <td>12.42</td>
      <td>1</td>
      <td>0.45</td>
      <td>N</td>
      <td>3</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>I describe the shape of the data <br> 
<i> This information will be vital in cheking if there's any missing values later </i></p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[71]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">loan_data</span><span class="o">.</span><span class="n">shape</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[71]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>(22850, 12)</pre>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><i> from the output above we have 12 columns and 22850 rows </i></p>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>I described the dataset as shown below to check for the total number of each variable and whether it aligns with what I got from above <br>
Also to confirm the datatype of each variable</p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[72]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">loan_data</span><span class="o">.</span><span class="n">info</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>&lt;class &#39;pandas.core.frame.DataFrame&#39;&gt;
RangeIndex: 22850 entries, 0 to 22849
Data columns (total 12 columns):
 #   Column                      Non-Null Count  Dtype  
---  ------                      --------------  -----  
 0   person_age                  22850 non-null  int64  
 1   person_income               22850 non-null  int64  
 2   person_home_ownership       22850 non-null  object 
 3   person_emp_length           22237 non-null  float64
 4   loan_intent                 22850 non-null  object 
 5   loan_grade                  22850 non-null  object 
 6   loan_amnt                   22850 non-null  int64  
 7   loan_int_rate               20703 non-null  float64
 8   loan_status                 22850 non-null  int64  
 9   loan_percent_income         22850 non-null  float64
 10  cb_person_default_on_file   22850 non-null  object 
 11  cb_person_cred_hist_length  22850 non-null  int64  
dtypes: float64(3), int64(5), object(4)
memory usage: 2.1+ MB
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b> From the data above we get the datatype of each variable and the total count of each of the variables.<br>
From the observation made "person_emp_length" and "loan_int_rate" have some missing values as they all 
don't add up to 22850 from the shape we described above. <br>
</b>
<br>
<br>
<br>
Let's confirm this observation in the next cell</p>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>here I checked for the total number of missing values for each variable</p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[73]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">loan_data</span><span class="o">.</span><span class="n">isnull</span><span class="p">()</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[73]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>person_age                       0
person_income                    0
person_home_ownership            0
person_emp_length              613
loan_intent                      0
loan_grade                       0
loan_amnt                        0
loan_int_rate                 2147
loan_status                      0
loan_percent_income              0
cb_person_default_on_file        0
cb_person_cred_hist_length       0
dtype: int64</pre>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b>
From the data above variable "person_emp_length" and "loan_int_rate" have some missing values. <br> By adding the values we get a total of 2,760 missing values.<br> 
Assuming each value of the two variables is on a different row, <br> we will have rows less than than 2,760 with missing values.<br> 2,760 out of 22,850 rows is around 12.08%, <br> So I chose to eliminate the rows with missing values in the next cell.
</b></p>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>here I dropped all the rows with missing values</p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[74]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">clean_data</span> <span class="o">=</span> <span class="n">loan_data</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[75]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Here I confirmed whether we still had missing values</span>
<span class="n">clean_data</span><span class="o">.</span><span class="n">isnull</span><span class="p">()</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[75]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>person_age                    0
person_income                 0
person_home_ownership         0
person_emp_length             0
loan_intent                   0
loan_grade                    0
loan_amnt                     0
loan_int_rate                 0
loan_status                   0
loan_percent_income           0
cb_person_default_on_file     0
cb_person_cred_hist_length    0
dtype: int64</pre>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b>
From the data above we can see that we have no variables with missing values.
</b></p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[76]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#lets describe the data to have a statistical look</span>
<span class="n">clean_data</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[76]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>person_age</th>
      <th>person_income</th>
      <th>person_emp_length</th>
      <th>loan_amnt</th>
      <th>loan_int_rate</th>
      <th>loan_status</th>
      <th>loan_percent_income</th>
      <th>cb_person_cred_hist_length</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>20136.000000</td>
      <td>2.013600e+04</td>
      <td>20136.000000</td>
      <td>20136.000000</td>
      <td>20136.000000</td>
      <td>20136.000000</td>
      <td>20136.000000</td>
      <td>20136.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>27.696663</td>
      <td>6.668643e+04</td>
      <td>4.799315</td>
      <td>9664.420689</td>
      <td>11.044253</td>
      <td>0.218415</td>
      <td>0.169607</td>
      <td>5.785658</td>
    </tr>
    <tr>
      <th>std</th>
      <td>6.249689</td>
      <td>6.528580e+04</td>
      <td>4.117205</td>
      <td>6331.903997</td>
      <td>3.232466</td>
      <td>0.413181</td>
      <td>0.106243</td>
      <td>4.024539</td>
    </tr>
    <tr>
      <th>min</th>
      <td>20.000000</td>
      <td>4.000000e+03</td>
      <td>0.000000</td>
      <td>500.000000</td>
      <td>5.420000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>23.000000</td>
      <td>3.900000e+04</td>
      <td>2.000000</td>
      <td>5000.000000</td>
      <td>7.900000</td>
      <td>0.000000</td>
      <td>0.090000</td>
      <td>3.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>26.000000</td>
      <td>5.595600e+04</td>
      <td>4.000000</td>
      <td>8000.000000</td>
      <td>10.990000</td>
      <td>0.000000</td>
      <td>0.150000</td>
      <td>4.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>30.000000</td>
      <td>8.000000e+04</td>
      <td>7.000000</td>
      <td>12500.000000</td>
      <td>13.480000</td>
      <td>0.000000</td>
      <td>0.230000</td>
      <td>8.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>144.000000</td>
      <td>6.000000e+06</td>
      <td>123.000000</td>
      <td>35000.000000</td>
      <td>23.220000</td>
      <td>1.000000</td>
      <td>0.780000</td>
      <td>30.000000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b>
from the describe attribute data table we can see the statistics of our dataset, that is the count, mean, standard deviation,etc
&lt;/b</p>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h4 id="Here-I'll-try-to-change-the-categorical-columns-into-numerical-values-for-analysis">Here I'll try to change the categorical columns into numerical values for analysis<a class="anchor-link" href="#Here-I'll-try-to-change-the-categorical-columns-into-numerical-values-for-analysis">&#182;</a></h4>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[77]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#before changing the categorizes to columns I&#39;ll first check what they entail to avoid missing any detail.</span>
<span class="n">clean_data</span><span class="p">[</span><span class="s1">&#39;person_home_ownership&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[77]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>RENT        10210
MORTGAGE     8283
OWN          1573
OTHER          70
Name: person_home_ownership, dtype: int64</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[78]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#checking what they contain</span>
<span class="n">clean_data</span><span class="p">[</span><span class="s1">&#39;loan_intent&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[78]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>EDUCATION            4025
MEDICAL              3662
VENTURE              3484
PERSONAL             3432
DEBTCONSOLIDATION    3234
HOMEIMPROVEMENT      2299
Name: loan_intent, dtype: int64</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[79]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#checking what they contain</span>
<span class="n">clean_data</span><span class="p">[</span><span class="s1">&#39;loan_grade&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[79]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>A    6591
B    6468
C    3983
D    2302
E     609
F     146
G      37
Name: loan_grade, dtype: int64</pre>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[80]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#checking what they contain</span>
<span class="n">clean_data</span><span class="p">[</span><span class="s1">&#39;cb_person_default_on_file&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[80]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>N    16532
Y     3604
Name: cb_person_default_on_file, dtype: int64</pre>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h3 id="Label-encoding-to-change-categorizes-to-numerical-values-for-later-analysis.">Label encoding to change categorizes to numerical values for later analysis.<a class="anchor-link" href="#Label-encoding-to-change-categorizes-to-numerical-values-for-later-analysis.">&#182;</a></h3>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[81]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#changing the categorizes to numerical values</span>
    <span class="c1">#I had used the LabelEncoder library but I kept getting erros. I opted to go the long way.</span>
<span class="n">encoded_data</span> <span class="o">=</span> <span class="n">clean_data</span><span class="o">.</span><span class="n">replace</span><span class="p">({</span><span class="s1">&#39;person_home_ownership&#39;</span><span class="p">:{</span><span class="s1">&#39;RENT&#39;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s1">&#39;MORTGAGE&#39;</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span> <span class="s1">&#39;OWN&#39;</span><span class="p">:</span><span class="mi">2</span><span class="p">,</span> <span class="s1">&#39;OTHER&#39;</span><span class="p">:</span><span class="mi">3</span><span class="p">},</span>
                                 <span class="s1">&#39;loan_intent&#39;</span><span class="p">:{</span><span class="s1">&#39;EDUCATION&#39;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s1">&#39;MEDICAL&#39;</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span> <span class="s1">&#39;VENTURE&#39;</span><span class="p">:</span><span class="mi">2</span><span class="p">,</span> <span class="s1">&#39;PERSONAL&#39;</span><span class="p">:</span><span class="mi">3</span><span class="p">,</span> <span class="s1">&#39;DEBTCONSOLIDATION&#39;</span><span class="p">:</span><span class="mi">4</span><span class="p">,</span> <span class="s1">&#39;HOMEIMPROVEMENT&#39;</span><span class="p">:</span><span class="mi">5</span><span class="p">,},</span>
                                 <span class="s1">&#39;loan_grade&#39;</span><span class="p">:{</span><span class="s1">&#39;A&#39;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s1">&#39;B&#39;</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span> <span class="s1">&#39;C&#39;</span><span class="p">:</span><span class="mi">2</span><span class="p">,</span> <span class="s1">&#39;D&#39;</span><span class="p">:</span><span class="mi">3</span><span class="p">,</span> <span class="s1">&#39;E&#39;</span><span class="p">:</span><span class="mi">4</span><span class="p">,</span> <span class="s1">&#39;F&#39;</span><span class="p">:</span><span class="mi">5</span><span class="p">,</span> <span class="s1">&#39;G&#39;</span><span class="p">:</span><span class="mi">6</span><span class="p">},</span>
                                 <span class="s1">&#39;cb_person_default_on_file&#39;</span><span class="p">:{</span><span class="s1">&#39;N&#39;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s1">&#39;Y&#39;</span><span class="p">:</span><span class="mi">1</span><span class="p">}</span>
                                <span class="p">})</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b> from the observation : the data has been converted from string to numerical values </b></p>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h2 id="Data-Visualization">Data Visualization<a class="anchor-link" href="#Data-Visualization">&#182;</a></h2><h3 id="I'll-plot-and-visualize-predictor-variables-against-our-target-variable-to-see-the-relation.">I'll plot and visualize predictor variables against our target variable to see the relation.<a class="anchor-link" href="#I'll-plot-and-visualize-predictor-variables-against-our-target-variable-to-see-the-relation.">&#182;</a></h3>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[82]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Visualization of the numeric distribution</span>
<span class="n">clean_data</span><span class="o">.</span><span class="n">hist</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span><span class="mi">9</span><span class="p">),</span> <span class="n">bins</span><span class="o">=</span><span class="mi">12</span><span class="p">,</span> <span class="n">ec</span><span class="o">=</span><span class="s2">&quot;b&quot;</span><span class="p">,</span> <span class="n">xlabelsize</span><span class="o">=</span><span class="mi">8</span><span class="p">,</span> <span class="n">ylabelsize</span><span class="o">=</span><span class="mi">8</span><span class="p">,</span> <span class="n">alpha</span><span class="o">=</span><span class="mf">0.9</span><span class="p">,</span> <span class="n">grid</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">tight_layout</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
class="
jp-needs-light-background
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[83]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#visualization of the categoric distribution</span>
<span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">clean_data</span><span class="o">.</span><span class="n">select_dtypes</span><span class="p">(</span><span class="n">include</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;object&quot;</span><span class="p">])</span><span class="o">.</span><span class="n">columns</span><span class="p">:</span>
    <span class="n">clean_data</span><span class="p">[</span><span class="n">col</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">()</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span><span class="o">=</span><span class="s2">&quot;bar&quot;</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="n">sns</span><span class="o">.</span><span class="n">color_palette</span><span class="p">(</span><span class="s2">&quot;rocket&quot;</span><span class="p">))</span>
    
    <span class="n">plt</span><span class="o">.</span><span class="n">xlabel</span><span class="p">(</span><span class="s2">&quot;Class&quot;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">10</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">xticks</span><span class="p">(</span><span class="n">rotation</span><span class="o">=</span><span class="mi">90</span><span class="p">,</span> <span class="n">horizontalalignment</span><span class="o">=</span><span class="s2">&quot;center&quot;</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">ylabel</span><span class="p">(</span><span class="s2">&quot;Count&quot;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">10</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="n">col</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">10</span><span class="p">,</span> <span class="n">loc</span><span class="o">=</span><span class="s2">&quot;right&quot;</span><span class="p">)</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
class="
jp-needs-light-background
"
>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
class="
jp-needs-light-background
"
>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
class="
jp-needs-light-background
"
>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
class="
jp-needs-light-background
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[84]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># here we check how the loan intent affects loan defaulting</span>
<span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s1">&#39;loan_intent&#39;</span><span class="p">,</span> <span class="n">hue</span><span class="o">=</span><span class="s1">&#39;loan_status&#39;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">clean_data</span><span class="p">)</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">rc</span> <span class="o">=</span> <span class="p">{</span><span class="s1">&#39;figure.figsize&#39;</span><span class="p">:(</span><span class="mi">16</span><span class="p">,</span><span class="mi">4</span><span class="p">)})</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAa0AAAEMCAYAAAB3Ful8AAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjUuMSwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy/YYfK9AAAACXBIWXMAAAsTAAALEwEAmpwYAAAqnElEQVR4nO3de5xVVfnH8c8ZGC7FTWEI8AL6Qx7voAGZVzSze2amlgiCihKaWZmWYoplJhYSJmoiopJ3I/OCXbzhtULFVOQJSzEEBVGCUYEZZn5/rHVkzzCXMzBnztkz3/frxYs56+y9zlp777OfvdZeZ+1MdXU1IiIiaVBS6AKIiIjkSkFLRERSQ0FLRERSQ0FLRERSQ0FLRERSQ0FLRERSo30+Mzezi4FvANXA9e4+xcxuAA4E3o+LTXL3OWY2BJgBdAPmAePdvdLMdgRmA70BB0a6e3k+yy0iIsUpby0tMzsEOAzYGxgKfMfMLP59sLsPif/mxFVmA2e4+yAgA4yL6dOB6e6+KzAfuCBfZRYRkeKWyeePi82s1N0rzKw/8ARwAPAi8BSwHTAHmATsADzs7v8X1zsopn8OWAVsG1tdOwCPufvOOXx8R2AYsBzY2Lw1ExFptdoBfYF/AOsLXJbN5LV7MAasScDZwJ1AKfAwMAH4H3AfcDLwEiG4ZC0Htgd6AWvcvbJWei6GAY9vbR1ERNqogwiNjaKS16AF4O4XmtllwL3AZ9z9qOx7ZnYlMBpYSLjvlZUBqgjdl7WbglU5fvRygPfee5+qKk1VJSKSi5KSDNts83Go2ZAoGnkLWma2K9DJ3Re4+wdm9nvgODNb5e53x8UyQAWwlNAczeoDLANWAN3NrJ27b4zLLMuxCBsBqqqqFbRERJquKG+r5HPI+87AdWbW0cw6AEcCjwFTzWwbMysFTgXmuPsSYJ2ZHRDXHQXMdfcKQhffcTF9NDA3j2UWEZEilreg5e4PAPcDzwPPAk+5+8XApcCThC7BBe5+a1xlJHCFmS0CugDTYvoE4FQzW0joY52YrzKLiEhxy+vowQIbALy2alW5ugdFhA8/fJ/y8tVs3FjZ+MJtQLt27enSpQedO3+8RnpJSYaePbsA7AS8XoCiNSjvAzFERArtww/fZ+3a9+jRo4zS0g5kMplCF6mgqqurqajYwOrVKwE2C1zFTNM4iUirV16+mh49yujQoWObD1gAmUyGDh060qNHGeXlqwtdnCZR0BKRVm/jxkpKSzsUuhhFp7S0Q+q6SxW0RKRNUAtrc2ncJrqn1Qp17daJTh1Lmz3fdesrWLtmXbPnKyKSKwWtVqhTx1KOP+d3zZ7vLZNHshYFLREpHHUPikib9dxz8xk16thCFwOAyy77GYsWvdJsy7VWCloiIkXgH//4G5tPtbrly7VW6h4UkTavvLycKVMuY/FiJ5PJsN9++3PqqafTvn177rvvHu655/dUVlawZs0aTjhhDEcd9Q0eeOBe5s17hEymhKVL36BTp06cf/4kBgzYqd7PqaysZOrUy3nxxRdo1649/fptx3nnXcjNN9/AO++sZNKkiUyceDHV1dVcffU0NmzYwKpV7zBs2Kf48Y9/wrXXXlVjuauvnsbRRx/LoYceDsAZZ5z60evrr7+WefMeoX37Urp37855511Er169WmqT5o1aWiLS5k2dejndunXnpptuZ8aMm3n11cXceutsPvjgA+699w/88pe/5oYbbmHSpEuZPn3aR+stWPAc3/veD7n55jvYffc9mT17VoOf8/LLL/L8888ya9atzJw5m379tuPf/17MaaedTq9eZVx44c/YY489ufPOWzn55NO47robmT37Tp58ch6LFr2y2XL1efvtt7jjjlu47rqbuP76mxk2bD8WLnypuTZXQamlJSJt3jPPPMXVV18ff3TbgSOPPJo777yVUaPGMHnyFTz11BMsXfpfFi/+Fx9++MFH65ntRu/enwBg0KBdeeyxRxr8nJ13HkhJSQmnnnoiw4d/mhEjDmP33TcPPhMnTuLpp5/kpptmsmTJ66xfv77G5zamrKw3AwcO4qSTTmC//fZnv/32Z+jQ4TmvX8zU0hKRNq+6uqrGb5aqq6uorKxkxYq3GTt2JG+//RZ77z2EceO+XWO9jh07fvR3WL/he01du3Zl1qxbOf30sygpKeHCC8/j97+/c7PlTj99HE8//ST9+w9g7Nhx9OpVRl3zxGYyGZLJlZXhh8IlJSX85je/5fzzL6R79+5ceeUUpk//dS6bougpaIlImzd8+Ke5++47qK6uZsOGDfzxj3MYNuxTLFr0Cj169ODEE09m+PD9eOqp8DD0jRu37FFTTz75ON/97rfZc8+9Ofnk0/j857/EokULAWjXrh2VlZWsXbuWRYsW8u1vf4dDDjmM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
"
class="
jp-needs-light-background
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b> observaton from the data above: <br>
    customers with Educational intents with the loan are the one with the highest non-defaulters <br>
    customer with Personal and venture intents follow closely by being most likely to pay their debts. <br>
    Customers with Medical, home improvement and debt consolidation intentions are more likely to default their loans as compared to the customers with other intents . <br></p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[85]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># here we check whether the home ownership affects loan defaulting</span>
<span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s1">&#39;person_home_ownership&#39;</span><span class="p">,</span> <span class="n">hue</span><span class="o">=</span><span class="s1">&#39;loan_status&#39;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">clean_data</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[85]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:xlabel=&#39;person_home_ownership&#39;, ylabel=&#39;count&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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l12mlJQU+fv7a9CgQbriiiv09ddf67HHHpPNZtOKFSvk7e0tX19fzZw5U5dccon27t2rmTNn6ujRozKZTHrggQd0++23a+vWrVqwYIFCQkK0d+9e1dXVKS0tTVdfffUp63322Wf1+eef6+jRo3rwwQc1evRoSdJzzz2nf/7znzKbzerWrZueeOIJWa1WjRkzRr1799Znn32mI0eO6K677lJJSYm2bdum48ePa+HCherRo4fKy8s1e/Zs7dmzR7W1tQoPD1dCQoIslsYv9yc77ueff66XXnpJr732miRpyJAhGj58uKZNm6YffvhBo0aN0uuvv677779fkZGR+vzzz3Xs2DHFx8frlltukSRlZWXp7bfflsPhUJcuXZSamqrOnTtrzJgxat++vb755hvde++96ty5s7KysmQymWQ2m5WQkKB+/fpJkt555x0tWbJEJSUlCg8P16xZs3T48GFFR0fr008/1bPPPquDBw/qhx9+kM1mU8+ePTV79mz5+/ufzV8pAIABMLILADCEXbt2acyYMdqwYYNiYmIUHx+v559/XmazWWvWrNH69esVGBiojIwM1zaXXnqp3nrrLQ0aNEhz5szRiy++qDfffFN33XWXCgoKVFdXp8mTJ7v2+8ILL2j+/Pn69NNPJUk7duzQAw88oHXr1ikmJkYLFixoUq0hISFas2aNFi9erPT0dNXW1urNN9/UBx98oNWrV2vDhg269NJLlZiY6NqmsLBQK1as0FNPPaWnnnpK11xzjdasWaPrr79er7zyiiRpzpw56t27t9asWaN169aprKxML7/8cqO1/NZxr7vuOn399dc6duyYDh06pMrKSuXl5Un6OYDefPPNMplM+u6773Tddddp9erVevzxxzVnzhxJ0rp167Rnzx6tWrVK2dnZioyMVEpKiuu4559/vnJycjRmzBjNmzdPqampWrNmjf7yl79o69atrn6VlZVasWKFcnJy9P7772v79u0NziE/P18LFy7UW2+9JYvFoueee65Jfw4AAGNjZBcAYAg9e/ZUWFiYJGnkyJGaOXOmKioqZDKZXCGttrZWHTt2dG1zor/ZbFZUVJTuuece3XDDDbruuusUGRmp/fv3q7q6WoMHD5b08/TZwYMH64MPPlD//v114YUXqlevXpKkyy67TGvXrm1SrbfeeqskqVevXqqpqVFFRYXef/99xcTEqG3btpKksWPH6r//+79VU1MjSa7R0pCQEEnS9ddfL0n6wx/+oG3btkmS3nvvPe3cuVOrV6+WJFVVVZ2ylt86rpeXlwYMGKAtW7aorKxMd999t9544w2Vl5fr3Xff1fjx4yVJ3t7eioyMdL0GR48elST97//+r3bu3KmRI0dKkhwOh44fP97gtZek4cOHa8qUKYqMjNTAgQM1YcIE17phw4bJbDbLz89PF198sUpLSxUUFFTvHKKiotSpUydJ0qhRozRnzhz97W9/O+W5AwCMjbALADAEs9ncoM3hcOiJJ55whbHKykpVV1e71p8IeJKUkZGhPXv2KC8vT88//7yys7P18MMPy2Qy1dun0+lUXV2dJKlNmzaudpPJJKfT2aRaT0wrPrFvp9Mph8NR71gOh8N1HEny8fGptw9vb++Tnu8zzzyj7t27S5KOHTvWoP6TbfNbx7355pv1/vvv69ixYxo/fry++eYb/etf/9KePXt0zTXX6Pvvv5e3t7e8vLzqnc+J/YwfP16xsbGSpJqaGv3444+u9b987ePi4jRy5Eht2bJFa9as0UsvveQK7L+cgv1br/Ev/+wdDoerHgDA7xtXAwCAIXz11Vf66quvJElvvPGG+vbtq2HDhunVV19VTU2NK/jOnz+/wbZHjhxRZGSkOnTooHHjxunRRx/Vzp079cc//lEWi0Vvv/22pJ/vArxp0yYNGDCg2eu//vrr9eabb+qnn36SJC1fvlz9+vVrEHIbc91112np0qVyOp2qqanR5MmTXVOcz+S4gwYN0kcffaTdu3friiuu0MCBA/XMM88oIiLipP+58OtaVq9erYqKCknSM888o4SEhAb96urqNGjQIB0/flz33nuvUlNT9fXXX7tGtJvinXfeUXl5uRwOh1auXKkbb7yxydsCAIyLkV0AgCF06tRJCxcuVGFhoQICAjRv3jx16tRJTz75pO644w7Z7Xb16tWr3vdgTwgICNDkyZM1btw4tWnTRmazWbNmzZK3t7cyMzM1a9YsPfvss7Lb7XrkkUd07bXX1vteaXMYNWqUvv/+e915551yOBzq2rVrve8XN0VycrJmz56t6Oho1dbWasCAAa7pxmdy3Hbt2ql79+7y8/OT2WzW9ddfr+TkZNe07sbceeedKioq0l133SWTyaTg4GClp6c36GexWJSUlKS//vWvslgsMplMmjNnzmmF/E6dOmnChAkqKytTv379NGnSpCZvCwAwLpOzqXOuAABopbZu3aq///3v2rhxo6dLQQt79tlnVVZWphkzZni6FABAK8PILgAAzejFF1/Uhg0bTrruwQcf1G233dbCFUmxsbGqrKw86bpXX32Vx/QAAAyJkV0AAAAAgOFwgyoAAAAAgOEQdgEAAAAAhkPYBQAAAAAYDmEXAAAAAGA4hF0AAAAAgOEQdgEAAAAAhvP/AWRV3eShRTBOAAAAAElFTkSuQmCC
"
class="
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[86]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#here we check whether the loan grade affects loan defaulting</span>
<span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s1">&#39;loan_grade&#39;</span><span class="p">,</span> <span class="n">hue</span><span class="o">=</span><span class="s1">&#39;loan_status&#39;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">clean_data</span><span class="p">)</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">rc</span> <span class="o">=</span> <span class="p">{</span><span class="s1">&#39;figure.figsize&#39;</span><span class="p">:(</span><span class="mi">8</span><span class="p">,</span><span class="mi">6</span><span class="p">)})</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
class="
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[87]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># here we check whether the customer&#39;s age affects loan defaulting</span>
<span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s1">&#39;person_age&#39;</span><span class="p">,</span> <span class="n">hue</span><span class="o">=</span><span class="s1">&#39;loan_status&#39;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">clean_data</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[87]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:xlabel=&#39;person_age&#39;, ylabel=&#39;count&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
class="
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[88]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># here we check whether the customer&#39;s employment length affects loan defaulting</span>
<span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s1">&#39;person_emp_length&#39;</span><span class="p">,</span> <span class="n">hue</span><span class="o">=</span><span class="s1">&#39;loan_status&#39;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">clean_data</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[88]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:xlabel=&#39;person_emp_length&#39;, ylabel=&#39;count&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
class="
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h3 id="In-the-next-cell-I-will-be-separating-the-predictor-variables-from-the-target-variable-(Loan_status)">In the next cell I will be separating the predictor variables from the target variable (Loan_status)<a class="anchor-link" href="#In-the-next-cell-I-will-be-separating-the-predictor-variables-from-the-target-variable-(Loan_status)">&#182;</a></h3>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[89]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#separating loan status from the independent variables</span>
<span class="c1">#I&#39;ll be now using the data that was converted into numerical value earlier in cell 44</span>
<span class="n">X</span> <span class="o">=</span> <span class="n">encoded_data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;loan_status&#39;</span><span class="p">],</span><span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span> <span class="c1">#axis is set to one as we are dropping a column</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">encoded_data</span><span class="p">[</span><span class="s1">&#39;loan_status&#39;</span><span class="p">]</span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b> here we dropped loan_status from the X axis and added it onto the Y axis </b></p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[90]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#confirming </span>
<span class="nb">print</span><span class="p">(</span><span class="n">X</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>       person_age  person_income  person_home_ownership  person_emp_length  \
0              22          59000                      0              123.0   
1              21           9600                      2                5.0   
2              23          65500                      0                4.0   
3              21           9900                      2                2.0   
4              26          77100                      0                8.0   
...           ...            ...                    ...                ...   
22845          52          65004                      0                4.0   
22846          57          53000                      1                1.0   
22847          54         120000                      1                4.0   
22848          56         150000                      1                5.0   
22849          66          42000                      0                2.0   

       loan_intent  loan_grade  loan_amnt  loan_int_rate  loan_percent_income  \
0                3           3      35000          16.02                 0.59   
1                0           1       1000          11.14                 0.10   
2                1           2      35000          15.23                 0.53   
3                2           0       2500           7.14                 0.25   
4                0           1      35000          12.42                 0.45   
...            ...         ...        ...            ...                  ...   
22845            3           3      20000          15.58                 0.31   
22846            3           2       5800          13.16                 0.11   
22847            3           0      17625           7.49                 0.15   
22848            3           1      15000          11.48                 0.10   
22849            1           1       6475           9.99                 0.15   

       cb_person_default_on_file  cb_person_cred_hist_length  
0                              1                           3  
1                              0                           2  
2                              0                           2  
3                              0                           2  
4                              0                           3  
...                          ...                         ...  
22845                          1                          19  
22846                          0                          30  
22847                          0                          19  
22848                          0                          26  
22849                          0                          30  

[20136 rows x 11 columns]
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b> from the observation above we now have 11 columns instead of 12 <br>
    The column missing is "loan_status" and it is in the Y axis as shown below <br>
<b></p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[91]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="n">y</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>0        1
1        0
2        1
3        1
4        1
        ..
22845    1
22846    0
22847    0
22848    0
22849    0
Name: loan_status, Length: 20136, dtype: int64
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h3>Training the model <br></h3>
<p><br>
<b> I'll still need to split my training dataset so as to check for the accuracy of the model that I have created before using it in prediction </b></p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[92]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#splitting my data</span>
<span class="n">X_train</span><span class="p">,</span> <span class="n">X_test</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">y_test</span> <span class="o">=</span> <span class="n">train_test_split</span><span class="p">(</span><span class="n">X</span><span class="p">,</span> <span class="n">y</span><span class="p">,</span> <span class="n">test_size</span> <span class="o">=</span> <span class="mf">0.2</span><span class="p">,</span> <span class="n">random_state</span> <span class="o">=</span> <span class="mi">0</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h3 id="Machine-Learning-Models.">Machine Learning Models.<a class="anchor-link" href="#Machine-Learning-Models.">&#182;</a></h3><p><b> I decided to train and test my test data with different models. <br>
    I will then check for the accuracy of each model that I have created. <br>
    The model with the higher accuracy rate I'll use it to predict the <i> loan_status </i> variable<br>
</b></p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[93]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># I have created a classification function which I&#39;ll call in all my models. it will also prevent data corrupting by the first model.</span>
<span class="k">def</span> <span class="nf">classify</span><span class="p">(</span><span class="n">model</span><span class="p">,</span> <span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">):</span>
    <span class="n">x_train</span><span class="p">,</span> <span class="n">x_test</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">y_test</span> <span class="o">=</span> <span class="n">train_test_split</span><span class="p">(</span><span class="n">X</span><span class="p">,</span> <span class="n">y</span><span class="p">,</span> <span class="n">test_size</span><span class="o">=</span><span class="mf">0.25</span><span class="p">,</span> <span class="n">random_state</span><span class="o">=</span><span class="mi">42</span><span class="p">)</span>
    <span class="n">model</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x_train</span><span class="p">,</span> <span class="n">y_train</span><span class="p">)</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;The Accuracy of this model is:&quot;</span><span class="p">,</span> <span class="n">model</span><span class="o">.</span><span class="n">score</span><span class="p">(</span><span class="n">x_test</span><span class="p">,</span> <span class="n">y_test</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[94]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#KNN classifier</span>
<span class="n">odel</span> <span class="o">=</span> <span class="n">KNeighborsClassifier</span><span class="p">()</span>
<span class="n">classify</span><span class="p">(</span><span class="n">model</span><span class="p">,</span> <span class="n">X</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>The Accuracy of this model is: 80.3933253873659
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[95]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#RandomForestClassifier</span>
<span class="n">model</span> <span class="o">=</span> <span class="n">RandomForestClassifier</span><span class="p">()</span>
<span class="n">classify</span><span class="p">(</span><span class="n">model</span><span class="p">,</span> <span class="n">X</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>The Accuracy of this model is: 93.3849821215733
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[96]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#LogisticRegression model</span>
<span class="n">model</span> <span class="o">=</span> <span class="n">LogisticRegression</span><span class="p">()</span>
<span class="n">classify</span><span class="p">(</span><span class="n">model</span><span class="p">,</span> <span class="n">X</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>The Accuracy of this model is: 80.3933253873659
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[97]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#DecisionTree Classifier model</span>
<span class="n">model</span> <span class="o">=</span> <span class="n">DecisionTreeClassifier</span><span class="p">()</span>
<span class="n">classify</span><span class="p">(</span><span class="n">model</span><span class="p">,</span> <span class="n">X</span><span class="p">,</span> <span class="n">y</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>The Accuracy of this model is: 87.74334525228447
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b> Comparing the 4 models that I used RandomForest Classifier ranks the highest with an accuracy of 93.38% <br> while logisticRegression is the lowest with 80.39%. <br>
So I'll be working with the RandomForest classifier to predict <i> loan_status </i> </b></p>
<h3 id="Note:-I-commented-out-the-other-models-to-avoid-data-corruption-after-finding-the-best-model.">Note: I commented out the other models to avoid data corruption after finding the best model.<a class="anchor-link" href="#Note:-I-commented-out-the-other-models-to-avoid-data-corruption-after-finding-the-best-model.">&#182;</a></h3>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[258]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#let&#39;s describe our data</span>
<span class="n">test_data</span><span class="o">.</span><span class="n">info</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>&lt;class &#39;pandas.core.frame.DataFrame&#39;&gt;
RangeIndex: 9731 entries, 0 to 9730
Data columns (total 12 columns):
 #   Column                      Non-Null Count  Dtype  
---  ------                      --------------  -----  
 0   person_age                  9731 non-null   int64  
 1   person_income               9731 non-null   int64  
 2   person_home_ownership       9731 non-null   object 
 3   person_emp_length           9449 non-null   float64
 4   loan_intent                 9731 non-null   object 
 5   loan_grade                  9731 non-null   object 
 6   loan_amnt                   9731 non-null   int64  
 7   loan_int_rate               8762 non-null   float64
 8   loan_percent_income         9731 non-null   float64
 9   cb_person_default_on_file   9731 non-null   object 
 10  cb_person_cred_hist_length  9731 non-null   int64  
 11  loan_status                 0 non-null      float64
dtypes: float64(4), int64(4), object(4)
memory usage: 912.4+ KB
</pre>
</div>
</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[259]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#changing categorizes to numericals</span>
<span class="n">clean_test</span> <span class="o">=</span> <span class="n">test_data</span><span class="o">.</span><span class="n">replace</span><span class="p">({</span><span class="s1">&#39;person_home_ownership&#39;</span><span class="p">:{</span><span class="s1">&#39;RENT&#39;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s1">&#39;MORTGAGE&#39;</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span> <span class="s1">&#39;OWN&#39;</span><span class="p">:</span><span class="mi">2</span><span class="p">,</span> <span class="s1">&#39;OTHER&#39;</span><span class="p">:</span><span class="mi">3</span><span class="p">},</span>
                                 <span class="s1">&#39;loan_intent&#39;</span><span class="p">:{</span><span class="s1">&#39;EDUCATION&#39;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s1">&#39;MEDICAL&#39;</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span> <span class="s1">&#39;VENTURE&#39;</span><span class="p">:</span><span class="mi">2</span><span class="p">,</span> <span class="s1">&#39;PERSONAL&#39;</span><span class="p">:</span><span class="mi">3</span><span class="p">,</span> <span class="s1">&#39;DEBTCONSOLIDATION&#39;</span><span class="p">:</span><span class="mi">4</span><span class="p">,</span> <span class="s1">&#39;HOMEIMPROVEMENT&#39;</span><span class="p">:</span><span class="mi">5</span><span class="p">,},</span>
                                 <span class="s1">&#39;loan_grade&#39;</span><span class="p">:{</span><span class="s1">&#39;A&#39;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s1">&#39;B&#39;</span><span class="p">:</span><span class="mi">1</span><span class="p">,</span> <span class="s1">&#39;C&#39;</span><span class="p">:</span><span class="mi">2</span><span class="p">,</span> <span class="s1">&#39;D&#39;</span><span class="p">:</span><span class="mi">3</span><span class="p">,</span> <span class="s1">&#39;E&#39;</span><span class="p">:</span><span class="mi">4</span><span class="p">,</span> <span class="s1">&#39;F&#39;</span><span class="p">:</span><span class="mi">5</span><span class="p">,</span> <span class="s1">&#39;G&#39;</span><span class="p">:</span><span class="mi">6</span><span class="p">},</span>
                                 <span class="s1">&#39;cb_person_default_on_file&#39;</span><span class="p">:{</span><span class="s1">&#39;N&#39;</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span> <span class="s1">&#39;Y&#39;</span><span class="p">:</span><span class="mi">1</span><span class="p">}</span>
                                <span class="p">})</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[273]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#splitting our data</span>
<span class="n">a</span> <span class="o">=</span> <span class="n">clean_test</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;loan_status&#39;</span><span class="p">],</span><span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span> 
<span class="n">b</span> <span class="o">=</span> <span class="n">clean_test</span><span class="p">[</span><span class="s1">&#39;loan_status&#39;</span><span class="p">]</span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[274]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">b</span> <span class="o">=</span> <span class="n">model</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">X_test</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[280]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="n">b</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>[1 0 0 ... 0 0 0]
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><b> I have  predicted the values of loan_status which are shown above with the variable "b" </b></p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

     </div>
</div>
</div>
</div>

</div>
</body>







</html>
