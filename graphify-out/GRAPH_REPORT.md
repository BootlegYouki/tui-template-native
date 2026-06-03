# Graph Report - tui-template-native  (2026-06-03)

## Corpus Check
- 25 files · ~35,918 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 162 nodes · 220 edges · 17 communities (14 shown, 3 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

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

## God Nodes (most connected - your core abstractions)
1. `useTheme()` - 27 edges
2. `TuiText()` - 13 edges
3. `expo` - 11 edges
4. `scripts` - 9 edges
5. `TUI Template Native (Expo / React Native)` - 5 edges
6. `TuiContainer()` - 4 edges
7. `🚀 Getting Started` - 4 edges
8. `ios` - 3 edges
9. `android` - 3 edges
10. `adaptiveIcon` - 3 edges

## Surprising Connections (you probably didn't know these)
- `MainApp()` --calls--> `useTheme()`  [EXTRACTED]
  App.tsx → src/theme/theme-provider.tsx
- `TuiCalendar()` --calls--> `useTheme()`  [EXTRACTED]
  src/components/tui-calendar.tsx → src/theme/theme-provider.tsx
- `TuiProgressMeter()` --calls--> `useTheme()`  [EXTRACTED]
  src/components/tui-chart.tsx → src/theme/theme-provider.tsx
- `TuiSegmentedMeter()` --calls--> `useTheme()`  [EXTRACTED]
  src/components/tui-chart.tsx → src/theme/theme-provider.tsx
- `TuiBarChart()` --calls--> `useTheme()`  [EXTRACTED]
  src/components/tui-chart.tsx → src/theme/theme-provider.tsx

## Communities (17 total, 3 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.10
Nodes (19): styles, TuiCheckbox(), TuiCheckboxProps, styles, TuiInput(), TuiInputProps, ScreenType, styles (+11 more)

### Community 1 - "Community 1"
Cohesion: 0.11
Nodes (18): backgroundColor, foregroundImage, adaptiveIcon, predictiveBackGestureEnabled, expo, android, icon, ios (+10 more)

### Community 2 - "Community 2"
Cohesion: 0.12
Nodes (23): styles, TuiButton(), TuiButtonProps, ChartItem, MeterSegment, styles, TuiBarChart(), TuiBarChartProps (+15 more)

### Community 3 - "Community 3"
Cohesion: 0.12
Nodes (17): dependencies, expo, expo-document-picker, expo-file-system, expo-font, @expo-google-fonts/jetbrains-mono, expo-sharing, expo-splash-screen (+9 more)

### Community 4 - "Community 4"
Cohesion: 0.13
Nodes (14): author, main, name, private, scripts, android, format, ios (+6 more)

### Community 5 - "Community 5"
Cohesion: 0.20
Nodes (10): devDependencies, eslint, @eslint/js, eslint-plugin-react-hooks, eslint-plugin-react-refresh, globals, prettier, @types/node (+2 more)

### Community 6 - "Community 6"
Cohesion: 0.18
Nodes (10): 1. Rename the Project, 2. Install Dependencies, 3. Launch Development Server, 📦 Automated iOS Release Pipeline, 🛠 Available Scripts, 🎨 Brutalist Design System (TUI), Core Components (`src/components/`), 🚀 Getting Started (+2 more)

### Community 7 - "Community 7"
Cohesion: 0.33
Nodes (5): MONTHS, styles, TuiCalendar(), TuiCalendarProps, WEEKDAYS

### Community 8 - "Community 8"
Cohesion: 0.40
Nodes (4): SPRING_CONFIG_OPEN, styles, TuiDrawer(), TuiDrawerProps

### Community 9 - "Community 9"
Cohesion: 0.40
Nodes (4): compilerOptions, strict, exclude, extends

### Community 14 - "Community 14"
Cohesion: 0.20
Nodes (7): appJsonPath, fs, packageJsonPath, path, rootDir, slug, workflowPath

## Knowledge Gaps
- **105 isolated node(s):** `name`, `slug`, `version`, `orientation`, `icon` (+100 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `useTheme()` connect `Community 2` to `Community 0`, `Community 8`, `Community 7`?**
  _High betweenness centrality (0.042) - this node is a cross-community bridge._
- **Why does `dependencies` connect `Community 3` to `Community 4`?**
  _High betweenness centrality (0.040) - this node is a cross-community bridge._
- **Why does `devDependencies` connect `Community 5` to `Community 4`?**
  _High betweenness centrality (0.025) - this node is a cross-community bridge._
- **What connects `name`, `slug`, `version` to the rest of the system?**
  _105 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.10153846153846154 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.10526315789473684 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.11822660098522167 - nodes in this community are weakly interconnected._