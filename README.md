# ganttplay

## Why?

I like to use existing tools as much as possible, but cannot find one that does
what I need, so here is an attempt at hacking one together.

## What?

- Produces gantt charts based on text file data
- Supports text file format that works with git workflows, so one task per line
- Generates charts based on data without having to drag/click with mouse
- Optionally renders multiple tasks on the same row
- Outputs schedules in png format
- Produces plan on a page
- Supports logic linking of tasks, so that if the start-date or duration of one
  task is changed, any other task that is linked to it changes automatically
- Reads a per schedule config file to set start/finish dates, style and so on.
- Does not require massive dependencies
- Does not support critical path analysis, resource profiling, earned value,
  S-curves and network diagrams.

## The Obligatory Screenshot

<img src="scrot.png"/>
