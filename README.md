# Awesome list of Visual Studio Extensibility resources

I can't find any already existing awesome list about this topic. Thus, I'm starting it now.

## Extensions

VS extensions that are particulary useful when developing VS extensions:
* [Roslyn Clr Heap Allocation Analyzer](https://github.com/Microsoft/RoslynClrHeapAllocationAnalyzer) — Helps minimizing memory traffic (a.k.a. GC Pressure). Common cortesy for smaller extensions, neccessity for bigger extensions.

## Guidelines and publishing

* [Visual Studio Extensibility Checklist](https://gist.github.com/madskristensen/7310c0d61694e323f4deeb5a70f35fec) — A list of things to make sure to remember before publishing your Visual Studio extension.

## Integration

Specific areas to integrate into.

### Options (Settings)

* [Adding a WPF Settings Page To The Tools Options Dialog](https://blog.danskingdom.com/adding-a-wpf-settings-page-to-the-tools-options-dialog-window-for-your-visual-studio-extension/) — Unlike Windows Forms approach of the tutorial at the Microsoft Docs (former MSDN), this post offers using WPF instead.

## Performance

* [Building High Performance Extensions Part 1](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Building-High-Performance-Extensions-Part-1), [Part 2](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Building-High-Performance-Extensions-Part-2) — Testing (incl. Unit-, Integration-/System-, BDD), Exception Handling, Crash Analysis, Profiling, Optimization (Loading Performance, Memory Leaks, Memory Traffic).

## Awesome Roslyn (.NET Compiler Platform) lists
* [Awesome Roslyn](https://github.com/ironcev/awesome-roslyn)
* [Awesome Analyzers](https://github.com/Cybermaxs/awesome-analyzers)

## Undocumented API

* [MinimalisticView](https://github.com/poma/MinimalisticView) — Sample-like extension that overrides internal WPF styles in order to achieve its purpose.

# Other lists and hubs

* [Visual Studio Extensibility Samples](https://github.com/microsoft/VSSDK-Extensibility-Samples)
* [The official hub on extending VS](https://aka.ms/extendvs) — [Samples](https://docs.microsoft.com/ru-ru/visualstudio/extensibility/extensibility-hello-world), [Forum](https://gitter.im/Microsoft/extendvs), [Documentation](https://docs.microsoft.com/ru-ru/visualstudio/extensibility/starting-to-develop-visual-studio-extensions).
* [Carlos Quintero’s website about Visual Studio Extensibility](http://www.visualstudioextensibility.com/) — Vast majority of own articles, [links to documentation](http://www.visualstudioextensibility.com/documentation/), [links to articles](http://www.visualstudioextensibility.com/articles/), [links to samples](http://www.visualstudioextensibility.com/samples/) are still relevant even when seem like too old.
