# Taaabs-Trace-Timeline-Docker

`<taaabs-trace-timeline-docker>` is a component that embeds a trace timeline, an obsel explorer, a model explorer and a stylesheet editor.
This component helps the navigation in a trace through a timeline. The stylesheet can be materialized
into a [custom method](https://kernel-for-trace-based-systems.readthedocs.io/en/latest/methods/hrules.html)
to apply on any other trace respecting the same trace model.

## Examples

#### Classic use:

    <taaabs-trace-timeline-docker trace-url="https://your.ktbs.com/ktbs"
                                  auto-launch
                                  language="fr">
    </taaabs-trace-timeline-docker>

#### Using class-style constructor:

    var elem = new TAAABS.TraceTimelineDocker();
    elem.set('traceUrl', "https://your.ktbs.com/ktbs");
    Polymer.dom(this.$['trace-timeline-target']).appendChild(elem);
    elem.refresh();


## Source files

[Github](https://github.com/TaaabsElements/taaabs-trace-timeline-docker)

## Todo
