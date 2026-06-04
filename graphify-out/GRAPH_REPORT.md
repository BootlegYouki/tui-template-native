# Graph Report - tui-template-native  (2026-06-04)

## Corpus Check
- 30 files · ~55,278 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 195 nodes · 259 edges · 26 communities (23 shown, 3 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `b0cde739`
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
- [[_COMMUNITY_Community 17|Community 17]]
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
4. `scripts` - 10 edges
5. `TUI Template Native (Expo / React Native)` - 5 edges
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

## Communities (26 total, 3 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.22
Nodes (7): ScreenType, styles, TuiTabBar(), TuiTabBarProps, TuiSkeletonLoader(), MainApp(), styles

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
Nodes (15): author, main, name, private, scripts, android, dev, format (+7 more)

### Community 5 - "Community 5"
Cohesion: 0.18
Nodes (11): devDependencies, eslint, @eslint/js, eslint-plugin-react-hooks, eslint-plugin-react-refresh, globals, prettier, @types/node (+3 more)

### Community 6 - "Community 6"
Cohesion: 0.17
Nodes (11): 1. Rename the Project, 2. Install Dependencies, 3. Launch Development Server, 📦 Automated iOS Release Pipeline, 🛠 Available Scripts, 🎨 Brutalist Design System (TUI), Core Components (`src/components/`), 🚀 Getting Started (+3 more)

### Community 7 - "Community 7"
Cohesion: 0.33
Nodes (6): styles, TuiContainer(), TuiContainerProps, styles, TuiText(), TuiTextProps

### Community 8 - "Community 8"
Cohesion: 0.15
Nodes (11): SPRING_CONFIG_OPEN, styles, TuiDrawer(), TuiDrawerProps, ACCENT_COLORS, AccentTheme, ThemeColors, ThemeContext (+3 more)

### Community 9 - "Community 9"
Cohesion: 0.40
Nodes (4): compilerOptions, strict, exclude, extends

### Community 14 - "Community 14"
Cohesion: 0.20
Nodes (7): appJsonPath, fs, packageJsonPath, path, rootDir, slug, workflowPath

### Community 17 - "Community 17"
Cohesion: 0.33
Nodes (5): MONTHS, styles, TuiCalendar(), TuiCalendarProps, WEEKDAYS

### Community 18 - "Community 18"
Cohesion: 0.50
Nodes (3): IconSvg(), SplashIcon(), SplashIconProps

### Community 19 - "Community 19"
Cohesion: 0.50
Nodes (3): styles, TuiButton(), TuiButtonProps

### Community 20 - "Community 20"
Cohesion: 0.50
Nodes (3): styles, TuiCheckbox(), TuiCheckboxProps

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
- **127 isolated node(s):** `name`, `slug`, `version`, `orientation`, `icon` (+122 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `dependencies` connect `Community 3` to `Community 4`?**
  _High betweenness centrality (0.064) - this node is a cross-community bridge._
- **Why does `useTheme()` connect `Community 2` to `Community 0`, `Community 7`, `Community 8`, `Community 17`, `Community 19`, `Community 20`, `Community 21`, `Community 22`, `Community 23`?**
  _High betweenness centrality (0.034) - this node is a cross-community bridge._
- **Why does `devDependencies` connect `Community 5` to `Community 4`?**
  _High betweenness centrality (0.027) - this node is a cross-community bridge._
- **What connects `name`, `slug`, `version` to the rest of the system?**
  _127 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.08695652173913043 - nodes in this community are weakly interconnected._
- **Should `Community 3` be split into smaller, more focused modules?**
  _Cohesion score 0.06666666666666667 - nodes in this community are weakly interconnected._
- **Should `Community 4` be split into smaller, more focused modules?**
  _Cohesion score 0.125 - nodes in this community are weakly interconnected._