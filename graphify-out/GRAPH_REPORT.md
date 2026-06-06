# Graph Report - tui-template-native  (2026-06-06)

## Corpus Check
- 28 files · ~16,371 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 192 nodes · 256 edges · 24 communities (20 shown, 4 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `7e5ee9b8`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]

## God Nodes (most connected - your core abstractions)
1. `useTheme()` - 29 edges
2. `TuiText()` - 14 edges
3. `expo` - 12 edges
4. `scripts` - 11 edges
5. `TUI Template Native (Expo / React Native)` - 6 edges
6. `splash` - 4 edges
7. `TuiContainer()` - 4 edges
8. `🚀 Getting Started` - 4 edges
9. `🎨 Brutalist Design System (TUI)` - 4 edges
10. `ios` - 3 edges

## Surprising Connections (you probably didn't know these)
- `MainApp()` --calls--> `useTheme()`  [EXTRACTED]
  App.tsx → src/theme/theme-provider.tsx
- `TuiButton()` --calls--> `useTheme()`  [EXTRACTED]
  src/components/tui-button.tsx → src/theme/theme-provider.tsx
- `TuiCalendar()` --calls--> `useTheme()`  [EXTRACTED]
  src/components/tui-calendar.tsx → src/theme/theme-provider.tsx
- `TuiProgressMeter()` --calls--> `useTheme()`  [EXTRACTED]
  src/components/tui-chart.tsx → src/theme/theme-provider.tsx
- `TuiSegmentedMeter()` --calls--> `useTheme()`  [EXTRACTED]
  src/components/tui-chart.tsx → src/theme/theme-provider.tsx

## Communities (24 total, 4 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.24
Nodes (6): ScreenType, styles, TuiTabBar(), TuiTabBarProps, MainApp(), styles

### Community 1 - "Community 1"
Cohesion: 0.09
Nodes (22): backgroundColor, foregroundImage, adaptiveIcon, predictiveBackGestureEnabled, expo, android, icon, ios (+14 more)

### Community 2 - "Community 2"
Cohesion: 0.24
Nodes (10): ChartItem, MeterSegment, styles, TuiBarChart(), TuiBarChartProps, TuiProgressMeter(), TuiProgressMeterProps, TuiSegmentedMeter() (+2 more)

### Community 3 - "Community 3"
Cohesion: 0.07
Nodes (30): dependencies, expo, expo-av, expo-camera, expo-clipboard, expo-dev-client, expo-device, expo-document-picker (+22 more)

### Community 4 - "Community 4"
Cohesion: 0.12
Nodes (16): author, main, name, private, scripts, android, dev, fix-assets (+8 more)

### Community 5 - "Community 5"
Cohesion: 0.18
Nodes (11): devDependencies, eslint, @eslint/js, eslint-plugin-react-hooks, eslint-plugin-react-refresh, globals, prettier, @types/node (+3 more)

### Community 6 - "Community 6"
Cohesion: 0.15
Nodes (12): 1. Rename the Project, 2. Install Dependencies, 3. Launch Development Server, 🎨 App Icon & Splash Screen Assets Regeneration, 📦 Automated iOS Release Pipeline, 🛠 Available Scripts, 🎨 Brutalist Design System (TUI), Core Components (`src/components/`) (+4 more)

### Community 7 - "Community 7"
Cohesion: 0.40
Nodes (4): SPRING_CONFIG_OPEN, styles, TuiDrawer(), TuiDrawerProps

### Community 8 - "Community 8"
Cohesion: 0.10
Nodes (17): MONTHS, styles, TuiCalendar(), TuiCalendarProps, WEEKDAYS, styles, TuiContainer(), TuiContainerProps (+9 more)

### Community 9 - "Community 9"
Cohesion: 0.40
Nodes (4): compilerOptions, strict, exclude, extends

### Community 14 - "Community 14"
Cohesion: 0.20
Nodes (7): appJsonPath, fs, packageJsonPath, path, rootDir, slug, workflowPath

### Community 19 - "Community 19"
Cohesion: 0.50
Nodes (3): styles, TuiButton(), TuiButtonProps

### Community 20 - "Community 20"
Cohesion: 0.33
Nodes (5): styles, TuiCheckbox(), TuiCheckboxProps, TuiText(), TuiTextProps

### Community 21 - "Community 21"
Cohesion: 0.50
Nodes (3): styles, TuiHeader(), TuiHeaderProps

### Community 22 - "Community 22"
Cohesion: 0.50
Nodes (3): styles, TuiInput(), TuiInputProps

### Community 23 - "Community 23"
Cohesion: 0.50
Nodes (3): styles, TuiSwitch(), TuiSwitchProps

## Knowledge Gaps
- **129 isolated node(s):** `name`, `slug`, `version`, `orientation`, `icon` (+124 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **4 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `dependencies` connect `Community 3` to `Community 4`?**
  _High betweenness centrality (0.067) - this node is a cross-community bridge._
- **Why does `useTheme()` connect `Community 2` to `Community 0`, `Community 7`, `Community 8`, `Community 19`, `Community 20`, `Community 21`, `Community 22`, `Community 23`?**
  _High betweenness centrality (0.035) - this node is a cross-community bridge._
- **What connects `name`, `slug`, `version` to the rest of the system?**
  _129 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.08695652173913043 - nodes in this community are weakly interconnected._
- **Should `Community 3` be split into smaller, more focused modules?**
  _Cohesion score 0.06666666666666667 - nodes in this community are weakly interconnected._
- **Should `Community 4` be split into smaller, more focused modules?**
  _Cohesion score 0.11764705882352941 - nodes in this community are weakly interconnected._
- **Should `Community 8` be split into smaller, more focused modules?**
  _Cohesion score 0.10476190476190476 - nodes in this community are weakly interconnected._