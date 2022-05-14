
----

====
uOffice enhancement proposal #1
====

There were feature proposals before this, but they weren't known as enhancement proposals yet. They will be added in the future.

----
uOffice highlighter
----

* Solid highlighting (the default option already present in most Rich Text office software)
* Gradient highlighting (the same as solid color, except not solid color, but with gradient)
* Pattern highlighting (the same as gradient, except not gradient, but with an image pattern)

----
Highlighter code:
----

``<hl-s>`` - Solid highlighting 

**Usage:**

``<hl-s-id="#XXID"">Lorem ipsum</hl-s>``

``<hl-g>`` - Gradient highlighting

**Usage:**

``<hl-g-id="#XXID">Sample text</hl-g>``

``<hl-p>`` - Pattern highlighting

**Usage:**

``<hl-p-id="#XXID">Bottom text</hl-p>``

----
Highlighter subcodes:
----

**Solid color:** defined in ``style.scss``, ``style.less``, or ``style.css`` with SVG formatting (just for the color code)
**Gradient:** defined in ``style.scss``, ``style.less``, or ``style.css`` with SVG formatting (just for the color code range)
**Pattern:** defined in ``style.scss``, ``style.less``, or ``style.css`` with SVG formatting (just for the repeating image pattern)

----

**Thought of on:** ``2022, Friday, May 13th at 12:24 am PST``

**First draft finished on:** ``2022, Friday, May 13th at 12:38 am PST``

**Current draft version:** ``1 (2022, Friday, May 13th at 12:38 am PST)``

**Format:** ``ReStructuredText document (*.rst)``

**Line count (including blank lines and compiler line):** ``65``

**Original EP language:** ``English (US)``

**Author:** ``@seanpm2001 (Sean Patrick Myrick)``

----
