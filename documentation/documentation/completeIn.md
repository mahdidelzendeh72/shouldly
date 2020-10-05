# ShouldCompleteIn

<!-- snippet: ShouldCompleteInExamples.ShouldCompleteIn.codeSample.approved.cs -->
<a id='snippet-ShouldCompleteInExamples.ShouldCompleteIn.codeSample.approved.cs'></a>
```cs
Should.CompleteIn(
                    action: () => { Thread.Sleep(TimeSpan.FromSeconds(2)); },
                    timeout: TimeSpan.FromSeconds(1),
                    customMessage: "Some additional context");
```
<sup><a href='/src/DocumentationExamples/CodeExamples/ShouldCompleteInExamples.ShouldCompleteIn.codeSample.approved.cs#L1-L4' title='File snippet `ShouldCompleteInExamples.ShouldCompleteIn.codeSample.approved.cs` was extracted from'>snippet source</a> | <a href='#snippet-ShouldCompleteInExamples.ShouldCompleteIn.codeSample.approved.cs' title='Navigate to start of snippet `ShouldCompleteInExamples.ShouldCompleteIn.codeSample.approved.cs`'>anchor</a></sup>
<!-- endSnippet -->


**Exception**

<!-- include: ShouldCompleteInExamples.ShouldCompleteIn.exceptionText.approved.txt -->
```

Delegate
    should complete in
00:00:01
    but did not

Additional Info:
    Some additional context
```
<!-- endInclude -->