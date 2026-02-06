# Contemporary_Chinese_History
Timeline of events in contemporary Chinese history.



How to add your own events: Everything is in the EVENTS array near the top of the <script> tag. Each event is a simple object:

```
{
    era: "Optional Section Header",     // shows a divider — omit if not needed
    date: "October 1, 1949",            // display string
    sortYear: 1949,                     // for chronological sorting
    title: "Founding of the PRC",
    category: "political",              // used for filtering
    notes: `<p>Your notes here...</p>`  // supports HTML
}
```
