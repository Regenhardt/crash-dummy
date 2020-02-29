# Crash dummy

To crash VS2019:
- Open the solution (which is basically the default blazor wasm template plus one line)
- Open FetchData.razor
- Put cursor at the beginning of line 14
- Type @if()
- Watch as VS2019 shows a line about an InvalidOperationException and a log file, freezes, and crashes a few seconds after that.