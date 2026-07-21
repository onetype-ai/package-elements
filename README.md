# UI

The element library of the OneType platform. Forms, cards, charts, data views, navigation and status blocks — the shared visual language every package can build screens from.

Front-only package. Each element registers itself on the framework's `elements` addon via `onetype.AddonReady('elements', ...)`, so anything installed alongside it — the admin shell, the CMS, a custom package — picks the same vocabulary up automatically.
